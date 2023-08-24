---
layout: page
permalink: /simuvox/
title: SimuVox
comment: Computer simulation of disordered voices
nav: true
order: 4
---


This project focuses on the clinical assessment of voice disorders. Abnormal voices with irregular pitch, loudness, or timbre often stem from laryngeal pathologies or physiological dysfunctions. To address this, I developed SimuVox, a physics-based speech synthesizer capable of simulating normal and disordered voice timbres.

SimuVox models the vocal fold vibration, glottal aerodynamics, and acoustic wave propagation in the vocal tract. This allows direct control of the simulated sound through physiological parameters. The vocal fold model can introduce asymmetric left/right tissue properties. The simulator also incorporates models of the trachea, bronchi, nasal tract, paranasal sinuses, muscle jitter, neurological/physiological tremor, and aspiration noise. An articulatory model shapes the vocal tract using configurable parameters for the jaw, tongue, lips, and larynx.    

<p><i class="fa fa-download"></i> <a href="https://www.mediafire.com/file/87ndqzkz2tz8ws3/SimuVox.zip/file"><b>Download</b></a>, version 0.1.1, July 2017.</p> 

<p class="mb-0"><i class="fa fa-volume-up"></i> Audio:</p>
<ul>
<li><a href="/disorder/">Voice disorders</a></li>
<li><a href="/french/">French vowels</a></li>
</ul>

<div class="row mt-3 mx-auto" style="max-width:750px">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/simuvox.png" class="img-fluid img-bg rounded" %}
    </div>
</div>
<div class="caption">
     User interface of SimuVox. 
</div>



Potential applications of SimuVox include:

- Investigating signal properties and laryngeal conditions causing abnormal voice quality
- Providing controllable synthetic stimuli for perceptual assessments
- Computational training tool for clinicians
- Assisting clinical diagnosis and treatment

<p>The main mathematical models are described in:  Lucero, Schoentgen & M Behlau, "Physics-based synthesis of disordered voices", <i>Interspeech 2013 </i> (Lyon, France, 2013) 
[<a href="/assets/pdf/10.1.1.727.1140.pdf">PDF</a>].</p> 


### Support

This project was supported by a CNPq-FRS/FNRS Brazil-Belgium cooperation program with Jean Schoentgen at Université Libre de Bruxelles (2012-2014), and a CNPq grant (2015-2018) in collaboration with Mara Behlau's team at the Center of Voice Studies of São Paulo.

SimuVox research has won awards from the Brazilian Society of Speech-Language Pathology and Audiology (2013, 2015, 2016, 2020) and the Brazilian Chapter of The Voice Foundation (2017, 2021).



