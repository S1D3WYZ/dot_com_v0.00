---
title: "Progress With Scss"
date: 2020-08-15T18:14:35-07:00
draft: false
toc: false
images:
tags: 
  - HTML
  - Templates
  - HUGO
  - CSS
  - SCSS
  - Web Dev
---

I think I made some progress today on the site. I've been trying to create a custom [support-my-friends page][1], but was having difficulty integrating the HTML/CSS things I have been learning from YouTube tutorials into the [goHUGO.io](https://gohugo.io/) site generator...

... which is purported to be a middle-road approach between (1) taking the fine control and monotony of manually coding each page of your site in HTML, CSS, and JavaScript , or (2) using more ease-of-use-over-fine-control-hands-off-template-y-services like WordPress, Squarespace, etc; It's supposed to give you (3) all the fine control of structure and format, but the ease of use of applying it automagically to what you write in Markdown instead of manually hardcoding the base HTML each time.. which is fine if you just want to use the downloaded templates, but... well, I like to tinker... 

Something was getting lost in translation. Between being freshly armed with tons of random insigts into how I would go about manually crafting the site, and HUGO's I-give-you-full-control-but-theres-no-base-template-so-everything-is-different, and misreading/misunderstanding the documentation. I had a basic home page, social links, and could create posts (such as this one), but was completely lost creating the support-my-friends page. I was trying all the "make new template", "apply to this view", single. list? index?? "no you gotta watch out for this theme's sneaky setting that completely changes what the doc's say is going on under the hood"...

...to be fair, I honestly have NO idea what I did that broke it (site wouldn't even build for a while, no matter how many changes I rolled back), or what I did that eventually fixed it (was something going on with passing variables between site/page/item contexts).. but uh, well, it kinda works now... [go take a look][1] And I just de-string-i-fied their SCSS , so now the *real* un-winding of the template can begin. Fully custom, coming soon™

[1]: {{<ref "/squad/">}}