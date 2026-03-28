---
layout: default
title: ""
---

<h1 style="text-align:center; margin-bottom:10px;">Welcome to the Hearing World!</h1>

<img src="/assets/images/cartoon.JPG" 
     style="display:block; margin:20px auto; width:220px; border-radius:12px;">

<p style="text-align:center; font-weight:600; max-width:650px; margin:0 auto;">
Let’s explore together. This is a space where I write about hearing, hearing loss, Audiology, Assistive Technology, and personal experience.
</p>




 
___

<h2 style="text-align:center;">What you’ll find here</h2>

- Everyday explanations of hearing and hearing loss
- Thoughts on Audiology care and hearing technology
- Personal reflections on living with hearing loss
- Practical tips for communication and accessibility






<h2 style="text-align:center;">Why I started this blog</h2>

Hearing is more than ears — it’s how we connect, learn, and belong. I wanted to create a space that explains these topics in a way that feels clear, human, and real.


<h2 style="text-align:center;">Posts</h2>

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

<div style="clear:both;"></div>
