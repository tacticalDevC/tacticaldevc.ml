---
title: "Domain Registrar Orangewebsite unveiled"
date: 2019-11-26T19:20:49+01:00
draft: true
---
# Introduction
Today I searched for a new domain name registrar for my blog domain. What I found is "Orange". They seemed trustworthy. I cross-checked them with [privacytools.io](https://privacytools.io). I thought "okay well why not". But after a way too fast click on that buy button (shame on me) I researched a bit about this company which claims to be privacy-focused and 100% Icelandic.

See for yourself!

## Wait... what is this even about?
A domain registrar! Orangewebsite claims to be a 100% icelandig company. In this post I will show you what convinced me to buy that domain, the conversation between me and the support and how I found out that they actually aren't that what we think of Orangewebsite is.

## TL;DR
Orangewebsite might be a Hong Kong owned company which claims to be Icelandic. In WHOIS they hide their own data (why should they?) using a WHOIS Privacy proxy. That proxy unveils the owner if a subpoena (or NSL) is received. The proxy and it's hoster are based in the US and run on AWS.

## I did a bad thing...
So I was searching for a new domain registrar for a new domain for this blog. I was searching on different sites. One of them was [privacytools.io](https://privacytools.io). In the Hosting section I found Orangewebsite. They say that they are from Iceland and so are their servers. I was looking at their Privacy Statement and was pretty satisfied with what I saw. In fact you only need an email address to sign up. No personal information and absolutely nothing else required. I thought "Okay let's give them a try! They seem trustworthy.". Dumb me hehe. Well I set up an account and selected my domain. At the checkout I used PayPal as I don't own any cryptocurrency atm. And that's... My mistake. I checked everything price related one last time and clicked "Pay". But wait what is that written down at the bottom?... It says "IceNetworks Hong Kong Limited". Ummm Iceland is definitely not China?

![](../orange/paypal.png)

## But they said they are Icelandic?!
Yes they do. But you also know that you shouldn't trust a company. Let's examine the picture. Look at the links under the header "Verkäufer" (german word for seller). The first link references to [orangewebsite.com](https://orangewebsite.com). That might let you think "Woah! Wait... they are actually a china-owned company?!". Yes I thought that too. The two other links are pretty obvious to where they lead to. 

Next stop: traceroute and geoip check. The trace leads me to 82.221.131.223 and this is an IP in Iceland. Now it gets **really** interesting. We have an apparently china-owned company in Iceland. Or at least their frontpage is hosted in Iceland. Sounds not really trustworthy.

In fact if you look at their website at the domain registration section you will find the following sentence.

> We are able to offer you extended privacy and low online censorship by registering all the domains in an offshore location, outside of the USA or European Union.

This confirms that the domain I bought is not hosted from where I expected it. From there on I can only speculate where the servers are actually located. It might be in Iceland, China or even the USA. Why the USA? Well read on.

## What is going on with the support?
Next stop was the support. The first person seemed to really be Icelandic. At least I think so. I haven't researched the person and it would be a little bit out-of-scope of this article. He was nice and used proper English. Nothing which confirms my suggestions so far. I asked him why my money is sent to China and he escalated my ticket to the 2nd Level Support. From there on I talked to two Customer Support Representatives. And there is something else. Why don't they use their full names anymore? Did I ask the wrong questions?

First I talked to J. Frederick.

![](../orange/reply1.png)

Alright... An Icelandic company has issues (note the "s" at the end) with PayPal. And why is he telling me that they are 100% Icelandic? I never said that I have concerns regarding the origin. After all I don't believe anymore that this company is really from Iceland. 

Btw did you notice that Frederick doesn't use proper English? Could be because he isn't that good in English but then he wouldn't be in the 2nd Level Support right? Correct me if I'm wrong but this is getting really really dubious and raises a red flag in my head.

I moved on and asked what kind of issues they had with PayPal. This was his answer:

![](../orange/reply2.png)

Why am I talking to Vince now? Has Frederick not the right answer for my question? I want Frederick back! And besides of that, shouldn't the support give me a more explainatory answer?

Now thinking of these technical issues as well as administrative issues I asked a more specific question. Why should PayPal not be able to fix technical issues and tbh having issues with payments doesn't sound healthy. Things start to make absolutely no sense.

I asked Vince about these issues. Also it would make sense if my money is sent there, then the company must be registered there too, right? And if Orangewebsite is trustworthy, then there should be at least a statement. I know, I suggest at this point that they are actually china-owned but I think with this I hit a critical point.

Vince sent me one last answer.

![](../orange/reply3.png)

That hurt Vince. I'll be honest I was getting naggy and made vague claims but that isn't a reason to get unfriendly.

From there on I didn't get any answer from them anymore.

## Summary #1
We have a company:

 - with an Icelandic IP address
 - that wants you to send money to China
  - that may be registered in China
  - but still insists in being in Iceland
 - with support that doesn't want to let you know about problems
  - or doesn't publish a statement
 - which 2nd Level Support isn't really friendly or helpful


Notes:
 - PayPal nach Zahlungsinformationen fragen
 - Isländische Regierung befragen (Firmengrundbuch)
