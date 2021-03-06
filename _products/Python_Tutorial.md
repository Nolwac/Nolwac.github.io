---
layout: tutorial
title:  "Python Programming Language"
subtitle: pip install Nwafor.org!
date:   2019-08-03 20:22:11 +0100
categories: jekyll update
image: /assets/Posts/Python_image.jpeg
menubar: python_tutorial
hero_image: /assets/Posts/Python_image.jpeg
---

`Python` is a [general purpose][general_purpose] [interpreted][interpreted-language] [High Level][High-level-language] `programming language` founded by [Guido van Rossum][Gudovan-Roseum]. Python finds application in different fields, like `Control system Engineering`, `Scientific Computing`, `Machine Learning`, `Data analysis`, `Networking and Network Programming`, `Web development` and many more. The most interesting fact about Python is that you achieve a lot just by writing very few lines of codes as the Programming language has a lot of tools available. By the virtue of the `syntax` of Python it is very understandable to a beginner in programming as the syntax is very close to our normal language. Below is an example Python program for a `24 hours` digital clock.

{% highlight python %}
>>> import time
>>> def clock():
	for i in range(24):
		for j in range(60):
			for k in range(60):
				print("the time is {}:{}:{}".format(i,j,k))
				time.sleep(1)


>>> clock()
the time is 0:0:0
the time is 0:0:1
the time is 0:0:2
the time is 0:0:3
the time is 0:0:4
the time is 0:0:5

{% endhighlight %}


[Gudovan-Roseum]: https://en.wikipedia.org/wiki/Guido_van_Rossum
[interpreted-language]:   https://en.wikipedia.org/wiki/Interpreted_language
[High-level-language]: https://en.wikipedia.org/wiki/High-level_programming_language
[general_purpose]: https://en.wikipedia.org/wiki/General-purpose_programming_language
