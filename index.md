---
layout: default
title: Home
---

# Welcome to My Personal Website

This is a simple site using Markdown and LaTeX equations.

## Sample Equation

Here is an inline equation: $E=mc^2$.

And a block equation:

$$
\int_{a}^{b} f(x) \, dx
$$

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
