---
layout: home
permalink: /
---

<style>
p, h1 {
  display:none;
  }
.entry-content p, h1.entry-title {
  display: block !important;
}
</style>

{% assign post = site.posts.first %}
{% assign content = post.content %}
{% include post_detail.html %}