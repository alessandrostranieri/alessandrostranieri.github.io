---
layout: default
title: Books
permalink: /books/
---

<ul>
{% for book in site.data.books %}
  <p>
  {{ book.title }} <br>
  {{ book.authors }} <br>
  {{ book.isbn }} <br>
  </p>
{% endfor %}
</ul>