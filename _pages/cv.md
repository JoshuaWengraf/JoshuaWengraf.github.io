---
layout: archive
title: "CV"
permalink: /CV/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* MPhys in Physics, The University of Manchester University, 2013 - 2017
* MSc in Physics (by research),  Lancaster University, 2017-2020

Research experience
======

* MPhys Project: A Correlated Percolation Model for the Spread of Ash Dieback

For my final year masters project, in collaboration with Daniel Pettitt and supervised by Dr. Ingo Dierking, I developed a simulation to model the spread of ash dieback in the UK. This was fit to data provided by the forestry commission. The simulation was executed on a square grid, with infected squares infecting neighboring squares with probability p and killing them with probability 1-p; these represent infection and immunisation respectfully. We also introduced a probability for an infected square to infect any other random square on the grid. We fit values of p to the model to determine whether the epidemic was dominated by short range or long-range infections. 

MSc (by research) Project: Magnetophonon Oscillations in Graphene with a Large Applied DC Bias Voltage

Magnetophonon resonance (MPR) oscillations are a valuable spectroscopic tool for studying electron interactions in solids. This type of spectroscopy is performed by applying a magnetic field to the solid, to quantise the energy of the charge carriers, and inter-Landau level scattering transitions are observed as oscillations in magnetoresistance. Since the transition energy is known, these oscillations can be used to identify phonons responsible for the inter-Landau level scattering. These oscillations, which arise due to scattering of Dirac fermions by transverse and longitudinal acoustic phonons, appear only in large graphene Hall bars with dimensions in excess of 10 um (greater than the phonon scattering mean free path). Here we apply large current-induced bias voltages (up to 1 mA) through a large graphene Hall bar and study the effect on the MPR oscillations. We observe a splitting of these oscillations due to a spatial tilting of the Landau levels induced by a strong Hall electric field. At sufficiently large Hall fields we also observe 'phonon-less' inter-Landau level scattering transitions which arise when the Landau level states become parallel in energy. Finally, we observe an additional scattering process when the drift velocity approaches the speed of the transverse acoustic phonon.



Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
