---
layout: video_embed
embeds:
  - code: "Ais6TNHJqhg"
    title: "Watch video on Python List part 1"
    description: "This video illustrates what was discussed in this tutorial"
  - code: "NoR6d1n5qn4"
    title: "Python List part 2"
    description: "This video illustrates what was discussed in this tutorial"
  - code: "74rtRFah0FU"
    title: "Python List part 3"
    description: "This video illustrates what was discussed in this tutorial"

title:  "Python List"
subtitle: accommodating data of different types can be very important too!
date:   2019-08-06 20:22:11 +0100
categories: python_tutorial
show_sidebar: true
tutorial: Python_Tutorial
permalink: /tutorials/:categories/:title.html
author: Livinus Anayo
---

A list in Python is a collection of items, this items could be of different object types. In a python list we can have an Integer, a string or even an instance of a given class.

The example below illustrates how to create a list and also shows how a list is capable of holding different object types.

{% highlight python %}

>>> items = ['Nwafor', 9, 3, ['Charles', 64], 13.2]
>>> items
['Nwafor', 9, 3, ['Charles', 64], 13.2]

{% endhighlight %}

From what we see notice that in creating a list we use block(square, `[]` brackets to hold the items. You can also observe that a list can as well hold another list, notice that `['charles', 64]` is a different list entirely.
