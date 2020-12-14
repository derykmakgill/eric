---
layout: essay
title: Purists versus Pragmatists
meta: Originally posted on 14 Jun 2003. Thanks to Martin Fowler and Kent Beck for insightful comments.
---

At the heart of the historical development of computing is the age-old philosophical impasse between _purist_ and _pragmatist_ approaches to technology, which is particularly pronounced in software due to its seeming near-Platonic ineffability. One way to understand the distinction is through a dinnerware analogy.[![](https://1cv7ua4679w3p6rv53wmjvoh-wpengine.netdna-ssl.com/wp-content/uploads/2015/02/puristvbricolage75ppi.png)](https://1cv7ua4679w3p6rv53wmjvoh-wpengine.netdna-ssl.com/wp-content/uploads/2015/02/puristvbricolage75ppi.png)

Purist approaches, which rely on alluring visions, are like precious “good” china: mostly for display, and reserved exclusively for narrow uses like formal dinners. Damage through careless use can drastically lower the value of a piece. Broken or missing pieces must be replaced for the collection to retain its full display value. To purists, mixing and matching, either with humbler everyday tableware, or with different china patterns, is a kind of sacrilege.

The pragmatic approach on the other hand, is like unrestricted and frequent use of hardier everyday dinnerware. Damage through careless play does not affect value as much. Broken pieces may still be useful, and missing pieces need not be replaced if they are not actually needed. For pragmatists, mixing and matching available resources, far from being sacrilege, is something to be encouraged, especially for collaborations such as neighborhood potlucks.

In software, the difference between the two approaches is clearly illustrated by the history of the web browser.

On January 23, 1993, Marc Andreessen sent out a short email, announcing the release of Mosaic, the first graphical web browser:

> 07:21:17-0800 by marca@ncsa.uiuc.edu:
> 
> By the power vested in me by nobody in particular, alpha/beta version 0.5 of NCSA’s Motif-based networked information systems and World Wide Web browser, X Mosaic, is hereby released:
> 
> file://ftp.ncsa.uiuc.edu/Web/xmosaic/xmosaic-0.5.tar.Z

Along with Eric Bina  he had quickly hacked the prototype together after becoming enthralled by his first view of the World Wide Web, which Tim Berners-Lee had unleashed from CERN in Geneva in 1991\. Over the next year, several other colleagues joined the project, equally excited by the possibilities of the web. All were eager to share the excitement they had experienced, and to open up the future of the web to more people, especially non-technologists.

Over the course of the next few years, the graphical browser escaped the confines of the government-funded lab (the National Center for Supercomputing Applications at the University of Illinois) where it was born. As it matured at Netscape and later at Microsoft, Mozilla and Google, it steered the web in unexpected (and to some, undesirable) directions. The rapid evolution triggered both the legendary browser wars and passionate debates about the future of the Internet. Those late-nineties conflicts shaped the Internet of today.

To some visionary pioneers, such as Ted Nelson, who had been developing a purist hypertext paradigm called Xanadu for decades, the browser represented an undesirably messy direction for the evolution of the Internet. To pragmatists, the browser represented important software evolving as it should: in a pluralistic way, embodying many contending ideas, through what the Internet Engineering Task Force (IETF) calls “rough consensus and running code.”

While every major software project has drawn inspiration from both purists and pragmatists, the browser, like other pieces of software that became a mission critical part of the Internet, was primarily derived from the work and ideas of pragmatists: pioneers like Jon Postel, David Clark, Bob Kahn and Vint Cerf, who were instrumental in shaping the early development of the Internet through highly inclusive institutions like the IETF.

Today, the then-minority tradition of pragmatic hacking has matured into agile development, the dominant modern approach for making software. But the significance of this bit of history goes beyond the Internet. Increasingly, the pragmatic, agile approach to building things has spread to other kinds of engineering and beyond, to business and politics.

The nature of software has come to matter far beyond software. Agile philosophies are eating all kinds of building philosophies. To understand the nature of the world today, whether or not you are a technologist, it is crucial to understand agility and its roots in the conflict between pragmatic and purist approaches to computing.

The story of the browser was not exceptional. Until the early 1990s, almost all important software began life as purist architectural visions rather than pragmatic hands-on tinkering.

This was because early programming with punch-card mainframes was a highly constrained process. Iterative refinement was slow and expensive. Agility was a distant dream: programmers often had to wait weeks between runs. If your program didn’t work the first time, you might not have gotten another chance. Purist architectures, worked out on paper, helped minimize risk and maximize results under these conditions.

As a result, early programming was led by creative architects (often mathematicians and, with rare exceptions like Klari Von Neumann and Grace Hopper, usually male) who worked out the structure of complex programs upfront, as completely as possible. The actual coding onto punch cards was done by large teams of hands-on programmers (mostly women[<sup>1</sup>](#_ftn1)) with much lower autonomy, responsible for working out implementation details.

In short, purist architecture led the way and pragmatic hands-on hacking was effectively impossible. Trial-and-error was simply too risky and slow, which meant significant hands-on creativity had to be given up in favor of productivity.

With the development of smaller computers capable of interactive input hands-on hacking became possible. At early hacker hubs, like MIT through the sixties, a high-autonomy culture of hands-on programming began to take root. Though the shift would not be widely recognized until after 2000, the creative part of programming was migrating from visioning to hands-on coding. Already by 1970, important and high-quality software, such as the Unix operating system, had emerged from the hacker culture growing at the minicomputer margins of industrial programming.

Through the seventies, a tenuous balance of power prevailed between purist architects and pragmatic hackers. With the introduction of networked personal computing in the eighties, however, hands-on hacking became the defining activity in programming. The culture of early hacker hubs like MIT and Bell Labs began to diffuse broadly through the programming world. The archetypal programmer had evolved: from interchangeable member of a large team, to the uniquely creative hacker, tinkering away at a personal computer, interacting with peers over networks. Instead of dutifully obeying an architect, the best programmers were devoting increasing amounts of creative energy to scratching personal itches.

The balance shifted decisively in favor of pragmatists with the founding of the IETF in 1986\. In January of that year, a group of 21 researchers met in San Diego and planted the seeds of what would become the modern “government” of the Internet.

Despite its deceptively bureaucratic-sounding name, the IETF is like no standards organization in history, starting with the fact that it has no membership requirements and is open to all who want to participate. Its core philosophy can be found in an obscure document, _[The Tao of the IETF](https://www.ietf.org/tao.html),_ little known outside the world of technology_._ It is a document that combines the informality and self-awareness of good blogs, the gravitas of a declaration of independence, and the aphoristic wisdom of Zen koans. This oft-quoted section illustrates its basic spirit:

> In many ways, the IETF runs on the beliefs of its members.  One of the “founding beliefs” is embodied in an early quote about the IETF from David Clark: “We reject kings, presidents and voting.  We believe in rough consensus and running code”.  Another early quote that has become a commonly-held belief in the IETF comes from Jon Postel: “Be conservative in what you send and liberal in what you accept”.

Though the IETF began as a gathering of government-funded researchers, it also represented a shift in the center of programming gravity from government labs to the commercial and open-source worlds. Over the nearly three decades since, it has evolved into the primary steward[<sup>2</sup>](#_ftn2) of the inclusive, pluralistic and egalitarian spirit of the Internet. In invisible ways, the IETF has shaped the broader economic and political dimensions of software eating the world.

The difference between purist and pragmatic approaches becomes clear when we compare the evolution of programming in the United States and Japan since the early eighties. Around 1982, Japan chose the purist path over the pragmatic path, by embarking on the ambitious “fifth-generation computing” effort. The highly corporatist government-led program, which caused much anxiety in America at the time, proved to be largely a dead-end. The American tradition on the other hand, outgrew its government-funded roots and gave rise to the modern Internet. Japan’s contemporary contributions to software, such as the hugely popular Ruby language designed by Yukihiro Matsumoto, belong squarely within the pragmatic hacker tradition.

I will argue that this pattern of development is not limited to computer science. _Every_ field eaten by software experiences a migration of the creative part from visioning activities to hands-on activities, disrupting the social structure of all professions. Classical engineering fields like mechanical, civil and electrical engineering had already largely succumbed to hands-on pragmatic hacking by the nineties. Non-engineering fields like marketing are beginning to convert.

So the significance of pragmatic approaches prevailing over purist ones cannot be overstated: in the world of technology, it was the equivalent of the fall of the Berlin Wall.

---

[[1]](#_ftnref1) This distinction between high-autonomy architects and low-level programmers in the early days of computing is often glossed over in feel-good popular accounts of the role of women in early computing. This popular narrative conflates the high-level work of women like Klari von Neumann and Grace Hopper (the latter is in some ways the [zombie Marie Curie](https://xkcd.com/896/) of computing, whose totemic prominence somewhat obscures the contributions of other pioneering women) with the routine work of rank-and-file women programmers. By doing so, the popular narrative manages to overstate the creative contribution of women in the early days, and thereby, rather ironically, understates the actual misogyny of the 1940s-50s. This leads to a misleading narrative of decline from an imagined golden age of women in computing. A clearer indicator of the history of women in programming would be the rate of their participation in _interactive computing_, starting with the early 1960s hacker culture of the sort that developed at MIT around the earliest interactive minicomputers such as the PDP-1\. Measured against this baseline, I suspect the participation of women in _creative _hands-on programming has been steadily increasing from an early misogynistic low, and is likely significantly better than in other engineering fields. I do not, however, have the data to justify this claim.

[[2]](#_ftnref2) This rise, in terms of both institutional power and philosophical influence has, of course, attracted criticism. The most common criticism is the expected one from purists: that the IETF philosophy encourages incrementalism and short-term thinking. This sort of criticism is briefly addressed in these essays, but represents a fundamental philosophical divide comparable to the Left/Right divide in politics, rather than dissent within the pragmatic philosophy. There has also been actionable criticism within the pragmatic camp. For instance, Postel’s robustness principle cited above (“be conservative in what you send and liberal in what you accept”), has [been criticized by Joel Spolsky](http://www.joelonsoftware.com/items/2008/03/17.html) for creating chaos in standards efforts by allowing too much “soft failure.” This particular criticism is [being accommodated by the IETF](https://tools.ietf.org/html/draft-thomson-postel-was-wrong-00) in the form of the alternate “fail hard and fast” design principle.

