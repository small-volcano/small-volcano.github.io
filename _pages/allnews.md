---
title: "Can Bu (卜灿) - News"
layout: gridlay
excerpt: "Wenbo Huang"
sitemap: false
permalink: /allnews
---
<div class="col-sm-4" align="right" style="display:table-cell; vertical-align:middle; text-align:center">

  <ul style="overflow: hidden">
  <a href ="https://wenbohuang1002.github.io"> <img align="right" src="{{ site.url }}{{ site.baseurl }}/images/NewsCloud.png" class="img-responsive" width="100%" /></a>
  </ul>
  <ul style="overflow: hidden">
  <a href ="https://wenbohuang1002.github.io"> <img align="right" src="{{ site.url }}{{ site.baseurl }}/images/ActivityR.png" class="img-responsive" width="100%" /></a>
  </ul>
  <ul style="overflow: hidden">
  <a href ="https://wenbohuang1002.github.io"> <img align="right" src="{{ site.url }}{{ site.baseurl }}/images/ActivityC.png" class="img-responsive" width="100%" /></a>
  </ul>
  <!-- The shapes of the word cloud is <a href ="https://nishinonanase.com">Nishino Nanase</a> and <a href ="https://weibo.com/snh48wangxiaojia">Xiaojia Wang</a><br> -->
  The word cloud was made by <a href ="https://wordart.com/">WordArt</a>
</div>


<div class="col-sm-8">

## News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}

</div>