---
title: Koala Lesson Plans
---

<div class="callout">
  Koalas
  <img src="/assets/img/koala-2.svg" alt="a koala" style="width:2em;">
  <ul class="menu vertical">
    {% for post in site.categories.koalas %}
    <li>
      <a href="{{ post.url }}">
        <span style="font-size:0.7em;">week</span>
        {{ post.categories[2] | remove: "week-" }}
        |
        <span style="font-size:0.7em;">
        {{ post.title | slice: 0, 3 }}
        </span>
      </a>
    </li>
    {% endfor %}
  </ul>
</div>
