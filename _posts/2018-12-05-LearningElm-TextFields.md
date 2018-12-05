---
layout: post
title: Learning Elm - Text Fields
tags: elm coding
category: coding 🗝
---
# Learning Elm - Text Fields
## Questions for the Day ⁉️
* What do the (...) mean when importing?
Ok first up, **idiot**, it's supposed to be ``(..)`` (scoff)

* How to reformat code automatically?
![]({{site.url}}/{{site.baseurl}}/assets/2018-12-05-LearningElm-TextFields/5A65FFAB-F298-47F8-8E0C-28BDFEBC796C.png)

* ::How the fuck do I properly set up a view? Like what is up with all these divs and whatnot?::


## Mistakes I made 🤦🏽‍♀️
* `import Html.Attributes exposing (..)` uses 2 dots **idiot**

![]({{site.url}}/{{site.baseurl}}/assets/2018-12-05-LearningElm-TextFields/DEF98A9F-00E9-434C-8C5D-52B71FA9C65B.png)

* Model was missing a record
![]({{site.url}}/{{site.baseurl}}/assets/2018-12-05-LearningElm-TextFields/6D62112D-1D5A-4512-AC0A-FE60818A0012.png)

![]({{site.url}}/{{site.baseurl}}/assets/2018-12-05-LearningElm-TextFields/D1473327-A04A-48CC-93F2-6E74D4A8547C.png)
![]({{site.url}}/{{site.baseurl}}/assets/2018-12-05-LearningElm-TextFields/9E4B23CD-6C0B-4884-B4AB-EFFA7948A413.png)

so tried some pretty naive shit at first **moving brackets around you**
really `view` needs to be typed as a capital M Model which is a type with content


## Success 👌
![]({{site.url}}/{{site.baseurl}}/assets/2018-12-05-LearningElm-TextFields/719A98FD-7A2F-4B01-BB84-EC7855805032.png)


Nov 26, 2018 at 3:36 AM

#coding/elm
