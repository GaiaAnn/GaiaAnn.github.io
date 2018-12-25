---
layout: post
title:  "Jekyll with GitHub"
date:   2018-10-29 00:00:00
categories: [tutorial]
tags: Jekyll GitHub 
comments: true
image:
  feature: https://images.unsplash.com/photo-1440635592348-167b1b30296f?crop=entropy&dpr=2&fit=crop&fm=jpg&h=475&ixjsv=2.1.0&ixlib=rb-0.3.5&q=50&w=1250
  credit: thomas shellberg
  creditlink: https://unsplash.com/photos/Ki0dpxd3LGc
---
  
> Jekyll is a simple, blog-aware, static site generator. Written by Ruby.  

1. No more database.
2. Use Liquid Template with markdown
3. Free hosting with GitHub Pages

<!--more-->
## Create Jekyll Blog Steps
* Install ruby or update ruby verision.
  {% highlight bash %}
  curl -sSL https://get.rvm.io | bash -s stable
  rvm list known
  rvm install ruby-2.4.2
  {% endhighlight %}
* Install jekyll.
  {% highlight bash %}
  gem install jekyll
  {% endhighlight %}
* Go to GitHub and fork your favorite template then go to template path.
* Install bundler. This can manage gem plugins and fix dependency issue.
  {% highlight bash %}
  gem install jekyll bundler 
  {% endhighlight %}
* Strat running jekyll local server
  {% highlight bash %}
  bundle exec jekyll serve
  {% endhighlight %}
* If missing some plugin... According to the error msg and execute some command like below.  
  (tzinfo-data is plugin name)
  {% highlight bash %}
  gem install tzinfo-data
  {% endhighlight %}
* After install plugin. Need to update bundle.
  {% highlight bash %}
  gem install tzinfo-data
  {% endhighlight %}

## Host with GitHub 

## About this blog
This blog is using [Leonids Theme][leonids theme] template & **Sass** & **BootStrap 4**.  
compiler IDE: **Visual Studio Code**.
plugins: **Live Sass Compiler**.



## Other Jekyll Problems
Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll.  
File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh].  
If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
[leonids theme]: http://github.com/renyuanz/leonids/">=