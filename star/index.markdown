---
layout: post
title:  "收藏"
categories: 技术收藏
---

<div class="container-fluid">

<div class="row">
	<h3>技术好文</h3>
	{% for article in site.data.star_articles %}
	<div class="col-xs-12 col-sm-6 col-md-4 col-lg-3">

    <div class="thumbnail">
    	<div style="background-image:url(../assets/star_item/insta-2.jpg);" class="panel-heading"></div>
      <!-- <img src="../assets/star_item/insta-2.jpg" alt="..." class="img-responsive"/> -->
      <!-- <img src="" alt="..." class="img-responsive"/> -->
      <div class="caption">
        <h4>{{ article.title }}</h4>
        <p><a href="{{ article.url }}" target="_blank" class="btn btn-primary" role="button">阅读</a></p>
      </div>
    </div>

	</div>
	{% endfor %}
</div>

<div class="row">
	<h3>个人博客</h3>
	{% for blog in site.data.star_blogs %}
	<div class="col-xs-12 col-sm-6 col-md-4 col-lg-3">

    <div class="thumbnail">

    	<div style="background-image:url(../assets/star_item/insta-2.jpg);" class="panel-heading"></div>
      <div class="caption">
        <h4>{{ blog.name }}</h4>
        <p><a href="{{ blog.url }}" target="_blank" class="btn btn-primary" role="button">阅读</a></p>
      </div>
    </div>

	</div>
	{% endfor %}
</div>

<div class="row">
	<h3>技术站点</h3>
	{% for website in site.data.star_websites %}
	<div class="col-xs-12 col-sm-6 col-md-4 col-lg-3">

    <div class="thumbnail">
    	<div style="background-image:url(../assets/star_item/insta-2.jpg);" class="panel-heading"></div>
      <div class="caption">
        <h4>{{ website.name }}</h4>
        <p><a href="{{ website.url }}" target="_blank" class="btn btn-primary" role="button">阅读</a></p>
      </div>
    </div>

	</div>
	{% endfor %}
</div>

</div>
