---
layout: page
title: Academical service
permalink: /teaching
---


### Teaching
{% assign teaching = site.data.teaching | sort: 'year' | reverse %}
{% for item in site.data.teaching %}
  {% include teaching-item.html %}
{% endfor %}
<br>

### Talks 
{% assign talks = site.data.talks | sort: 'year' | reverse %}
{% for item in talks %}
  {% include talk-item.html %}
{% endfor %}
<br>

### Voluntary work
- **Co-organiser** of the Learning-on-Graphs (LoG) conference 2023.
- **Organiser** of local meetups in Paris about Graph Machine Learning.
- **Contributor** to open source libraries (e.g. Pytorch Geometric).
- **Reviewer** for ICML, NeurIPS, LoG and the Web Conference.
- **Lab representative** at CVN CentraleSupelec and Inria OPIS.
- **Supervisor** of one MSc intern at Mila and ENS MVA students. 
- **AI for Tomorrow**: write articles about AI, discuss challenges and promote beneficial usage.
<br>

### Awards
- **Runner-up** award in the 3 Minutes Thesis (**3MT**) competition with Universit ́e Paris-Saclay.
- **Mitacs Globalink Scholarship** award obtained in 2022 for my work on accelerated catalysis discovery, with Prof. Yoshua Bengio, Prof. David Rolnick and Prof. Fragkiskos Malliaros.
- **SIGIR Student Travel Grant** to participate in CIKM 2022 international conference in Atlanta (US). 
