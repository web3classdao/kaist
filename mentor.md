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

<a href="https://www.bitblue.team/" target="_black">
	<img src="/kaist/assets/images/bitblue.jpg" width="200px" alt="bitBLUE">
</a>
<a href="https://www.companoid.io/" target="_black">
	<img src="/kaist/assets/images/companoidlabs.png" width="200px" alt="Companoid Labs">
</a>
