---
title: Implementing Google reCAPTCHA v3 using Apache Royale and Grails
permalink: /docs/recaptcha/impl
layout: docpage
---
# Implementing Google reCAPTCHA v3 using Apache Royale and Grails

---

## Part 1 - Basic information and architecture overview

##### What are bots?

Over the web there is a lot of malicious software floating around, constantly trying to exploit web pages. We call this software robots or bots. They are looking for ways to interact with sites in a way that will provide benefit to its creators.

What bots may want from your website? For example:

- They may pretend to be your customers and request to be contacted by your sales department. When they obtain your email address they may try phishing attack on your company.

- They may want to post fake reviews on your webpage, trying to advertise they're own products.

##### What is captcha?

Captcha is a simple challenge presented on webpages in order to tell apart humans from bots. One of the most popular captcha providers is Google. Google brands its captcha algorithm as reCAPTCHA. Up to this day there were three major versions of Google's reCAPTCHA (plus an enterprise one). You may remember older ones with some nostalgia:

- Version 1 presented a hard to read text (and a voice variant) to be retyped by the user:
  
  ![](img/recaptcha-v1.png)

- Version 2 tried to analyze visitor's behavior and included "I'm not a robot" checkbox:

  ![](img/recaptcha-v2-checkbox.png)

  If the interaction was seen as potentially malicious it resorted to presenting visitor a puzzle:

  ![](img/recaptcha-v2-puzzle.png)

- Version 3 will **never** interrupt a visitor. The distinction will be made solely on the user's behavior during the visit. It scores users interaction on the scale from 0 to 1 and lets you decide on your own cut-off point (for example 0.6). It also lets you analyze past behaviors based of sub-page and type of interaction.
  
  ![](img/recaptcha-v3-royale.png)

Everybody hated the earlier iterations of reCAPTCHA and for a good reason. People agonized over few pixels in the corner being a part of the street sign or not -- only to get it wrong and be presented with a next challenge.

Now you can protect your page without annoying your customers, and this is probably step in the right direction.

##### How to implement reCAPTCHA to protect your page?

In these articles I will show you how you can register for reCAPTCHA v3 and implement it on your website. The examples will be presented in Apache Royale on the front and and in Groovy/Grail on the back end. These two technologies allowed our team to build this quickest and easiest but if you want you can easily translate this to your own stack.

- Part 1 - registration and communication overview

- Part 2 - front end in Apache Royale

- Part 3 - back end in Groovy/Grails
