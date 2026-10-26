---
title: Home
layout: base
date: 2026-01-01
summary: An online-only museum of historical objects and the essays written about them.

# The object featured in the opening spotlight. Use an object's folder name.
spotlight: planispheric-astrolabe
spotlight-note: A brass model of the sky that could tell the time, find north and point toward Mecca.

hero:
  kicker: An online-only museum
  title: Your Museum Name Goes Here
  text: Objects from across four thousand years, gathered into rooms and read in essays. Everything on this page is placeholder until your class replaces it.
---

{% include museum/home-opening.html %}

{% include museum/section.html %}

{: .m-statement}
This museum has no building. It exists only here, where every object is a *question* and every room is an attempt to answer it.

{% include museum/section-end.html %}

{% include museum/section.html tone="tint" %}

## The rooms

[All exhibitions →]({{ site.baseurl }}/exhibitions)

{% include museum/exhibition-grid.html collection="exhibitions" limit=3 %}

{% include museum/section-end.html %}

{% include museum/section.html %}

## Travel through time

[Full timeline →]({{ site.baseurl }}/timeline)

{% include museum/ribbon.html collection="objects" %}

{% include museum/section-end.html %}

{% include museum/section.html tone="tint" %}

## Essays

[All essays →]({{ site.baseurl }}/essays)

{% include museum/essay-grid.html collection="essays" limit=3 %}

{% include museum/section-end.html %}

{% include museum/section.html tone="dark" %}

## Choose your route

Take a guided route, fifteen minutes or an afternoon.

[Plan your visit]({{ site.baseurl }}/visit) · [Browse all objects]({{ site.baseurl }}/objects) · [See the map]({{ site.baseurl }}/map)

{% include museum/section-end.html %}
