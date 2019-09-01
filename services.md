---
layout: default
title: Services
---

# Services

<div class="">
	{% for service in site.data.services %}
		<div class="card my-3">
		  	<div class="card-body">
		  		<h5 class="card-title">{{ service.name }}</h5>
		  		<p class="card-text">{{ service.description }}</p>
		  	</div>
		</div>
	{% endfor %}
</div>