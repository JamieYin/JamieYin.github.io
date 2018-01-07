---
layout: archive
title: "信息可视化作品集"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: "期末作品"
tags: []
image: 
  feature: 
  teaser:
---
<a href="https://public.tableau.com/profile/.25311013#!/vizhome/_18372/sheet3"><img src="/images/四大交通类型与三大地区的关系.png" width="900" height="687" border="0" /></a>

其他作品：
<div class="tiles">
{% for post in site.categories.tableau %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 tableau 的列出来-->