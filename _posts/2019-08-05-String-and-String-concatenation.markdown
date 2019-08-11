---
layout: video_embed
embeds:
  - code: "sEbc4UhMr-g"
    title: "Watch video on String and String concatenation"
    description: "This video illustrates what was discussed in this tutorial"

title:  "String and String concatenation"
subtitle: pip install Nwafor.org!
date:   2019-08-05 21:03:11 +0100
categories: python_tutorial
show_sidebar: true
tutorial: Python_Tutorial
permalink: /tutorials/:categories/:title.html
author: Livinus Anayo
---


## What is a string?
A string is a collection of characters.
Example is my name "Livinus", what we have in the quotation is a collection of the alphabetical characters that make up the spelling of my name.
Having a string is not just all, there may be need to add strings together, this will then lead us into talking about `string concatenation`.

{% highlight python %}
>>> name = "Livinus"
{% endhighlight %}

## String concatenation

String concatenation is simply the bring together of strings, it is the addition of strings or a way of putting strings together. We shall look at some of the methods of concatenating strings in Python.

{% highlight python %}
>>> name = "Livinus" + "Anayo"
"LivinusAnayo"
{% endhighlight %}

There are several methods that we can use in doing string concatenation in Python, these methods are listed below:

<ul>
  <li>String addition</li>
  <li>String formatting (using the format function)</li>
  <li>The new string concatenation method in python 3</li>
  <li>We are going to take this methods one after the other.</li>
</ul>

## String addition

In string addition we use the plus sign to add strings like though as if we are adding numbers together. what this does is that it takes the preceding string and appends it to initial string, an example of this is shown below in the example program.

{% highlight python %}
>>> name = "Livinus" + "Anayo"
"LivinusAnayo"
{% endhighlight %}

The problem with this method of concatenation is that you can not easily convert other object types to string through this operation.

## String formatting

In string formatting we use the built in Python format method(function). This function is built into the string class so is accessible to any string object. Below is an example program showing how this is done.
From the example above we can see that in using the format method we have to use curly braces to close to indicate a position where we want to position an object in the string, then after that we extend the string to the format method, providing inside the bracket parameters which are the objects we wish to have in the string with respect to the order in which the curly braces were placed in the string.

{% highlight python %}
firstname = "Livinus"
othernames = "Nwafor Anayo"
fullname = "my name is {} {}".format(othernames, firstname)
print(fullname)
{% endhighlight %}

<h3>Result</h3>

{% highlight python %}
>>>
"Nwafor Anayo Livinus"
{% endhighlight %}

## Using the percentage symbol

Python is equipped with different methods for doing string concatenation. Another method one can apply in doing string concatenation is using the percentage method, this method is similar to the string formatting method but here we do not use dot in extending the string, the dot is usually omitted in this method. Another difference is that instead of using curly braces to denote where we wish to have the objects placed in the string we use "%s", percentage S. An example showing an illustration of this is shown below.

{% highlight python %}
fullname = "my name is %s %s"%(othernames, firstname)
print(fullname)
{% endhighlight %}

<h3>Result</h3>

{% highlight python %}
>>>
"Nwafor Anayo Livinus"
{% endhighlight %}

## The new Python 3 method

Python 3.6 and above comes equipped with a new method of doing string concatenation. This method share some things in common with the string formatting method. Here we put the objects that we want to place in the string directly inside the curly braces in the string. And before the string is the small letter f, placed the way we place the letter r as in regular expressions and the letter b as in binary strings. The example below illustrates this method.

{% highlight python %}
fullname = f"my name is {othernames} {firstname}"
print(fullname)
{% endhighlight %}

<h3>Result</h3>

{% highlight python %}
>>>
"Nwafor Anayo Livinus"
{% endhighlight %}
