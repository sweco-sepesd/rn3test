---
permalink: /books
layout: page
title: Books

---

Variables:

`site.url`: {{ site.url }}

{{ site.url }}/assets/documentation/help/index.html

`base_url`: {{ base_url }}

`site.baseurl`: {{ site.baseurl }}


[A]({% link /assets/documentation/help/index.html %})

[B]({% link assets/documentation/help/index.html %})

[C]({% link {{ assets/documentation/help/index.html | prepend:site.baseurl }} %})
