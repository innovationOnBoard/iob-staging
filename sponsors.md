---
layout: sponsor_page
title: Sponsors
description: Sponsors and Community Supporters
image: assets/images/pic05.jpg
---

<h2 style="color: #2a2f4a !important;">Platinum</h2>
<div class="row">
{% for sponsor in site.sponsors %}
	{% if sponsor.status == 'platinum' %}
		<div class="4u 12u$(small)" style="text-align:center;">
			<span class="image fit">
				<img src="{{ sponsor.img | prepend: site.baseurl | prepend: site.url }}" class="img-sponsor">
			</span>
		</div>
	{% endif %}
{% endfor %}
</div>

<hr>

<h2 style="color: #2a2f4a !important;">Gold</h2>
<div class="row">
{% for sponsor in site.sponsors %}
	{% if sponsor.status == 'gold' %}
		<div class="4u 12u$(small)" style="text-align:center;">
			<span class="image fit">
				<img src="{{ sponsor.img | prepend: site.baseurl | prepend: site.url }}" class="img-sponsor">
			</span>
		</div>
	{% endif %}
{% endfor %}
</div>

<hr>

<h2 style="color: #2a2f4a !important;">Silver</h2>
<div class="row">
{% for sponsor in site.sponsors %}
	{% if sponsor.status == 'silver' %}
		<div class="4u 12u$(small)" style="text-align:center;">
			<span class="image fit">
				<img src="{{ sponsor.img | prepend: site.baseurl | prepend: site.url }}" class="img-sponsor">
			</span>
		</div>
	{% endif %}
{% endfor %}
</div>

<hr>

<h2 style="color: #2a2f4a !important;">Community Partners</h2>
<div class="row">
{% for sponsor in site.sponsors %}
	{% if sponsor.status == 'partner' %}
		<div class="4u 12u$(small)" style="text-align:center;">
			<span class="image fit">
				<img src="{{ sponsor.img | prepend: site.baseurl | prepend: site.url }}" class="img-sponsor">
			</span>
		</div>
	{% endif %}
{% endfor %}
</div>