---
layout: page
title:  "Automating Makerlog with Apple Shortcuts"
date:   2021-06-30 01:45:51 +0300
# categories: jekyll update
---
## Prologue

I really like logging my daily tasks and keeping up with streaks.

But doing it from phone takes some efforts. By saying "efforts" I mean going throught the mess of visual actions - like opening the browser and searching for the website, then navigating it to find the right fields and so on...

So one day I thought:

> Can I have one icon on my home screen just for logging tasks? 

## Realization


`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
  