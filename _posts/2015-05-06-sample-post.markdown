---
layout: post
title:  "Test Post"
author: nyurin
date:   2015-05-06 14:34:25
---

Sample article
==============

This this sample content
Bla bla bla

bla bla bla

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}
