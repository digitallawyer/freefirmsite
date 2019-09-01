---
layout: default
title: Attorneys
---

# Attorneys
<div class="card-deck">
	{% for attorney in site.data.attorneys %}
		  <div class="card my-3" style="min-width: 30%;">
		    	<img src="{{ attorney.picture }}" class="card-img" alt="...">
		  		<div class="card-body">
		  			<h5 class="card-title">{{ attorney.name }}</h5>
		  			<p class="card-text">{{ attorney.bio }}</p>
		  		</div>
				<ul class="list-group list-group-flush">
				    <li class="list-group-item">Email: {{ attorney.email }}</li>
				    <li class="list-group-item">Call: {{ attorney.phone }}</li>
				</ul>
		  </div>
	{% endfor %}
</div>	
