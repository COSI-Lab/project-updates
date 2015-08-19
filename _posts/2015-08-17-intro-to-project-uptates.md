---
layout: post
title: Intro to Project Updates
author: Benjamin Lannon
---

Welcome to Project updates, a site for hosting updates on work being done inside
COSI. The site is being hosted on Github with Github-Pages and Jekyll, which
allows us to only need to make a commit to the repository to push an update. With
Jekyll, all posts are put in the \_posts/ directory after being pulled down onto
a machine. each document is written in markdown and saved with a format of
yyyy-mm-dd-title.md. (Example: this article is 2015-08-17-intro-to-project-updates.md)

features
---

Any main markdown document can be rendered using Jekyll, although a few packages allow
specific features such as code snippets and TeX rendering.

It supports syntax highlighting of many relevant languages (C, C++, Java, Python, etc.)
as seen below.

{% highlight c %}
//Have some C code
int main() {
  printf("Hello World!\n");
}
{% endhighlight %}

Also through a package called [KaTeX](https://khan.github.io/KaTeX/), you can
display TeX expressions as seen below

$$f(x) = \frac{x^2 + 2x}{2 - x}$$

How to use Project updates
---

A document on how to write a post can be found on jekyll's site [here](http://jekyllrb.com/docs/posts/).
once the document is done, make a commit including your post and push it up to the Github repository
under the gh-pages branch.
