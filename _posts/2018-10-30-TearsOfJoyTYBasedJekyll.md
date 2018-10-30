---
layout: post
title: Configuring Jekyll with Github Pages - A F'ing Nightmare
tags: coding jekyll website
category: coding 🗝
---
finally bought the url!! `aida.wtf` woopty-frickin-doo 🎊

except for the fact that i can't get the connection/hosting whatever right. just for personal logs, here's some pages i followed today

## resources
https://ilovesymposia.com/2015/01/04/some-things-i-learned-while-building-a-site-on-github-pages/
https://stackoverflow.com/questions/9082499/custom-domain-for-github-project-pages


## building locally
all files are in `~/coding/booleanings.github.io`
just run `jekyll serve` to build and serve locally @ `http://127.0.0.1:4000/blog/`

## routing problems
so cname is linked to aida.wtf as is the hosting redirects on namecheap. 
thinking there is a problem with `config.yml` file

> ya know the worst part about solving hosting problems is sitting there waiting for the dns to refresh 🙄


# ESKETIT
i got it to work _finally_. no clue exactly what i did but `config.yml` has these configs:

url: "https://aida.wtf/"

baseurl: "/" 

markdown: kramdown


the hosting has these configs:
A Record`@`192.30.252.154`30 min
A Record`@`192.30.252.153`Automatic
CNAME Record`wwwbooleanings.github.io`Automatic

and then on github i just have a file called `CNAME` with this
`https://aida.wtf`

the day has been exhausting but i'm so damn proud 

![tears of joi](https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Ftse4.mm.bing.net%2Fth%3Fid%3DOIP.RbM_s7THmThqCIV9TG2gbAHaEA%26pid%3D15.1&f=1)
