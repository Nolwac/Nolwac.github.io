---
layout: video_embed
embeds:
  - url: "https://www.youtube.com/embed/6o7b9yyhH7k"
    title: "the new title"
  - url: "https://www.youtube.com/embed/6o7b9yyhH7k"

title:  "Python Programming Language"
subtitle: pip install Nwafor.org!
date:   2019-08-03 20:22:11 +0100
categories: jekyll update
image: /assets/heroimages/philo.jpg
show_sidebar: true
callout: example_callouts
---

`Python` is a general purpose [interpreted][interpreted-language] [High Level][High-level-language] `programming language` founded by [Gudovan Roseum][Gudovan-Roseum]. Python finds application in different fields, like `Control system Engineering`, `Scientific Computing`, `Machine Learning`, `Data analysis`, `Networking and Network Programming`, `Web development` and many more. The most interesting fact about Python is that you achieve a lot just by writing very few lines of codes as the Programming language has a lot of tools available. By the virtue of the `syntax` of Python it is very understandable to a beginner in programming as the syntax is very close to our normal language. Below is an example Python program for a `24 hours` digital clock.

{% highlight python %}
import time

def clock():
  for i in range(24):
    for j in range(60):
      for k in range(60):
        print("the time is {}:{}:{}".format(i,j,k))
        time.sleep(1)

clock()
{% endhighlight %}


[Gudovan-Roseum]: https://jekyllrb.com/docs/home
[interpreted-language]:   https://github.com/jekyll/jekyll
[High-level-language]: https://talk.jekyllrb.com/
