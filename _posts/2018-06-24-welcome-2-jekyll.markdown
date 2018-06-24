---
layout: post
title:  "Terminal application launching"
date:   2018-06-23 16:08:10 -0400
categories: jekyll update
---
Bash/UNIX scripting is very underrated.

Basic
{% highlight bash %}
alias at = 'open -a "Atom"'
# opens a file using the Atom text editor
{% endhighlight %}

Advanced
{% highlight bash %}
alias ch = 'open -a "Google Chrome"'
# usage:
# ch https://google.com

alias chi = '/Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --args --incognito &>/dev/null &'
# opens a new Google Chrome incognito window

{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
