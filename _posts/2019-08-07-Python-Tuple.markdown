---
layout: video_embed
embeds:
  - code: "dFKgpwO8urg"
    title: "Watch video on Python Tuple"
    description: "This video illustrates what was discussed in this tutorial"

title:  "Python Tuple"
subtitle: Immutability is desirable when we don't want things changing!
date:   2019-08-07 13:22:11 +0100
categories: python_tutorial
show_sidebar: true
tutorial: Python_Tutorial
permalink: /tutorials/:categories/:title.html
author: Livinus Anayo
hero_height: is-fullwidth
---

A `Tuple` in Python is similar to a list, the difference between the two is in the way they are created and in the `mutability` of the contents.

Square brackets are used in creating a list but in creating a tuple we use circular brackets, `()`. A list is mutable (the items can be changed) but a tuple is not mutable (the items can not be changed)

{% highlight python %}

>>> list_items = ['Nwafor', 9, 3, ['Charles', 64], 13.2]
>>> list_items
['Nwafor', 9, 3, ['Charles', 64], 13.2]
>>> type(list_items)
<class 'list'>
>>> tuple_items = ('Nwafor', 9, 3, ['Charles', 64], 13.2)
>>> tuple_items
('Nwafor', 9, 3, ['Charles', 64], 13.2)
>>> type(tuple_items)
<class 'tuple'>
>>>

{% endhighlight %}
