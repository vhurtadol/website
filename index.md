---
layout: default
---

<div class="list">
  {% for list in site.list %}
    <article class="list">

      <h1><a href="{{ site.baseurl }}{{ list.url }}">{{ list.title }}</a></h1>

      <div class="entry">

      </div>

    </article>
  {% endfor %}
</div>

