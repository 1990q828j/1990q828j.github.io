---
layout: post
title:  "新博客成立啦-This is my first post in this blog"
date:   2015-08-13 16:22
categories: jekyll update
---
这是我的第一个个人博客
This is my first personal blog
thanks to github and jekyll

this python snippet	is for code display
{% highlight python %}
import web

urls = (
  '/', 'index'
)

app = web.application(urls, globals())

class index:
    def GET(self):
        greeting = "Hello World"
        return greeting

if __name__ == "__main__":
    app.run()
{% endhighlight python %}

welcome to [my blog](http://1990q828j.github.io)!

