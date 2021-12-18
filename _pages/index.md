---
layout: page
permalink: /
title: Asellus aquaticus
---

# Welcome!

This the homepage of The Asellus Consortium, an interest group for the broad use of _Asellus aquaticus_ as a system to study ecological, evolutionary and developmental phenomena. We are currently still in the phase of consolidating knowledge, connecting among interest parties, and establishing of purpose.

<link href="/assets/lightbox/css/lightbox.css" rel="stylesheet" />
<div class="img_row">

	<a href="\assets\images\iso1.jpg" data-lightbox="gallery-1" data-title="Under the binocular">
	<img id="img_thumb_modal" src="\assets\images\iso1.jpg" alt="Under the binocular">
	</a>

	<a href="\assets\images\iso2.jpg" data-lightbox="gallery-1" data-title="In situ">
	<img id="img_thumb_modal" src="\assets\images\iso2.jpg" alt="In situ">
	</a>

	<a href="\assets\images\iso3.jpg" data-lightbox="gallery-1" data-title="Phenotypic variation">
	<img id="img_thumb_modal" src="\assets\images\iso3.jpg" alt="Phenotypic variation">
	</a>
	
</div>
<script src="/assets/lightbox/js/lightbox-plus-jquery.min.js"></script>

If you are interested in joining the consortium, and want help us to compile knowledge on _Asellus aquaticus_, better connect the community, organize meetings and symposia, or have ideas for projects and collaborations, please get in touch by sending an email to [info@asellus.org](mailto:info@asellus.org)

# News

<div class="post">
  {% for post in site.posts %}
    <article class="post">

      <h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>

		  <div class="entry">
			{{ post.excerpt }}
		  </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
