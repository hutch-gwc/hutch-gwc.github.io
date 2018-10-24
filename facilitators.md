---
layout: page
title: Facilitators
permalink: /facilitators/
---
<div class="row">
	<div class="col-md-12">
		<div class="title">
			Current members
		</div>
	</div>
</div>

{% for facilitator in site.facilitators %}
  <h2>{{ facilitator.name }} - {{ facilitator.position }}</h2>
  <p>{{ facilitator.content | markdownify }}</p>
  <img src="{{site.baseurl}}/assets/images/facilitators/{{facilitator.image}}">
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
