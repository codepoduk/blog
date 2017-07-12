---
author: Mark Mitchell
date: 2017-07-11
layout: post
tags: [meetup, data, kaggle, numbers, UI]
title: Tuesday 11th July
---

Things were getting real at yesterday's code pod meetup as [Dan](https://github.com/danmarcus111) and [Rahul](https://github.com/rkadam21) discussed their approaches to [recognising handwritten digits](https://www.kaggle.com/c/digit-recognizer) in a kaggle challenge they're collaborating on - and that was just the beginning!

## Data Science
I was only clinging onto the conversation with my fingernails, but it seems that from datasets of 28x28 images, the pixel values are extracted into arrays of length 784. The challenge is to use the training data to design a method that correctly identifies the handwritted digits for each item of test data.

Dan and Rahul referred to a technique called [K-nearest neighbour](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm) that they're using to iterate over these data and progressively order them via [mean shifting](https://en.wikipedia.org/wiki/Mean_shift). If you're like me and don't understand that, here are some diagrams they provided:

![Dan's KNN diagram](/images/knn.jpg)
![Rahul's KNN diagram](/images/knn2.jpg)

Got that? good!

Joking aside, it was great to get a little insight into some of the more... serious? applications of reasonably accessible coding. Maybe I'll dip my toe into a bit of data science at some point.

## Meanwhile, back at web frontend

And what was I doing? Well, the somewhat less serious business of [monster snap](https://codepen.io/spitchell/pen/OgBgNN), which I wanted to move out of it's current home on codepen so I could organise it properly. Codepen's great for knocking up quick proofs of concept but I struggle to work directly in the editor, and usually prefer to transfer to github if there's proper organising to be done.

I was delighted to find that the pen export feature works like a dream, dowloading a compressed directory that unzips to give you linked index, css and js files ready to go. 

## UI training

Rahul is just recovering from a HDD failure - a good reminder to keep your backup strategy in order! - but once he'd finsihed setting up we got started discussing the [DOM-kata code pod repo](https://github.com/codepoduk/DOM-katas).

The aim of this poorly-named project is to build challenges to give budding web devs some positive experiences of DOM manipulation. With modular design-patterns becoming increasingingly popular, the hope is that these challenges will demystify some of the standard bits of web-furniture by taking them out of context. As the components are completed they can be composed together in ways that increasingly resemble real-world use cases. 

## Abstractions
[Gary](https://github.com/garysiu/)'s antipathy towards modal pop-ups spun off into a conversation with Dan that I quickly lost track of becuase Rahul and I went off on one of our usual philosophical tangents - about the epistemological status of numbers on this occasion.

All in all a pretty healthy meetup. 

Mark
 


