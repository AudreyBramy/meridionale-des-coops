---
title: "Articles"
order: 1
in_menu: false
blog_index: true
---
<aside>
  S'abonner via le <a href="{{ '/feed.xml' | relative_url }}">flux RSS</a>
  (<a href="https://flus.fr/carnet/a-quoi-servent-les-flux.html">c'est quoi ?</a>)
</aside>

{% for post in site.posts %}
<article class="blog-item">
  <h3>
    {{ post.title }}
  </h3>

  <a href="{{post.url | relative_url}}"> Lire l'article <span aria-hidden="true">➞</span></a>
</article>
<hr />
{% endfor %} 