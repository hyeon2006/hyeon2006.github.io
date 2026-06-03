---
layout: default
---

# Welcome!

반갑습니다. 제 깃허브 블로그에 오신 것을 환영합니다.

# My Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span style="color: #666;"> - {{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endfor %}
</ul>
