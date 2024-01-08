---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

A tentative plan for the schedule (topics, deadlines, etc.) is available [here](https://docs.google.com/spreadsheets/d/1OnB2sBq5kqIlrxscQ_l6tzIRD29XCASKz7WMZlbhV7E/edit?usp=sharing).


{% for module in site.modules %}
{{ module }}
{% endfor %}
