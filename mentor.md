---
layout: page
title: Mentor
nav_order: 3
description: A listing of all the course mentors.
---

# Mentors

Confirmed mentors come from various blockchain/web3 companies: DSRV, Theori, Haechi Labs, NFTBank, Klaytn, D'CENT Wallet, AI Network, Code States, bitBLUE, KryptoSeoul, Xangle, OFF, Coredotlab, WASD3R, Genesis Lab, Changer, and several free workers. The list will be updated. 

{% assign mentors = site.staffers | where: 'role', 'Mentor' %}
{% for staffer in mentors %}
{{ staffer }}
{% endfor %}
