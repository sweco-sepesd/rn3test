---
permalink: /books
layout: page
title: Books
booksurl: site.baseurl | append '/assets/documentation'
---

Variables:

`site.url`: {{ site.url }}

{{ site.url }}/assets/documentation/help/index.html

`base_url`: {{ base_url }}

`site.baseurl`: {{ site.baseurl }}

`test`: {{ '/assets/documentation/help/index.html' | prepend: site.baseurl }}

`test2`: {{ site.baseurl | append '/assets/documentation' }}

`booksurl`: {{ booksurl }}

[A]({% link /assets/documentation/help/index.html %})

[B]({% link assets/documentation/help/index.html %})






