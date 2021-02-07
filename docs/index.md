---
layout: page
title: simple site
tagline: Easy websites with GitHub Pages
description: Minimal tutorial on making a simple website with GitHub Pages
---

[home](index)  [about](about)
===

[Github Pages](https://pages.github.com) provide a simple way to make a website using [Markdown](https://daringfireball.net/projects/markdown/) and [git](https://git-scm.com).

This means no need to 

- work with html and css
- find a hosting site
- transfer stuff to the hosting site

With [GitHub Pages](https://pages.github.com), you just write things in [Markdown](https://daringfireball.net/projects/markdown/), [GitHub](https://github.com) hosts the site for you, and you just push material to your GitHub repository with `git add`, `git commit`, and `git push`.

Markdown supports fancy code blocks:

```python
def factorial(num):
    total = num
    for i in range(num - 1):
        total *= i
    return total
f_5 = factorial(5)
print(f_5)
```

...checkboxes:

**todo**

[ ] item 1
[ ] item 2
  [ ] subitem
[ ] item 3

If you love [git](https://git-scm.com/) and [GitHub](https://github.com), you'll love [GitHub Pages](https://pages.github.com), too.

The sites use [Jekyll](https://jekyllrb.com/), a [ruby](https://www.ruby-lang.org/en/) [gem](https://rubygems.org/), to convert Markdown files to html, and this part is done automatically when you push the materials to the `gh-pages` branch of a GitHub repository.
