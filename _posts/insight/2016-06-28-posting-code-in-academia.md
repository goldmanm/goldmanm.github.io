---
layout: layout-post
title: sharing research code
summary: reasons, motivations, resources
source: /app/posts/insight/code
preview-img : /app/posts/insight/code/preview.jpeg
preview-css : post-preview-std post__imgPreview--dark
category : insight
tags : [computation, academia, value creation, value capture]
published : true
portfolio : false
comments : false
featured : false
type : blog
---

In the [previous post]( {{sit.url}}/blog/2016/05/value-capture.html) on the concepts of academics, I mention insentives in industry. Like the business world, the value capture in academia is sometimes adverse to value creation. To many academics, value creation is increasing the world's knowledge on a topic. Value capture is often obtained by prestigious achievements, like a Nobel, big research grant, or getting published in a prestigious journal or write a manuscript. Issues with publication issues are widely publicized. The most populacized are when [scientists fake results](http://www.latimes.com/science/sciencenow/la-sci-sn-stap-stem-cell-suicide-20140805-story.html). Besides outright faking, scientists often select results to publish or not publish, based on percieved citations, and can change analyisis methods to obtain more significant sounding results. [Wikipedia](https://en.wikipedia.org/wiki/Publication_bias) has a great summary of these issues, lumped together as publication bias. One additional issue, not focused in these articles, is publishing of code. Here I discuss to issues potentially inhibiting the publication of code, which I have personally experienced in my first two years of grad school.

### 1. messiness

Just when I joined my research group, a post-doc was heading out to become a professor. Ten months later, a grad student in our same group wanted to build upon his work. He got access to the code from our server, but couldn't understand any of the messy scripts. He emailed the former post-doc about the code and the author responded that *he* would rewrite the entire code if he had to work on the project again. The code was not even clear enough for the author to go back to.

My colleague decided to rewrite the code, and has spent months to get understandable, working code that can replicate the results and understand any program errors. He's made considerable progress and hopefully can move forward with the project soon. 

I can only speculate why some academic code is so messy. Discovery is often not clear from the start, so maybe the mess results from trial and error. Though businesses have the same issues with uncertainty, the large-scale nature of commercial probably necessitates better coding practices. Many academics may not have desire or time to have coordinated, clear code. Regardless of the reason, messy code happens, and we deal with it. 

### 2. hidden code

For the code that isn't as messy as in the previous case, research could use and build upon it. This is necessary for work comparing different analysis methods. There is some analysis on increased publication impact from having open data,[^4] though I am not sure the community embraces the idea. [stack exchange](http://academia.stackexchange.com/questions/10247/why-are-cs-researchers-reluctant-to-share-code-and-what-techniques-can-i-use-to) has a short discussion on it, where some assert the main reason is essentially having messy, unusable code. There are cases, however, where people do not want to share code. 

I experienced not able to access code to test a method for application to my work on chemical cycles. The method was written 6 years ago, and had numerous publications by one group. No public code seemed to exist for the method, so I tried to approximate the method using the Jacobian from [Cantera](http://www.cantera.org). Unnfortuantely my re-creation of the method failed near ignition due to non-linearities, so I moved onto other approaches. Last week, I met a member of the group who works on it. According to him, the professor keeps the evaluation of a critical piece to himself and runs his students' calculations when they need him to. The student I talked to hasn't even seen the code that analyzes a part of the topic he's working on. There are likely valid reasons why the PI doesn't share his code with his students or others, though it is still a cause of inconvience preventing the utilization of the excellent methods he developed.

Not ironically (ok. a little ironically), a method to do the same thing recently appeared on [github](http://www.github.com), and the authors encourage collaboration. If I see the benefit of the method, I'll probably be collaborating with the authors of the open code, so that others can build off my scientific contributions. 

In a business environment, hiding code is often a method to keep a competitive advantage. For example, Google's current algorythem for search is secretely locked away so they can continue to profit and grow, which doesn't contradict their goal of providing searches and services for users. In an academic environment, having secretive code seems to contradict furthering science. Having the objective and reward mechanism at add odds can really jepordize the value creation aspect (see [previous post]({{sit.url}}/blog/2016/05/value-capture.html)). Granted, some professors, especially at places like MIT, may want to commercially develop the code, which gives a different set of value creation principles.

The general sharing of code is not that common. In a meta-analysis, Prof. West found that only thirteen papers in the 2013 Combustion Institute had supplemental code of chemical mechanisms in the standard Chemkin format, so others could easily replicate and extend upon their results.

### the way forward

Making code usable by others does take time, but it can also save the authors' time by allowing effective reuse of code, though I am unsure whether the time savings themselves are worth it. Since motivation is primarily about perception, it seems like the perceived effort of creating good code  could be inhibiting writing good code. 

Getting computational researchers to create readable and sharable code could improve the pace of research, and more options than ever exist for this to happen. Prof. Noble has a [good framework](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000424) describing how to organize computational code, which has some interesting ideas.  I currently use [GitHub](http://www.github.com) to store and share my scripts. When publishing my next work, I will store my scripts in the [Open Data Framework](https://osf.io/) or MIT's [DSpace](https://dspace.mit.edu/).

Getting others to value producing reusable code might benefit from shifting the value capture element. Many approaches could encourage this. People could value citations more, as reusable ideas are likely to get more cited and built upon.[^4] Journals could require open code for publication, which could improve their impact factor. Some Journals have already made requirements of utilizing online resources to validate methodology in psychology, so it doesn't seem impossible. If you think of other ideas to encourage the writing of good code and sharing it, [email me](markgoldman@mit.edu).

### resources 

* [Nature article about publishing of code](http://www.nature.com/news/2010/101013/full/467753a.html)
* [presentation comparing code publishing to proof publishing](http://faculty.washington.edu/rjl/talks/LeVeque_CSE2011.pdf)

[^4]: Piwowar HA, Day RS, Fridsma DB (2007) Sharing Detailed Research Data Is Associated with Increased Citation Rate. PLoS ONE 2(3): e308. doi:10.1371/journal.pone.0000308

<!-- old text:

Personally, I've found subtler discrepancies between value creation and value capture more inhibiting in my field of computational chemical informatics. Many papers exist for new methods of analyzing complex chemical systems which never mention or share the code used for the analysis. [......] authors may see some benefit by hiding code to requiring others to rewrite the method, so they can publish more papers and stay ahead of other groups, though I do not think this is the reason for most papers.

Many researchers just have terribly messy code, which the authors struggle to use after the paper is published. I recently looked into someone's code for a method I was interested in. The author said there was a 'high learning curve'. The documentation was a 138 page file of method headers, which meant the code wasn't commented, and it seemed extremely messy. For another paper, my group member emailed the author of the paper and code, who recommended that he would probably rewrite the code entirely if he had to work on the project again. His goal was to publish papers and could deal with the messy code while it was fresh in his mind. 


It doesn't seem like academia is immune to gaps in value creation and capture. We have mitigated the extreme examples of forgery, so maybe we could focus more on prevalent and subtle inefficiencies. 

-->

<!--other things not mentioned:

I find the quantification of value creation a sticky issue. 

write about KI encouraging reporting of environmental issues

In Market-Based Management, Charles Koch asserts that the free-market incentives for companies can also be applied to people working in a company. While I am not convinced of all the assertions that lead to this conclusion, treating people like this 
-->

Note: the [code photo](https://unsplash.com/photos/xekxE_VR0Ec) was taken by Markus Spiske and is licensed under cc0
