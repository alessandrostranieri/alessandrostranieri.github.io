---
layout: default
title: Books
permalink: /books/
---

<h1>Favorite books</h1>

Here's a list of my favourite books about:

* software engineering
* productivity
* just cool computer stuff

<ul>
{% for book in site.data.books %}
  <h2>{{ book.title }}</h2>
  Author(s): {{ book.authors }} <br>
  ISBN: {{ book.isbn }} <br>
{% endfor %}
</ul>