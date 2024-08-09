---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD student at [LIRIS](https://feb.kuleuven.be/research/decision-sciences-and-information-management/liris), KU Leuven, working on ML for geospatial data and real estate, supervised by Jochen De Weerdt (KU Leuven) and Seppe vanden Broucke (UGent). I received my master's Business and Information Systems Engineering from KU Leuven in 2021. 

News
======
* **[31/05/2024]** One paper accepted at the STRL workshop at IJCAI 2024.
* **[8/06/2024]** Our paper was accepted as Data Mining and Knowledge Discovery.
* **[13/05/2023]** Our paper was accepted at ISPRS International Journal of Geo-Information.
* **[1/06/2023]** One paper accepted at the STRL workshop at IJCAI 2023.
* **[15/03/2022]** My master's thesis was accepted at the RCIS'22 Forum.
* **[1/09/2021]** I started my PhD!

Publications
======
{% for link in site.data.publications.main %}

{% if link.image %}   {% endif %} {% if link.conference_short %} {{ link.conference_short }} {% endif %}
{{ link.title }}
{{ link.authors }}
{{ link.conference }}
{% if link.pdf %} PDF {% endif %} {% if link.code %} Code {% endif %} {% if link.page %} Project Page {% endif %} {% if link.bibtex %} BibTex {% endif %} {% if link.notes %} {{ link.notes }} {% endif %} {% if link.others %} {{ link.others }} {% endif %}

{% endfor %}
