---
title: Writing personal website and blog with eleventy(11ty)
description: This is the first post of my new blog.
date: 2023-12-30
tags:
  - programming
---

The first problem I encountered was the configuration file. ".eleventy.js" is used in either version 1 or 2. ".eleventy.config.js" was introduced in version 2. I followed the example from their official website by using ".eleventy.config.js". I set my return input to "src" and output to "_site" but my index.html got a 404 not found error. As soon as I renamed ".eleventy.config.js" to ".eleventy.js" it worked properly. When I'm writing this post I found the reason that I added a dot before "eleventy.config.js". I think 11ty's author should point out the difference for anyone who are confused as I was.

I have been back coding for 2 weeks. I am surprised by the number of those new frontend technologies I never heard or used. This eleventy is also new to me. It brings a bunch of new things such as nunjucks, liquid, etc. The last time I dived so deep in the frontend area while jquery was popular and AngularJS didn't release its second version. Anyway, I'm not intend to become a frontend developer nor learn so many new frontend things. I only need to know what I need for my website.

The first few blog posts will be put in this blog folder as it's a static content website. Later on I'm thinking move all posts to another project and write an API for my website to consume (if I could learn to use another programming language say Rust). 

It doesn't matter how messy my posts are because no one will ever come here to read them. However, some contents will be highly organised for showing on the internet. Afterall this website and blog idea is on my mind for years. 

There are 2 days in this year. Hope everything goes well in the new year to my own website and my second programming journey. 
