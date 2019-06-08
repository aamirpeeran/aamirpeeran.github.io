---
title: portfolio
layout: portfolio
---

{% for post in site.posts %} 

<div class="portfolioTile">
     <a href="{{ post.url }}"><img src="square.jpg" style="width:25%;"><div class="tileText">{{ post.title}}</div></a>
    
</div>

{% endfor %}