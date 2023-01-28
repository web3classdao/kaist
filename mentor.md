---
layout: page
title: Mentor
nav_order: 3
description: A listing of all the course mentors.
---

# Mentors

Mentors come from various blockchain/web3 companies. The list will be updated. 

{% assign mentors = site.staffers | where: 'role', 'Mentor' %}
{% for staffer in mentors %}
{{ staffer }}
{% endfor %}

## Mentor's affiliated companies

[![bitBLUE](/kaist/assets/images/bitblue.png)](https://www.bitblue.team/)
[![Companoid Labs](/kaist/assets/images/companoidlabs.png)](https://www.companoid.io/)
