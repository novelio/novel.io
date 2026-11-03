---
layout: default
---

<h1 class="site-logo"><img src="/assets/logo.svg" alt="novel i/o" width="1455" height="282"></h1>

detail-oriented software and consulting, at your service.

<section class="products">
<h2>products</h2>
<ul>
{% for product in site.data.products %}
<li><a href="{{ product.url }}">{{ product.name }}</a><span class="product-description">{{ product.description }}</span></li>
{% endfor %}
</ul>
</section>

get in touch: <a href="mailto:cody@novel.io">cody@novel.io</a>
