---
title: Code Snippets
date: 2012-02-10 00:00:00 Z
categories:
- Design
layout: post
excerpt: Quick overview on how to post code snippets using Liquid tags and how to
  escape or not escape markdown and HTML in your blog entries.
---

Whenever you need to post a code snippet, use the liquid tags `hilight` and `endhilight` like this:

{% highlight ruby %}
# some code goes here
puts "Hello World!"
{% endhighlight %}

Note that this only provides color-coding. For that you might need to use a front end colorization engine like Highlight.JS or something similar.
