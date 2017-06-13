---
author: Mark Mitchell
category: how-to
date: 2017-6-12 
layout: post
tags: [blog, markdown, tools, integration, how-to, github, stackedit]
title: Publishing to this blog
---
All code pod members are encouraged to contribute to the blog (should they have the inclination!). We don't have a newsletter or other channel or 'official' way of broadcasting to new or existing members, and it would seem to be a reasonable way to capture the momentum of the group and the projects and activities of its members.

## How to publish a post
### Way the first

1) write your blog post in markdown

2) include yaml front matter at the top of the post:

\- \- \-

author: your name

date: YYYY-MM-DD

layout: post

tags: [comma, separated, array, of, tags]

title: your title here

\- \- \- 

Those are three consecutive dashes at the top and bottom.

3) push it to the `_posts` directory of the [code pod blog repository](https://github.com/codepoduk/blog).

### Way the second

This is my personal tip because i've found it to be a nice workflow in other contexts and you might too.

Set yourself up on [stackedit](stackedit.io/editor) - it's an online markdown editor with a preview panel that's as close to perfect as i have found in my (extensive) search. If it had vim keybindings I think I'd be pretty much there.

I've synced stackedit to my googledrive, so now whenever I want to type something for whatever reason I just open the browser and go at it. It'll save every few seconds and you don't need to thing about where you're saving it or retrieving it from later.

One of the best features is the ability to publish directly to blogger,  github, tumblr, dropbox, wordpress - and a couple more I think.

Config can be a wee bit fiddly, and I haven't time to do a step-by-step here, but give it a go and let me know in the gitter if you have any problems.

The main thing you need to know is that the publishing details, when prompted are:

	repository:  codepoduk/blog
	branch:   master
	file path:   _posts/2017-06-12-publishing-blog-posts.md

This is the hardest part of the process, since nowhere seems to specifically explain the format, but once you got this down, you're set!

Mark 