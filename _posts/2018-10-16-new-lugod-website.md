---
layout: post
title:  "The New LUGOD Website"
date:   2018-10-16
excerpt: "Make everything as simple as possible, but not simpler."
image: "/images/code.jpg"
---

## The Redesign

The LUGOD website has come a long way from its start [back in 1999](http://web.archive.org/web/19991007030450/https://www.lugod.org/). Shout out to Marianne Waage for the original site design, of which I am a big fan. The most recent iteration of the site was a [custom PHP site](http://web.archive.org/web/20181002005929/https://www.lugod.org/) written by LUGOD cofounder [Bill Kendrick](https://twitter.com/billkendrick?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor). The codebase was well written and clean (not an easy feat with PHP), but it was custom enough to hinder beginners from making changes to the site. After some discussions and testing, we decided to migrate the site to a setup that was easier to work with, and that newcomers could understand.

In choosing a new platform, we wanted to go with a setup where people could add a new page via Markdown, deploy changes from a phone, and standardize on a well defined structure with existing documentation and support. We all decided to go with a Static Site Generator (SSG) which simplifies editing and deployment while maintaining a well-defined structure. A CMS or Wiki engine could have worked as well, but we wanted to keep things as simple as possible (but not simpler!). After trying out a few static site generators on [StaticGen](https://staticgen.com), including [Pelican](http://docs.getpelican.com/en/stable/), [Hugo](https://gohugo.io/), and [Nuxt](https://nuxtjs.org/), we decided to go with [Jekyll](https://jekyllrb.com/) because of its low learning curve, large userbase, tight integration with Github pages, and broad functionality out of the box. Not to mention, since Jekyll is arguably the "most popular" SSG, there are often resources or tools designed to migrate from Jekyll to other SSGs.

## Contributions

Do you have some long form ideas or writeups you'd like to share with the LUGOD community? Or maybe just a quick blurb or announcement? Submit a PR to our Github page and have your post published on the site!

The source code for this site is hosted on our Github page at https://github.com/DAVISLUG. Pull requests to the repo will be reviewed by LUGOD members, and changes to the master branch will be reflected on the site within a few minutes after approval.

To create a new blog post, add a markdown or html file to the `_posts` folder. The file should be named `YEAR-MONTH-DAY-title.MARKUP`. For example, this post is named: `2018-10-16-new-lugod-website.md`.  For more details on adding posts to Jekyll, please see their [documentation](https://jekyllrb.com/docs/posts/).
