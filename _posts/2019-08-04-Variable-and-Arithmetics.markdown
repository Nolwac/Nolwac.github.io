---
layout: video_embed
embeds:
  - code: "U_i4vNUw1RA"
    title: "Watch Video on Variables and Arithmetic in Python"
    description: "This video illustrates what was discussed in this tutorial"

title:  "Variables and Arithmetic"
subtitle: temporarily holding data is almost inevitable in computing!
date:   2019-08-04 20:32:11 +0100
categories: python_tutorial
show_sidebar: true
tutorial: Python_Tutorial
permalink: /tutorials/:categories/:title.html
author: Livinus Anayo
---

Creating `Variables` is a way of `temporarily` holding data while computing and using a `symbolic variable` way of accommodating substitution or a way of generalizing per say.

To create a variable in Python, we first state the name of the variable, then followed by a single equality sign which is meant for assignment, afterward comes the value to be attached to the variable. The value is usually held all through out the program `runtime` and does not change unless if changed in the program.

Example illustrating this is shown below.

{% highlight python %}

>>> name = "Nwafor Livinus Anayo"
>>> name
'Nwafor Livinus Anayo'
>>>

{% endhighlight %}

Is there any computing without arithmetic operations? Python like most other programming languages is equipped to perform basic arithmetic operations.

To perform an addition operation in Python we use the plus sign, `+`

To perform a subtraction operation we use the minus sign, `-`

To perform a multiplication operation we use a single asterisk symbol, `*`

To perform a quotient operation (raising to power, indices) we use a double asterisk symbol, `**`

The example below shows how this is used.

{% highlight python %}

>>> 5 + 3
8
>>> 8*2
16
>>> 8-2
6
>>> 5**3
125
>>>

{% endhighlight %}
