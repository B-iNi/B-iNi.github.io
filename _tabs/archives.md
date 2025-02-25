#---
#title: Archives
#icon: fas fa-archive
#order: 2
#---

{% for post in site.posts limit:5 %}
  - [{{ post.title }}]({{ post.url }})
{% endfor %}
---
layout: archives
icon: fas fa-archive
order: 3
---

