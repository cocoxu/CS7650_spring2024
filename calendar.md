---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

A tentative plan for the schedule (topics, deadlines, etc.) is available [here](https://docs.google.com/spreadsheets/d/1YPCGxG5w7meDsA2ysbG4C5ZFPd89nseoih5SP3wBVjU/edit?usp=sharing).


{% for module in site.modules %}
{{ module }}
{% endfor %}
