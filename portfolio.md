---
title: portfolio
layout: portfolio
---

{% for post in site.posts %} 

<div class="portfolioTile">
     <a href="{{ post.url }}"><div class="tile"></div><div class="tileText">{{ post.title}}</div></a>
    
</div>

{% endfor %}