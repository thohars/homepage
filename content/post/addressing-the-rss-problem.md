---
title: "Addressing the RSS Problem"
date: 2022-06-27T19:03:42+09:00
tags: ['update','meta']
---

When I migrated from Express to Hugo, I wanted to keep my main RSS feed URL ([/rss](/rss)). I forgot to implement that but basically, I'm planning to use a location block in Nginx and put the Hugo-generated feed ([/post/index.xml](/post/index.xml)).

If you're reading this and can't go to the main URL, go there instead. Perhaps I haven't configured the web server yet. If you don't know what RSS is, you should know it. Go here: [https://www.youtube.com/watch?v=hMH9w6pyzvU](https://www.youtube.com/watch?v=hMH9w6pyzvU)
