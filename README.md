---
layout: home
permalink: /
---

<style>
p {
  display:none;
  }
.entry-content p {
  display: block !important;
}
</style>

{% assign post = site.posts.first %}
{% assign content = post.content %}
{% include post_detail.html %}