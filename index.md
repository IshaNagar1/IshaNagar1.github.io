---
layout: default
title: ""
permalink: /
---

<div style="
  background:
    linear-gradient(135deg, #fdf3ea 0%, #f9e7db 50%, #f6ddd0 100%),
    repeating-linear-gradient(
      135deg,
      rgba(255, 140, 120, 0.08) 0px,
      rgba(255, 140, 120, 0.08) 2px,
      rgba(255, 180, 150, 0.05) 2px,
      rgba(255, 180, 150, 0.05) 6px,
      transparent 6px,
      transparent 10px
    );
  padding: 40px;
  border-radius: 20px;
">

<div style="max-width:700px; margin:40px auto 60px auto; padding:0 20px;">

  <h1 style="font-size:2.6rem; line-height:1.2; margin:0 0 18px 0; font-weight:700;">
    Hearing in Real Life
  </h1>

  <p style="font-size:1.2rem; line-height:1.8; margin:0 0 34px 0; max-width:700px;">
    Welcome to a space focused on hearing, hearing loss, audiology, assistive technology, and lived experience.
  </p>

  <h2 style="font-size:1.75rem; margin:0 0 12px 0; font-weight:600;">
    What you’ll find here
  </h2>

  <ul style="font-size:1.08rem; line-height:1.9; margin:0 0 34px 0; padding-left:26px;">
    <li>Everyday explanations of hearing and hearing loss</li>
    <li>Thoughts on audiology care and hearing technology</li>
    <li>Personal reflections on living with hearing loss</li>
    <li>Practical tips for communication and accessibility</li>
  </ul>

  <h2 style="font-size:1.75rem; margin:0 0 12px 0; font-weight:600;">
    Why I started this blog
  </h2>

  <p style="font-size:1.08rem; line-height:1.85; margin:0 0 34px 0; max-width:700px;">
    Hearing is more than ears — it’s how we connect, learn, and belong. I wanted to create a space that explains these topics in a way that feels clear, human, and real.
  </p>

  <h2 style="font-size:1.75rem; margin:0 0 12px 0; font-weight:600;">
    Posts
  </h2>

  <ul>
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>

</div>

</div>
