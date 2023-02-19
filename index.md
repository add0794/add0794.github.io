---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
---

# Welcome to my page!

I'm a data analyst that will help you and/or your organization make well-informed decisions by efficiently and effectively making sense of your data. Originally trained as a sustainability consultant, I've self-taught Python, SQL, Tableau, R, Git, Linux, and LaTeX. I am, additionally, a Certified Scrum Master (CSM) and Data Analyst Associate and Data Analyst Professional by Data Camp, and working toward the Project Management Professional (PMP) certification.

I regularly complete independent projects using Excel, Python, SQL, or Tableau (or a mix), all of which are below. I [blog](https://furry-date-ae4.notion.site/Rethinking-Circular-Economy-34b44ede819c49158d207ac18607e85d) regularly and invite you to learn about "circular economy!"

Please feel free to contact me at any time [here](mailto:add0794@gmail.com?subject=Excited to Connect with You!).

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