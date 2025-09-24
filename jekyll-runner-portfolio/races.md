---
layout: default
title: Races
---

# Race Portfolio

{% for race in site.data.races %}
## {{ race.title }}
- Distance: {{ race.distance }}
- Elevation: {{ race.elevation }}
- Date: {{ race.date }}
- Time: {{ race.time }}
[View on Strava]({{ race.strava_url }})

![Race photo]({{ race.image }})
{% endfor %}
