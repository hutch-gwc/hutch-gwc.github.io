---
layout: default
title: Facilitators
permalink: /facilitators/
---

{% for facilitator in site.facilitators %}
<img src="{{site.baseurl}}/assets/images/facilitators/{{facilitator.image}}">
<h2>
	<a href="{{ facilitator.url }}">
		{{ facilitator.name }}
	</a>
</h2>
{% endfor %}


<!-- <div class="bigspacer"></div> -->

<!-- {% for member in site.categories.team reversed %}
	{% if member.alumni != true %}
    {% cycle 'add rows': '<div class="row">', nil, nil %}
		<div class="col-md-4 memberbox">
			<div class="media">
  				<a class="pull-left" href="{{ member.url }}">
    				<img width=160 class="media-object" src="{{ member.image }}">
  				</a>
 			 	<div class="media-body">
    				<div class="head media-heading"><a href="{{ member.url }}" class="off">{{ member.title }}</a></div>
    				<p class="note">{{ member.position }}</p>
  				</div>
			</div>
			<div class="bigspacer"></div>
			<div class="bigspacer"></div>
        </div>
    {% cycle 'close rows': nil, nil, '</div>' %}
    {% endif %}
{% endfor %}
{% cycle 'close rows': nil, '</div>', '</div>' %} -->
