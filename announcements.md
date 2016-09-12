---
layout: home
title: Announcements
---

<div class="course-title">Announcements</div>
{% for post in site.posts %}
<div class="grey">{{ post.date | date_to_string }}</div>
<h2 class="announcement-title" style="color: #000;">{{ post.title }}</h2>
{{ post.content }}
{% endfor %}
