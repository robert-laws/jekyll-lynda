---
layout: default
permalink: /posts/
---

### Posts Page

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{site.baseurl}}{{post.url}}">{{post.title}}</a>
  </li>
{% endfor %}
</ul>