---
layout: page
title: "Home"
---

# Matthew Bull

I'm a desiger and web developer, with quite a few years experience of designing things on the internet.

People often talk about *building* in terms of websites. I like to think in terms of *design*. Whether it's user research, Figma prototyping or PHP coding - it's all a process where we attempt to design something that meets the needs of people using the website.

I prefer minimal designs and simplicity, although a dash of colour here and there never goes amiss.

<ul>
{% for post in site.posts limit:5 %}
    <li>
        <a class="page-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a><span> - {{ post.date | date: "%e %B %Y" }}</span>
    </li>
{% endfor %}
</ul>