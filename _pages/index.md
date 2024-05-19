---
permalink: /
---
{% assign title = "Week 01: Getting Started" %}
{% capture topics %}
  programming
  p5-setup
  p5-intro
  drawing
  variables
  transformations
{% endcapture %}
{% include home-section.html section="week01" title=title topics=topics %}

{% assign title = "Week 02: Structures" %}
{% capture topics %}
  conditionals
  patterns
  counters
  functions
  random
{% endcapture %}
{% include home-section.html section="week02" title=title topics=topics %}

{% assign title = "Week 03: Time" %}
{% capture topics %}
  arrays
  strings
  objects
  classes
  maths
  animations
{% endcapture %}
{% include home-section.html section="week03" title=title topics=topics %}

{% assign title = "Week 04: Randomness and Simulations" %}
{% capture topics %}
  cycles
  sincos
  vectors
  more-random
{% endcapture %}
{% include home-section.html section="week04" title=title topics=topics %}

{% comment %}

{% assign title = "Week 05: Data Structures" %}
{% capture topics %}
{% endcapture %}
{% include home-section.html section="week05" title=title topics=topics %}

{% assign title = "Week 06: Systems and Patterns" %}
{% capture topics %}
{% endcapture %}
{% include home-section.html section="week06" title=title topics=topics %}

{% endcomment %}
