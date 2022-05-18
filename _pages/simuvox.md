---
layout: page
permalink: /simuvox/
title: SimuVox
comment: Computer simulation of disordered voices
nav: true
---


The context of this project is the clinical assessment of voice.
A disordered voice is a voice that is perceived as abnormal with regard to pitch, loudness or timbre, and is often the consequence of a laryngeal pathology or physiological dysfunction. Here, we develop a simulator/synthesizer of speech sounds (SimuVox) which is capable of simulating a wide range of timbres of normal and disordered voices. We follow a physics-based approach by using models of the vocal fold vibration, glottal aerodynamics and acoustic wave propagation in the vocal tract, which allows for the control of the generated sound in direct terms of physiological parameters.  The vocal fold model can simulate right/left tissue asymmetries, and the simulator also includes models of the trachea and bronchi, nasal tract and paranasal sinuses, muscle jitter, neurological and physiological tremor, and aspiration noise. Further, it has an articulatory model for the vocal tract which controls its shape by configuration parameters of the jaw, tongue, lips and larynx.    

<p><a href="https://www.mediafire.com/file/87ndqzkz2tz8ws3/SimuVox.zip/file"><i class="fa fa-download"></i> <b>Download</b></a>, version 0.1.1, July 2017.</p> 

<p class="mb-0"><i class="fa fa-volume-up"></i> Audio:</p>
<ul>
<li><a href="/disorder/">Voice disorders</a></li>
<li><a href="/french/">French vowels</a></li>
</ul>

<div class="row mt-3 mx-auto" style="max-width:750px">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="/assets/img/simuvox.png" class="img-fluid" %}
    </div>
</div>
<div class="caption">
     User interface of SimuVox. 
</div>



<p>SimuVox may be used for the investigation of
the signal properties and laryngeal conditions that cause a particular
abnormal vocal quality, for providing controllable synthetic
stimuli in perceptual assessment, and as a computational
tool for training of clinicians, clinical diagnosis and treatment.</p>

<p>Its main mathematical models have been outlined in: Lucero, Schoentgen & M Behlau, "Physics-based synthesis of disordered voices", <i>Interspeech 2013 </i> (Lyon, France, 2013) 
[<a href="/assets/pdf/10.1.1.727.1140.pdf">PDF</a>].</p> 


### Support

<p>This project was supporte by a CNPq-FRS/FNRS (Brazil - Belgium) cooperation program with Jean Schoentgen at Université Libre de Bruxelles (2012 – 2014), and by a CNPq grant (2015 - 2018) with the collaboration of Mara Behlau and her team at the Center of Voice Studies of São Paulo. Conference presentations using results from SimuVox won prizes of the Brazilian Society of Speech-Language Pathology and Audiology (2013, 2015, 2016, 2020) and the Brazilian Chapter of The Voice Foundation (2017, 2021).</p>



