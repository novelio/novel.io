---
layout: default
---

<h1 class="site-logo"><img src="/assets/logo.svg" alt="novel i/o" width="1455" height="282"></h1>

detail-oriented software and consulting, at your service.

get in touch: <a href="mailto:cody@novel.io">cody@novel.io</a>

<section class="products" aria-label="products">
<ul>
{% for product in site.data.products %}
<li><a class="product-card" href="{{ product.url }}">
<span class="product-mark" aria-hidden="true" style="background: {{ product.mark.background }};"><span style="color: {{ product.mark.first }};">{{ product.monogram | slice: 0 }}</span><span style="color: {{ product.mark.second }};">{{ product.monogram | slice: 1 }}</span></span>
<span class="product-text"><span class="product-name">{{ product.name }}</span><span class="product-description">{{ product.description }}</span></span>
</a></li>
{% endfor %}
</ul>
</section>
