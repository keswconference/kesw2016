---
layout: page
title: News
published: true
---

{% for post in site.posts %}
<article>
    <header>
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <span class="submitted">
            <span>Posted on {{ post.date | date: "%-d %B %Y" }}</span>
        </span>
    </header>
    <div class="content node-blog">{{ post.excerpt }}</div>
    <footer>
        <ul class="links inline">
            <li class="node-readmore first">
                <a href="{{ post.url }}" >Read more</a>
            </li>
        </ul>
    </footer>
</article>
{% endfor %}
