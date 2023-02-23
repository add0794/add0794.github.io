---
layout: default
title: Projects
permalink: /projects/
---

<!-- Check out independent projects I've completed, organized by programming language I used. -->

<html>
    <body>
        <h1>Python</h1>
        {% for post in site.posts %}
            {% if post.categories contains "python" %}
                <article>
                    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                    <!-- <p style="font-size: 10px;">{{ post.date }}</p> -->
                    <p>{{ post.excerpt }}</p>
                </article>
            {% endif %}
        {% endfor %}
        <h1>Excel</h1>
        {% for post in site.posts %}
            {% if post.categories contains "excel" %}
                <article>
                    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                    <!-- <p style="font-size: 10px;">{{ post.date }}</p> -->
                    <p>{{ post.excerpt }}</p>
                </article>
            {% endif %}
        {% endfor %}
    </body>
</html>
