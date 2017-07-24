---
title: Foreign Teams
date: 2017-07-24 21:00:00
categories: events
author: rath
excerpt: "Wanna play with us? You've come to the right place!"
---

This page is still under development. Basically, if you're looking to play with us,
we'd love to hear from you.

Come to our teamspeak `hms-community.teamspeak3.com` to get the ball rolling!

{% for team in site.data.teams %}
{% if team.name %}

	### {{ team.name }}

	Country: {{ team.country }}

	{% for link in site.data.teams.links %}

		{% if link.steam %}
			Steam Group: {{ link.steam }}
		{% endif %}

		{% if link.url %}
			Website: {{ link.url }}
		{% endif %}

		{% if link.youtube %}
			Youtube Channel: {{ link.youtube }}
		{% endif %}

		{% if link.facebook %}
			Facebook Page: {{ link.facebook }}
		{% endif %}

	{% endfor %}

{% endif %}

{% endfor %}
