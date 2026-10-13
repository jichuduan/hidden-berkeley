---
layout: default
title: Hidden Berkeley
---

# Hidden Berkeley_jichu

Jichu Duan's Guide to Hidden Berkeley. Berkeley has many useful places that new students only discover by accident. This guide collects a few of them so you can find quiet study spots, research help, and support services sooner.

<!-- Edit the heading and introduction above. The supplied loop below displays each row of the CSV. -->
{% for resource in site.data.locations %}

### {{ resource.name | escape }}

**Category:** {{ resource.category | escape }}  
**Area:** {{ resource.area | escape }}  
**Access note:** {{ resource.access_note | escape }}  
<a href="{{ resource.source_url | escape }}">Official source</a>

{% endfor %}

---

The entries come from this project's CSV. Confirm current details using the official links.
