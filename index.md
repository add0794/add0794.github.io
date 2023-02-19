---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
---

# Welcome to my page!

I'm a data analyst that will help you and/or your organization make well-informed decisions by efficiently and effectively making sense of your data. 

You can find independent samples of my work using Excel, Python, SQL, and Tableau below.

<html>
  <head>
  </head>
  <body>
    {% for post in site.posts %}
      <article>
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p style="font-size: 10px;">{{ post.date }}</p>
        <p>{{ post.excerpt }}</p>
      </article>
    {% endfor %}
  </body>
</html>