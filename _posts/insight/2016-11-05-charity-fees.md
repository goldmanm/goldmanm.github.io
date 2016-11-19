---
layout: layout-post
title: effective giving
summary: reducing fees when supporting charities
source: /app/posts/insight/charity-fees
preview-img: /app/posts/insight/charity-fees/preview.jpeg
preview-css: post-preview-std post__imgPreview--dark
category : insight
tags : [charity, giving, online, fees]
published : true
type : blog
---

Technology has made our lives so much easier. E-mail allows us to get information much quicker to the wider world, in a cheaper and more environmentally friendly manner. 

After becoming a mentor in my hall, which cut my yearly expenses by ~$7000. I decided to give my excess stipend to charity. In my head, I idealized using an electronic platform to generously give to non-profits so I could easily keep track of donations for tax purposes. I imagined a secure company that would link to my bank account, and directly transfer to accounts of non-profits of my choice, for less than the cost of a postage stamp. At the end of the year, I could get an email notifying me of all my contributions to help file my taxes. This dream was a bit naive. 

Like any mellinial, I started my search online. I am familiar with [charity navigator](http://www.charitynavigator.org/) for their ratings of non-profits, and I was happy to see a 'donate' button over charities of interest. Upon checkout, I noticed that they went through a company, [Network for Good](http://www.networkforgood.com/), that charged a 4.75% flat fee. Giving a few hundred dollars through that is ten times more expensive than a postage stamp. A similar company, [JustGiving](https://www.justgiving.com/fees) charges 5% fee. A non-profit even [posted](http://www.ripoffreport.com/r/network-for-good/bethesda-maryland-20814/network-for-good-networkforgoodorg-rip-off-nonprofit-organizations-donations-bethesda-418759) that it didn't want to even be on Network for Good's site due to the cuts it was taking, though it seems the site lists every charity whether they want or not (which allows donors more convenience). I was struck by the cuts these financial organizations were taking, and some of the tactics used by them. 

And then I got into the weeds. There seem to be dozens of platforms for non-profits to choose from. I even stumbled upon an [open source](https://www.campaignion.org/pricing) option that allows charities to set up their own servers. Many of these options require the charity to sign up, with variable fees for each transaction. I saw charities complain about monthly fees for services that charge lower fee rate. Many platforms spoke to charities and not to donors, so I decided to find other resources.

The best resource that I have found targeted to givers is a [post on nerdwallet](https://www.nerdwallet.com/blog/nonprofits/donate-charities-corporations/0). It describes numerous methods and the fees associated with them, but I found some issues with their representation that I think I should highlight. For example, it claims Facebook donations have no fees, but the donate button takes you away from Facebook to various sites where fees are often charged. Another claim involves stating that there are no fees for [popmoney](https://www.popmoney.com/charity.html), despite its brochure mentions 'low transaction fees' (I couldn't find an absolute number on the site).

The best offer I found was [capital one](https://www.capitalone.com/give/faq/) which is waiving all fees donated through it's site. It claims 100% goes to the charity of your choice, and it goes through Network for Good. I couldn't find any information explicitly mentioning that Network for Good waives all fees, so I am not certain about the claim. Anyways, you may want to verify any statements in the nerdwallet article. The answer of the best platform to donate to charities gets more complicated when you recognize larger charities can get non-transparent 'bulk deals', which obscure fees for donor. 

I wrote a small python script to help me sort through the options based on the amount that I will donate. Below is a graph produced by the program, and [check it out for yourself](https://github.com/goldmanm/goldmanm.github.io/blob/master/app/posts/insight/charity-fees/charity%20donor%20fees.ipynb). I didn't put the captial one program on since, to the best of my knowledge, it has no fees.

![graph of costs]({{ page.source}}/graph.png)

If you have questions/comments/corrections or found a better resource, feel free to email me and I'll make this post more helpful for others. 


Note: [the image of eggs in a basket](https://unsplash.com/photos/TT28vvE-zZ8) was taken in by Joanna Kosinska and licensed with cc0.


