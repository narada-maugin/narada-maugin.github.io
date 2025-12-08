---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can find a detailed CV from December 2025 by clicking <a href="/files/CV/CV_12_2025.pdf" target="_blank">here (French)</a>.  
The courses I have taken in the LOGOS Master are listed on the <a href="/courses/" target="_blank">Courses</a> page.


Education
======
* Master’s program [Logos](https://master-logos.fr/), Université Paris Cité, 2024–2026
* Bachelor’s degree in Mathematics, Nantes Université, 2022–2024
* MP2I scientific preparatory class, Lycée Clemenceau (Nantes), 2021–2022
* Baccalauréat (Mathematics, Physics-Chemistry), Lycée David d’Angers, 2020–2021

Working Experience
======
* **Research intern – [LAMSADE](https://www.lamsade.dauphine.fr/), May 2025 - January 2026**
  * PokerGPT: playing (correct) poker with a large language model
  * Supervisor: [Tristan Cazenave](https://www.lamsade.dauphine.fr/~cazenave/index.php), full professor

* **Research intern – [Centre François Viète](https://cfv.univ-nantes.fr/), May - July 2024**
  * Poker : itinéraire scientifique d'un jeu controversé, du XVIIIe siècle à aujourd’hui
  * Supervisor: [Lisa Rougetet](https://nouveau.univ-brest.fr/fr/membre/lisa-rougetet), historian of science

* **Chess coach – [L’échiquier angevin](https://www.echiquierangevin.com/), 2019–2020**
  * Weekly chess lessons for young players from Angers. Preparation and support during youth championships.

* **Professional poker player – 2017–2020**
  * Online poker player specializing in Expressos/Spin & Go, up to €250 buy-ins.
  * Played on Winamax, PokerStars, Unibet, PartyPoker, and PMU.

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Publications
======
<ul>
  {% for post in site.publications reversed %}
    {% unless post.category == "theses" %}
      {% include archive-single-cv.html %}
    {% endunless %}
  {% endfor %}
</ul>

Bachelor thesis
======
<ul>
  {% for post in site.publications reversed %}
    {% if post.category == "theses" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}
</ul>

<!---
Hidden:

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams

-->
