---
layout: post
title:  "Fielding REST Dissertation - Introduction"
date:   2019-07-17 22:17:22 -0500
categories: Paper analysis
---

This post is the start of a series of posts focused on Roy Fielding's [dissertation][fielding-dissertation] on the REST network architecture. My motivation is to gain a deeper understanding of things I'm curious in by conveying my understanding and analysis.

I will begin with covering Fielding's Abstract and Introduction. The main motivation of his dissertation is to:

> `Understand, propose, and evaluate the architectural design of network-based application software.`

*What does he mean by `network-based application software`?* It's the kind of software that lets you access resources and services, essentially information, from a remote computer. The kind that not only grants you this ability to access this information, but to also convey it to others. The Internet. Of course the Internet is not the only network-based application software, but it's the most prevalent example of one. Imagine a high school classroom, and the teacher has her back to the class while scribbling some notes on the blackboard. Several students are taking notes, several are distracted on their computers, and several still are sleeping. Now imagine several students passing notes between each other. In this scene, these students are communicating...they have formed a network. The "software" necessary for this communication to be possible is a pen, paper, a throw, and a catch. Of course, the teacher turns around, and intercepts the note, but this is also part of the system of communication; it's part of the "software". In short, network-based application software is a means of communicating information. Only in this case, the students are computers, and the teacher is a failure in the system of communications. Of course, for the software to be useful, it must be know what to do for various failures and various scenarios.

*What does he mean by `architectural design`?* Weren't we talking about software, not buildings? Well, just as in architecture there is an adage `"Form follows function"`, he states that to understand and build an architectural design of network-based application software, one must 

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[fielding-dissertation]: https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm
[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
