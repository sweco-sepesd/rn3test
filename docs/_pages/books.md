---
permalink: /books
layout: page
title: Books
booksurl: {{ site.baseurl | append 'assets/documentation/assets/documentation' }}
---

Variables:

`site.url`: {{ site.url }}

{{ site.url }}/assets/documentation/help/index.html

`base_url`: {{ base_url }}

`site.baseurl`: {{ site.baseurl }}

`test`: {{ 'assets/documentation/assets/documentation/help/index.html' | prepend: site.baseurl }}

`booksurl`: {{ booksurl }}

[A]({% link /assets/documentation/help/index.html %})

[B]({% link assets/documentation/help/index.html %})


[B]({% link {{ booksurl | append: '/help/index.html' }} %})


