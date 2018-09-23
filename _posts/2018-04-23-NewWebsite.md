---
layout: post
title: Setting up a new site in <15 minutes
tags: coding website jekyll
category: coding 🗝
---
I had really been considering transferring my website to something more manageable for a while. My previous personal page was mostly hard-coded and really functioned more like a business card with a link to my resume than a fully-fledged bb coder blog.

I decided to move to Jekyll cause I wanted something way easier to update (maybe then I'll update it 😅) as well as something with a more consistent theme.

Just wanted to detail the process of setting it up and some resources I used.

## Set up the website
I initially set up the website by just creating a new repo then using `jekyll new .` within that directory. There were some complications with set up however, particularly versions of `rbenv` and `jekyll`. However, I don't think those are too important if your ruby and gem environments are set up correct.

## Replace the theme
The jekyll new command really does a lot in terms of setting up your project. The real remaining step is making it look *pretty*. For that I really recommend **webjeda**. He created the theme you can find here (called [Sidebar](([Sidebar | Webjeda](https://blog.webjeda.com/jekyll-themes/sidebar/)) on the website). Normally applying the theme is as easy as forking the project and scratching all the stuff they did (well ok not allll the stuff)

## Add tagging
If your writing workflow is like mine, it's pretty organized. I like to use tags to divide up my notes, so transferring this into my website is pretty easy using tags. I set up the tagging system using the tutorial found on Long Qian's website: http://longqian.me/2017/02/09/github-jekyll-tag/.

## Post post post
So now you have a brand spanking new site. You'll probably add a bunch of cool themes and colors and I can't wait. But for now, the important part: writing.

Hope this helped!
