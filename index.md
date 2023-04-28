---
layout: default
---

At WHAI, we're AI-enthusiasts exploring machine capabilities by delving into cutting-edge tools and technology to enhance our creative output.

Our focus is incorporating generative AI into our creations, venturing into lesser-known realms of machine intelligence, while constantly learning. Transparency is central to WHAI's methodology, striving to share knowledge and breakthroughs openly for a responsible AI community.

Our pursuits uncover groundbreaking discoveries and tackle complex challenges in the evolving AI landscape. Guided by curiosity and experimentation, we humbly utilize generative AI, like in this text, to explore AI's transformative potential.

---

<h2 class="posts-title">Posts</h2>

<div class="post-list">
{% for post in site.posts %}
  <div class="post">
    <h3 class="post-title">
      <span class="post-date">{{ post.date | date: "%Y-%m-%d" }}</span>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </h3>
  </div>
{% endfor %}
</div>
