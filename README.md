---
layout: default
title: 전혁건의 블로그
---

안녕하세요!  
이곳은 전혁건의 개발 공부 기록과 일상들을 담은 블로그입니다.

글 목록은 상단에서 확인할 수 있습니다.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>
