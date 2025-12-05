---
layout: archive
title: "블로그"
permalink: /blog/
author_profile: true
---

여기는 **이정진의 블로그** 페이지입니다 😊  
수업 과제, 개발 공부 기록, 일상 기록들을 정리해두는 공간이에요.

{% include base_path %}

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
