---
layout: post
title:  "Starting with Jekyll"
date:   2017-03-23 11:37:00 +1300
categories: jekyll
---

Basic Jekyll things:
Using my Jekyll RVM setup (RVM sets up individual gemsets and versions of ruby to use with each other)
{% highlight ruby %}
rvm gemset use jekyll1
{% endhighlight %}

Updating and building the site:
{% highlight ruby %}
bundle exec jekyll serve
{% endhighlight %}
