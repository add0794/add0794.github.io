---
layout: default
title: Projects
permalink: /projects
---

<html>
    <body>
        <h1>JavaScript</h1>
        {% for post in site.posts %}
            {% if post.categories contains "javascript" %}
                <article>
                    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                    <p>{{ post.excerpt }}</p>
                </article>
            {% endif %}
        {% endfor %}
        <h1>Python</h1>
        {% for post in site.posts %}
            {% if post.categories contains "python" %}
                <article>
                    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                    <p>{{ post.excerpt }}</p>
                </article>
            {% endif %}
        {% endfor %}
        <h1>Excel</h1>
        {% for post in site.posts %}
            {% if post.categories contains "excel" %}
                <article>
                    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                    <p>{{ post.excerpt }}</p>
                </article>
            {% endif %}
        {% endfor %}
    </body>
</html>
