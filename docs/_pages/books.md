---
permalink: /books
layout: page
title: Books
---

Variables:

`site.url`: {{ site.url }}

`site.baseurl`: {{ site.baseurl }}

{% capture booksurl %}{{ site.url | append: site.baseurl }}/assets/documentation{% endcapture %}

`booksurl`: {{ booksurl }}

`helpurl`: {{ booksurl | append: '/help/index.html' }}

`helpurl2`: {{ site.baseurl | append: '/assets/documentation/help/index.html' }}
