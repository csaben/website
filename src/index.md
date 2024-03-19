---
layout: base.liquid
---

### Clark Saben <span style="font-size: 0.6em;">(pseudonym 'arelius' iyk Cradle yk)</span>
Hi, I'm Clark Saben and this space is for some of my thoughts and projects to live.

I am currently a student at the University of Mary Washington (4th year) studying Mathematics and Physics. 

Links: [[Portfolio](https://portfolio-v2-kappa-dun-71.vercel.app/)] [<a href="/assets/Clark_Saben_Resume_r1.pdf" target="_blank">Resume</a>] [[Twitter](https://twitter.com/ClarkSaben)]


### Posts

{% for post in collections.posts reversed %}
  <p>
    <span style="opacity: 0.5;">{{ post.data.date | date: "%b %d, %Y" }} |</span>
    <span><a href="{{ post.url }}">{{ post.data.title }}</a></span>
  </p>
{% endfor %}