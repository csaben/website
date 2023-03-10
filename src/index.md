---
layout: base.liquid
---

### Clark Saben (sometimes arelius)
I am Clark Saben and I am a university student at the University of Mary Washington studying Mathematics and Physics. 

### Posts

{% for post in collections.posts reversed %}
  <p>
    <span style="opacity: 0.5;">{{ post.data.date | date: "%b %d, %Y" }} |</span>
    <span><a href="{{ post.url }}">{{ post.data.title }}</a></span>
  </p>
{% endfor %}
