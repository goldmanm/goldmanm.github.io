---
layout: layout-post
title: Value capture and incentives
summary: in business and academia
source: /app/posts/insight/value-capture
preview-img : /app/posts/insight/value-capture/preview.jpeg
preview-css : post-preview-std post__imgPreview--dark
category : insight
tags : [MBA, business, computation, academia, value creation, value capture]
published : true
portfolio : false
comments : false
featured : false
type : blog
---

This past semester, I took an MIT Sloan class called [Entrepreneurial Strategy](http://student.mit.edu/catalog/search.cgi?search=15.911&style=verbatim&when=2&termleng=4). Through each lecture, this course drove deeper into fundamental business decisions of a start-up. Being my first business course, unknown more-general business concepts flew around the class. I found two of these concepts both mysteriously complex and fundamental: value creation and value capture. In the class context, value creation is the benefit to people created by the business. Value capture is how a venture collects value from the environment in order to sustain and grow. For example, Facebook provides values to users by connecting them and provides value to advertisers by allowing access to the users. Facebook captures value by charging the advertisers for targeted user access. Essential to this course is aligning value creation and value capture with other parts of your business to make a successful market entry.

### when revenue undermines a business creating value

The drive to make profit often leads companies to enhance their value capture, which often comes at the expense of creating value for consumers. This becomes detrimental when value creation becomes at odds with value capture, usually by finding some unexpected loophole. I'll explain an extreme example in history to give you an idea about when things aren't aligned at all. 

A hallmark of the colonial mindset is that the dominant power provides culture and investment to subjugated people and is also able to extract revenue from the territory. Setting aside the white supremacist undertones, these two items seem to misalign more than they align, which is one reason why colonialism was detrimental to most of the world's population. I recently just finished a book that dove into issues of the British East India Company (BEIC) in what is now Malaysia, Singapore and Brunei. During the early 20th century, the main revenue from the colonies was from selling opium to the countries inhabitants. The British actually would initially discount opium to encourage the addictive habit to a new population and then hike up the price to extract as much profit as possible. The encouragement of drug use for revenue directly contradicts the value creation goal of providing culture and investment to the area. Other examples of BEIC's colonial practices involved eliminating the local trading class by imposing a monopoly, not enforcing human trafficking laws (allowing forced labor), and using unjustified stereotypes to justify improper treatment.^[The Myth of the Lazy Native by Syad Alatas (1977)] Since value capture directly harms the native population's ability to live, cultures were damaged, not enriched, by colonialism. This is on the extreme of value capture being antagonistic to value creation, but many cases today are more subtle. 

Described in the movie 'The Big Short' (2015), the market collapse in 2008 was amplified by misaligned incentives. Brokers were rewarded by obtaining loans which the people couldn't reasonably afford. Sadly, commission did not correlate with loan quality, so agents encouraged people to sign up for unreasonable loans. Many people bought these sub-prime loans and the investment firms hid the risk, leading to the housing market collapse. 

Like the business world, the value capture in academia is sometimes adverse to value creation. To many academics, value creation is increasing the world's knowledge on a topic. Value capture is often obtained by prestigious achievements, like a Nobel, big research grant, or getting published in a prestigious journal. There are numerous BEIC-like examples where people publish fake results. To mitigate this extreme ethical breach, academic culture often shuns those caught faking results. 

### academics face the same issues

Personally, I've found the subtler discrepancies between value creation and value capture more inhibiting in my field of computational chemical informatics. Many papers describe new methods of analyzing complex chemical systems, but they fail to mention or share the code used for the analysis. Authors may see some benefit by hiding code which allows them more time to publish more papers and stay ahead of other groups. Though I think there may be another reason code is hidden in many publications.

Many researchers just have terribly messy code, which even the authors struggle to use during and after the paper is published. I recently looked into someone's code for a method I was interested in. The author said there was a 'high learning curve'. The documentation was a 138 page file of method headers, which meant the code did not even have docstrings describing its methods, and it seemed extremely messy. For another paper, my group member emailed the author of the paper and code, who recommended that he would probably rewrite the code entirely if he had to work on the project again. His goal was to publish papers and could deal with the messy code while it was fresh in his mind, but using it after a month or two would be impossible. 

General sharing of code is not that common. In a meta-analysis, Prof. West found that only a small  percent of papers in the 2013 Combustion Institute had supplemental code to help others reproduce the work. 

Cleaning up code takes time, but it can also save themselves time by allowing effective reuse of code. I am unsure whether the time savings themselves are worth it. Since motivation is primarily about perception, it seems like people in the combustion field definitely think the code cleanup is more time consuming. This perceived effort of creating good code inhibits the ability to reproduce results in my field. Getting computational researchers to create readable and sharable code could improve the pace of research, and more options than ever exist for this to happen. I currently use [GitHub](http://www.github.com) to store and share my scripts. The [Open Science Framework](https://osf.io/) is another option.

Getting others to value producing reusable code might benefit from shifting the value capture element. Many approaches could encourage this. People could value citations more, as reusable ideas are likely to get more cited and built upon.^[Piwowar HA, Day RS, Fridsma DB (2007) Sharing Detailed Research Data Is Associated with Increased Citation Rate. PLoS ONE 2(3): e308. doi:10.1371/journal.pone.0000308] Journals could require open code for publications, which could improve their impact factor. Some Journals have already made requirements of utilizing online resources to validate methodology in psychology, so it doesn't seem impossible. If you think of other ideas to encourage the writing of good code and sharing it, [email me](markgoldman@mit.edu).

It doesn't seem like academia is immune to gaps in value creation and capture. We have mitigated the extreme examples of forgery, so maybe we could focus more on prevalent and subtle inefficiencies. 

[My next article]({{sit.url}}/blog/2016/06/posting-code-in-academia.html)) goes into more depth about code sharing.

<!--other things not mentioned:

I find the quantification of value creation a sticky issue. 

write about KI encouraging reporting of environmental issues

In Market-Based Management, Charles Koch asserts that the free-market incentives for companies can also be applied to people working in a company. While I am not convinced of all the assertions that lead to this conclusion, treating people like this 
-->

Note: the [photo of Sydney, AU](https://unsplash.com/photos/EOq4Dj33G_U) was taken by Seb Zurcher and is licensed under cc0
