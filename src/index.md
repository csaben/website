---
layout: base.liquid
---

### Clark Saben (sometimes arelius)
Hi, I'm Clark Saben and this space is for some of my thoughts and projects to live.

I am currently a student at the University of Mary Washington (3rd year) studying Mathematics and Physics. 

### Posts

{% for post in collections.posts reversed %}
  <p>
    <span style="opacity: 0.5;">{{ post.data.date | date: "%b %d, %Y" }} |</span>
    <span><a href="{{ post.url }}">{{ post.data.title }}</a></span>
  </p>
{% endfor %}
