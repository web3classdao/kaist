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

<div class="logo">
<a href="https://www.bisonai.com/" target="_black"><img class="logo-image" src="/kaist/assets/images/bisonai.png" alt="Bisonai"></a>
<a href="https://www.bitblue.team/" target="_black"><img class="logo-image" src="/kaist/assets/images/bitblue.jpg" alt="bitBLUE"></a>
<a href="https://www.companoid.io/" target="_black"><img class="logo-image" src="/kaist/assets/images/companoidlabs.png" alt="Companoid Labs"></a>
<a href="https://coredot.io/" target="_black"><img class="logo-image" src="/kaist/assets/images/coredotlab.png" alt="Coredotlab"></a>
<a href="https://www.genesislab.com/" target="_black"><img class="logo-image" src="/kaist/assets/images/genesislab.png" alt="Genesis Lab"></a>
<a href="https://havah.io/" target="_black"><img class="logo-image" src="/kaist/assets/images/havah.png" alt="Havah"></a>
<a href="https://dcentwallet.com/" target="_black"><img class="logo-image" src="/kaist/assets/images/iotrust.png" alt="iotrust"></a>
<a href="https://nftbank.ai/" target="_black"><img class="logo-image" src="/kaist/assets/images/nftbank.jpg" alt="NFTBank"></a>
<a href="https://off.live/" target="_black"><img class="logo-image" src="/kaist/assets/images/off.png" alt="OFF"></a>
<a href="http://www.paulus.pro/" target="_black"><img class="logo-image" src="/kaist/assets/images/paulus.jpg" alt="Paulus"></a>
<a href="https://theori.io/" target="_black"><img class="logo-image" src="/kaist/assets/images/theori.png" alt="Theori"></a>
<a href="https://www.facebook.com/uprootcompany/" target="_black"><img class="logo-image" src="/kaist/assets/images/uprootcompany.png" alt="Uproot Company"></a>
<a href="https://www.linkedin.com/in/ekjoo/" target="_black"><img class="logo-image" src="/kaist/assets/images/wasd3r.png" alt="WASD3R"></a>
</div>
