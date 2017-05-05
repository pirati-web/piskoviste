---
layout: default
section: blog
description: Stránka táborské pirátské buňky s nejnovějšími články a základním rozcestníkem.
keywords: organizace,transparence,politika
---

<section class="callout large">
	<div class="row">
		<div class="small-12 faded medium-8 columns">
			<h1>Piráti PIskoviste</h1>
      <h2 class="subheader">bfslafkjsalfelfakjaslfja</h2>
			<ul>
				<li>chces si zkusit blogovat</li>
				<li>djkasjfkdsahfkash</li>
				<li>fsjkjahfkjasfhksajfehea</li>
			</ul>
		</div>
	</div>
</section>

<section>
  <div class="row small-up-1 medium-up-2">
  {% for post in site.posts limit:4 %}
    <div class="column">
    {% include shared/articlesumary.html %}
    </div>
  {% endfor %}
  </div>
</section>
