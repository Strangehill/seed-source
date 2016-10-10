---
title: Lion Lesson Plans
category: lions
---

<div class="callout">
<a href="#">
  Lions
  <img src="/assets/img/lion-2.svg" alt="a lion" style="width:2em;">
</a>
<ul class="menu vertical">
  {% for post in site.categories.lions %}
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

