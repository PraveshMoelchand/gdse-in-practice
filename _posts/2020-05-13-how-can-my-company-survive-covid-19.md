---
title: "How can my company survive through COVID-19? Think DISTRIBUTED! - Part 1"
header:
  overlay_image: /assets/images/splash-image.jpg
  overlay_filter: "0.5"
  caption: "Photo credit: [**NASA Earth Observatory/NOAA NGDC**](https://www.nasa.gov/mission_pages/NPP/news/earth-at-night.html)"
  show_overlay_excerpt: false
tags:
  - covid-19
  - meta
---

In December 2019, the novel coronavirus 2019-nCoV emerged in the Chinese city Wuhan. This infectious disease has rapidly become a global pandemic and caused major disruptions in our economical society. 
The lock-down measures prevented our normal way of working. 
Due to these lock-downs, most of us are not co-located (anymore) and face-to-face collaboration unfortunately became impossible. We are forced to stay home while continuing with our work. 

This situation may look very similar to Globally Distributed Software Engineering. GDSE is a discipline which focuses on distributed design, implementation and validation of software products and/or components. The ideas and research in GDSE are crucial now, since they can provide us with interesting insights on how distributed workspaces and projects can be organized. 
In this blogpost we will talk about some principles in GDSE; whether they can be applied to the era of COVID-19 lock-down and provide some guidance.

## Distances
In GDSE, there are four environmental/external factors that are well studied: Geographical, Temporal, Language and Cultural. 
While all four factors are closely related, researchers study these factors independently, since they do not necessarily occur together. 
Therefore, we think this will be a very interesting point for SE teams to look at!

### Geographical  
GDSE usually takes place at least two geographic locations on at least different two continents. 
While coronavirus does not instantly send your colleagues/employees to other sides of the globe , the lockdown measures prohibits any physical (face-to-face) meetings.
Therefore, a link between geographical distance and a COVID-19 lockdown is not far-fetched.

Interestingly, while geographic distance seems to be a very serious problem in GDSE, the effects of geographic distance on coordination and collaboration have 
not been conclusively determined [1]. Some researchers concluded that many of the observed distance are due to factors other than the simple geographical distance [2]. 
Others, such as Hinds [3], state that face-to-face communication is much more effective. Nevertheless, the importance of coordination and planning are well stated in all of these papers.
Therefore, it is crucial to clarify distribution of goals, tasks, and responsibilities during these times. 
The dependency between teams should also be minimized if possible.

### Cultural and Language
Language distance (native vs non-native) causes misunderstandings and lesser speaker acceptance due to unfamiliar
accents in spoken language [1]. 
This effect can also be caused by the cultural distances. 
However, cultural distances can be more damaging, since it can lead to (different) ways of task execution, 
management styles or even increased conflict potential. 
While this can happen anywhere and is not necessarily unique to GDSE, the lack of physical meetings and communication 
(Allen Curve) amplifies the problem. To add insult to injury, some studies and surveys indicate that 
COVID-19 lockdowns lead to more tension and stress [reference link to news article]. 

There are several studies on how to narrow language and culture distances. 
Similar to geographical distance, most researchers again put emphasis on documentation and planning for the 
project. However, increasing informal communication seemed to be effective in narrowing the distance as well. 
For example, the management/team leaders can organize team members for cultural differences with online team-building 
projects or do daily coffee stands. 
These informal meet-ups should reduce the tension and stress between members! [^reference]

### Temporal
Temporal distances are also often called timezone distances.
This is very unlikely to occur during COVID-19 lockdowns.
Therefore, we shouldn't worry too much about it.

## Internal Factors
Beside the external factors, there are also internal factors which we have to consider. These 4 factors are: project's organizational structure, the development process, communication and collaboration issues. Compared to external factors, internal factors can be controlled by project managers in to some extent.


## How to solve it?
The paper *"How to go global: A transformative process model for the transition towards globally distributed software development projects"* [^ref1] has provided us an extensive (but not comprehensive) recommendation on how to overcome these internal and external factors succesfully. Every factor is divided into smaller challenges, for each challenges, several recommendations are provided. We won't go into the details, but the general recommendation are:

1. Divide task clearly, let everyone know what they and their peers are doing.
2. Keep tracks of the progress: this can be done with frequent meetings.
3. Ensure an universal understanding of the requirement and update documents frequently.
4. Prepare your team-members for cultural differences and avoid negative stereotyping.


## Conclusion
In this blogpost we have discussed 4 internal and external factors for globally distributed software process and if they are applicable for GDSE. Furthermore, we have provided some well-researched recommendations which may help you to improve the current workspace.

[^ref1] How to go global: A transformative process model for the transition towards globally distributed software development projects [link](https://pdf.sciencedirectassets.com/271951/1-s2.0-S0263786319X00083/1-s2.0-S0263786318309669/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAgaCXVzLWVhc3QtMSJGMEQCIF87DZzwSYib8MVrXrpMrbRO1DQfcKAjRkh0dnANmWttAiBzVC2UMEVYW8FH90xrI%2BTc8PMeYHOumzvDeg8zo%2BG2hyq0AwhQEAMaDDA1OTAwMzU0Njg2NSIMKnjQmIs0XN6XS4g0KpEDPFNwptiqsOdAo6Kz2Pm9x50ZSLapgl1DwDg8x4M82zMwrfPc6f%2BnEG6CMKMxp6AhCM7AURFoT3DiUhHHCVA4AAkGnTCrYNWYKhWIEKRDofOmuvjdDkDoIbE0B4k4eZko2LbAgmgmcYX8o1%2FKiAsFxBP%2FTEt0Wd9Ifu5Tt%2BD5AqxvWg49oY4kxqtgI7fTo5LdUtGUwsSAQjcEA4udurt%2B6k8WEmERel54hqaoCbiwF2wxwLDEXrZzcS%2BMpszn3VCXTf%2BVQF1f9kr2MnGQjPawRgjXZprBVsFFX2WQZpsa%2FMb6KyfpqQduzY1MMyE1m2%2BHC8JG6ls1%2BJq%2BIJVWf%2FrXnh4ZdGHHHzBlLJ8igWeT%2Fh6cQncw2pNhmKsj%2F%2B%2BBcySynmEh2rhZFgq7zfZKEBJgohf%2ByYvXPjvADjslGTqCxJqdHTvomWAom2eE%2BhNeMIzObKntFiMCJPHFWTwtP%2Fk8otdcYnRunPIY8jpavRoq6jnRmUdySKiwXBu0SYLpKHIWIvo0R5P2w7KF0wdP2r8Sifgw%2F9zs9QU67AEMJ92MLmNz0pBo7%2B6UCIWgDYgzan%2Bcd8z9rvpsH4Uf7bhMOpPtue2JQhZXQ8X1PIT9JPwshPL0bXSDH09CDUYt5CK6ZnpXEbACFo%2Bz9Jn4TYzpvXsE6%2FapGYpLmMruesOhRSlk61zZwlw6D9YxgonBRaCNRSlu6AdZydG5JhVw6VSEf5QB3j08AXZYKvAMqCA3fa2U9QeUcLH%2FmchhxTKjA%2FBT6EWseBk3ObugOfJJdzDcuLeYVMkVOe6yM%2BvMALbXEHT7zaLXNCkudQi0nN5ORxjhOacADysZdQlTu3OG1Ov0FGorIZNKgzH6%2BQ%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20200512T235707Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY5N2XSWWS%2F20200512%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=0157e8a1fc0f4a0c6ac5a1678dff3b487c515737d474eed5c4c746be4b5a8b9d&hash=bd1bc89d52bb64c099b70779da6ddb175175dfba32db3eaaad0ace907a05640c&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0263786318309669&tid=spdf-7ef9a53e-0158-41ce-aa8d-16c3f84ec1c2&sid=adb37992898b80416f29462-0b950967e593gxrqb&type=client](https://pdf.sciencedirectassets.com/271951/1-s2.0-S0263786319X00083/1-s2.0-S0263786318309669/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAgaCXVzLWVhc3QtMSJGMEQCIF87DZzwSYib8MVrXrpMrbRO1DQfcKAjRkh0dnANmWttAiBzVC2UMEVYW8FH90xrI%2BTc8PMeYHOumzvDeg8zo%2BG2hyq0AwhQEAMaDDA1OTAwMzU0Njg2NSIMKnjQmIs0XN6XS4g0KpEDPFNwptiqsOdAo6Kz2Pm9x50ZSLapgl1DwDg8x4M82zMwrfPc6f%2BnEG6CMKMxp6AhCM7AURFoT3DiUhHHCVA4AAkGnTCrYNWYKhWIEKRDofOmuvjdDkDoIbE0B4k4eZko2LbAgmgmcYX8o1%2FKiAsFxBP%2FTEt0Wd9Ifu5Tt%2BD5AqxvWg49oY4kxqtgI7fTo5LdUtGUwsSAQjcEA4udurt%2B6k8WEmERel54hqaoCbiwF2wxwLDEXrZzcS%2BMpszn3VCXTf%2BVQF1f9kr2MnGQjPawRgjXZprBVsFFX2WQZpsa%2FMb6KyfpqQduzY1MMyE1m2%2BHC8JG6ls1%2BJq%2BIJVWf%2FrXnh4ZdGHHHzBlLJ8igWeT%2Fh6cQncw2pNhmKsj%2F%2B%2BBcySynmEh2rhZFgq7zfZKEBJgohf%2ByYvXPjvADjslGTqCxJqdHTvomWAom2eE%2BhNeMIzObKntFiMCJPHFWTwtP%2Fk8otdcYnRunPIY8jpavRoq6jnRmUdySKiwXBu0SYLpKHIWIvo0R5P2w7KF0wdP2r8Sifgw%2F9zs9QU67AEMJ92MLmNz0pBo7%2B6UCIWgDYgzan%2Bcd8z9rvpsH4Uf7bhMOpPtue2JQhZXQ8X1PIT9JPwshPL0bXSDH09CDUYt5CK6ZnpXEbACFo%2Bz9Jn4TYzpvXsE6%2FapGYpLmMruesOhRSlk61zZwlw6D9YxgonBRaCNRSlu6AdZydG5JhVw6VSEf5QB3j08AXZYKvAMqCA3fa2U9QeUcLH%2FmchhxTKjA%2FBT6EWseBk3ObugOfJJdzDcuLeYVMkVOe6yM%2BvMALbXEHT7zaLXNCkudQi0nN5ORxjhOacADysZdQlTu3OG1Ov0FGorIZNKgzH6%2BQ%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20200512T235707Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY5N2XSWWS%2F20200512%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=0157e8a1fc0f4a0c6ac5a1678dff3b487c515737d474eed5c4c746be4b5a8b9d&hash=bd1bc89d52bb64c099b70779da6ddb175175dfba32db3eaaad0ace907a05640c&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0263786318309669&tid=spdf-7ef9a53e-0158-41ce-aa8d-16c3f84ec1c2&sid=adb37992898b80416f29462-0b950967e593gxrqb&type=client))

[^2]  Team Knowledge and Coordination in Geographically Distributed Software Development [link](https://www.tandfonline.com/doi/abs/10.2753/MIS0742-1222240104)
[^3] What Do We Know about Proximity and Distance in Work Groups? [link](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.620.7087&rep=rep1&type=pdf)

[^allen] The farther apart workspaces are, the less communication there is between them. You can read more about it in https://en.wikipedia.org/wiki/Allen_curve