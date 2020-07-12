---
layout: post
title: 'HTTPS By Default: How Facebook Could Help Human Rights'
date: '2012-08-14T13:42:00-04:00'
tags:
- facebook
- security
- activism
tumblr_url: https://blog.kendraalbert.com/post/29418037499/https-by-default-how-facebook-could-help-human
---
It is not news that Facebook has some image issues when it comes to protecting human rights. Its real name policy being enforced in an inconsistent way can create huge problems for activists and its privacy settings changes can result in data becoming public in a way that allows for identification of underground activist networks, to name two of many critiques made persuasively [elsewhere](http://jilliancyork.com/2011/02/24/would-anonymity-help-activists-on-facebook-a-response-to-luke-allnutt/).&nbsp;

So it is great to hear that Facebook is funding&nbsp;[prizes for human rights innovation](https://www.accessnow.org/blog/access-and-facebook-launch-tech-innovation-prize-to-promote-human-developme), including an encryption prize. (Submissions close tomorrow.)

But really, the best use of this money is for Facebook to take the $20,000 prize for “the best actionable idea to properly integrate encryption into an existing product/system, educate users as to how to use encryption and/or build a community who use encryption by default” and give it to its engineers to make HTTPS default for all of its users.<!-- more -->

For those who are unfamiliar, HTTPS is a secure connection to the site. It won’t prevent anyone sniffing your traffic from knowing you are on Facebook, but to quote the [EFF](https://www.eff.org/https-everywhere/faq), it can “protect you against eavesdropping and tampering with the contents of the site or with the information you send to the site. Ideally, this provides some protection against an attacker learning the content of the information flowing in each direction — for instance, the text of e-mail messages you send or receive through a webmail site, the products you browse or purchase on an e-commerce site, or the particular articles you read on a reference site.”

Currently on Facebook, HTTPS is an option you can turn on for your account under security settings. It’s great that Facebook gives users the option, but one has to be relatively knowledgeable to go to Security and turn it on. Many other services, including Gmail, default to HTTPS connections.

As things stand now, enabling HTTPS in countries like Syria can be the equivalent of telling authorities that you have something to hide. Never mind that your content is now encrypted, you’ve just placed a target on your back. If all of Facebook’s traffic was encrypted by default, HTTPS wouldn’t indicate “activist” – it would just indicate “Facebook user.” In effect, it could hide conversations that really need to be encrypted in a sea of other encrypted traffic.

So why hasn’t Facebook enabled HTTPS by default? I’m not sure, but there are two main criticisms of HTTPS defaulting – one technical, and one censorship-related.&nbsp;

First, many folks will claim that switching to HTTPS is resource intensive from a technical point of view. For this, I turn to Adam Langley, who wrote about [implementing SSL/TLS](http://www.imperialviolet.org/2010/06/25/overclocking-ssl.html) (which is the technology behind HTTPS) for Gmail (in 2010!) and said “SSL/TLS is not computationally expensive any more.” If Gmail can deal with the latency issues, my guess is that Facebook can too. There might be some additional issues with existing applications in a way that Gmail does not have contend with, since there are a variety of games and other apps that the Facebook ecosystem supports. Still, I have confidence in Facebook’s engineers.&nbsp;

Censorship objection - countries sometimes block all HTTPS traffic. If Facebook defaulted to HTTPS, no one could use Facebook! Here, as often on the Internet, the answer is cute cats. Ethan Zuckerman has postulated the “[cute cat theory of activism](http://www.nytimes.com/2009/06/22/technology/internet/22link.html?_r=2)” in which he says that attempts by authoritarian governments to block popular Web 2.0 sites because of activist content causes outrage because many people just use them to view cute cats. If blocking HTTPS websites meant blocking all of Facebook, my guess is that countries might think twice about the decision. The more sites default to using HTTPS, the better it will work from a “cute cat” perspective.&nbsp;

HTTPS is not perfect. There’s another blog post about the broken certificate system. Still HTTPS is better than no protection at all. So Facebook, take your own advice. Protect all your users, including the activists. Default to HTTPS.

(This post was inspired by an email to the Ideas for A Better Internet mailing list and by the Browsers + Internet Freedom workshop, which inspired my continued love for default HTTPS.)

