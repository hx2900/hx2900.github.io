---
layout: page
title: About
description: 道路千万条，安全第一条
keywords: Xin Huang，airlin_hx
comments: true
menu: 关于
permalink: /about/
---

有些事情不是看到希望才去坚持，

而是坚持了才会看到希望。


## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
