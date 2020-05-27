---
title: "Pair programming during COVID-19: right now is the perfect time to start"
header:
  overlay_image: /assets/images/pair-programming.png
  overlay_filter: "0.5"
  caption: "Photo credit: [**https://blog.daftcode.pl/pair-programming-demystified-730c6f0b145b**](https://blog.daftcode.pl/pair-programming-demystified-730c6f0b145b)"
  show_overlay_excerpt: false
tags:
  - covid-19
  - pair programming
---

It is 2020: pair programming has undoubtedly claimed its spot in modern software 
development. A number of scientific studies have shown that pair programming has 
an overal net positive effect on software quality[^1][^2], although there are 
exceptions[^3].

If you've been pair programming before the pandemic struck: good! This short post 
might help making your remote pair programming sessions more effective.

If pair programming is not engrained into your company-culture just yet: now is 
a great time to start! Really! This sounds counter-intuitive, but right now, with 
the whole engineering team working from home, pair programming is a perfect 
activity to stay in touch with your colleagues. It might just be the team-building 
activity that pulls your team through the pandemic. This article may help you 
convince your manager or team-lead and help you get started.

A word of warning: contrary to "co-located" pair programming, remote pair 
programming has received relatively little attention from the scientific community. 
Some of this is uncharted territory. Therefore, YMMV. Nevertheless, we've tried 
to compose this little blog post in which we outline how to perform remote pair 
programming *successfully*, using studies from the field of Globally Distributed
Software Engineering.

## What elements make co-located pair programming successful?

In his 1998 paper "Side-by-side collaboration" [^4] Nick V. Flor investigates the
 properties that effective pairs all share:

- The search through a larger space of alternatives
- Efficient communication
- Ongoing sharing of goals and plans
- Joint production of ambiguous plan segments
- Reuse of system knowledge
- Shared memory for old plans
- The ability to dynamically incorporate new divisions of labor and collaborative 
interaction systems

For remote pair programming to be just as effective as co-located programming it 
is required that the remote pairs internalize these properties.
Following up on his original paper, Flor notes that a remote workspace must reinforce 
and endorse, not complicate, the properties listed above. This is tough, because 
the implicit information infrastructure that we take for granted when working 
in close proximity is hard to replicate in a remote setting[^5].

## That sounds like it won't work

While we would love to debunk the statement above by overloading you with scientific
articles and evidence: we can't. There are few case studies on remote pair 
programming on actual industry software engineering teams. 
Few is not the same as none, however! One case study on a distributed software 
engineering team found the following benefits when using distributed pair 
programming for a project[^6]:

*Enjoyment*. The team members had more joy writing software, simply because of 
the increased social interaction. This seems minor, but the impact of unhappy 
developers is immeasurable[^7].

*Courage & Confidence*. Team members noted that they were quicker to refactor 
code, which in turn increased their confidence in the code base, leading to 
happier developers.

*Increased Quality*. Pair programming caused the developers to implement unit, 
integration and UI tests where they might have skipped them otherwise (we all 
have been there).

*Increased trust*. As the pairs progressed through the project, they learned to 
trust each others abilities more.

*Knowledge transfer*. Two programmers know more than one: by pairing them they
are able to transfer eachothers knowledge more (effectively) than they would 
have done otherwise.

Convinced yet? Good! [Over here](https://github.com/kkemple/awesome-pair-programming)
is a great list of tools and resources that you can use to start pair programming remotely,
right now. We also have a [blog post](https://www.gdse-in-practice.com/blog/tools-for-distributed-communication/)
in which we explore effective tools that you can use during the pandemic.



[^1]: Williams, L., Kessler, R., Cunningham, W., and Jeffries, R. Strengthening the case for pair programming. IEEE Software 17(2000), 19–25.
[^2]: F. Padberg and M. M. Muller, "Analyzing the cost and benefit of pair programming," Proceedings. 5th International Workshop on Enterprise Networking and Computing in Healthcare Industry (IEEE Cat. No.03EX717), Sydney, NSW, Australia, 2003, pp. 166-177, doi: 10.1109/METRIC.2003.1232465.
[^3]: Hanna Hulkko and Pekka Abrahamsson. 2005. A multiple case study on the impact of pair programming on product quality. In Proceedings of the 27th international conference on Software engineering (ICSE ’05). Association for Computing Machinery, New York, NY, USA, 495–504. DOI:https://doi.org/10.1145/1062455.1062545
[^4]: FLOR, N. 1998. Side-by-side collaboration: a case study. International Journal of Human-Computer Studies 49, 3, 201-222.
[^5]: Nick V. Flor. 2006. Globally distributed software development and pair programming. Commun. ACM 49, 10 (October 2006), 57–58. DOI:https://doi.org/10.1145/1164394.1164421
[^6]: Mark Rajpal. 2018. Effective distributed pair programming. In Proceedings of the 13th International Conference on Global Software Engineering (ICGSE ’18). Association for Computing Machinery, New York, NY, USA, 6–10. DOI:https://doi.org/10.1145/3196369.3196388
[^7]: D. Graziotin, F. Fagerholm, X. Wang and P. Abrahamsson. 2018. What happens when software developers are (un)happy. Journal of Systems and Software 140, 32-47. DOI:https://doi.org/10.1016/j.jss.2018.02.041
