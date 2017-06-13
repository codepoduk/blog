---
author: mark mitchell
category: how-to
date: 2017-6-12 
layout: post
tags: [blog, markdown, tools, integration, how-to, github, stackedit]
title: publishing to this blog
---
all code pod members are encouraged to contribute to the blog (should they have the inclination!). we don't have a newsletter or other channel or 'official' way of broadcasting to new or existing members, and it would seem to be a reasonable way to capture the momentum of the group and the projects and activities of its members.

## how to publish a post
### way the first

1) write your blog post in markdown

2) include yaml front matter at the top of the post:

\- \- \-

author: your name

date: date of publication

tags: [comma, separated, array, of, tags]

title: your title here

\- \- \- 

those are three consecutive dashes at the top and bottom.

3) push it to the `_posts` directory of the [code pod blog repository](https://github.com/codepoduk/blog).

### way the second

this is my personal tip because i've found it to be a nice workflow in other contexts and you might too.

set yourself up on [stackedit](stackedit.io/editor) - it's an online markdown editor with a preview panel that's as close to perfect as i have found in my (extensive) search. if it had vim keybindings i think i'd be pretty much there.

i've synced stackedit to my googledrive, so now whenever i want to type something for whatever reason i just open the browser and go at it. it'll save every few seconds and you don't need to thing about where you're saving it or retrieving it from later.

one of the best features is the ability to publish directly to blogger,  github, tumblr, dropbox, wordpress - and a couple more i think.

config can be a wee bit fiddly, and i haven't time to do a step-by-step here, but give it a go and let me know in the gitter if you have any problems.

the main thing you need to know is that the publishing details, when prompted are:

	repository:  codepoduk/blog
	branch:   master
	file path:   _posts/2017-06-12-publishing-blog-posts.md

this is the hardest part of the process, since nowhere seems to specifically explain the format, but once you got this down, you're set!

mark 