---
layout: page
title: project 1
description: 
img: assets/img/almeida_teaser.jpg
importance: 1
category: work
---

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal it's glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/almeida1681_1.png" title="" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/p1.jpg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The first translation of the New Testament into Portuguese was done in the 17th century by the Portuguese pastor Jõao Ferreira Annes d’Almeida (1628 –1691) in the Dutch East Indies (now Indonesia). Almeida completed its translation in 1676, and it was published in Amsterdam five years later. The translation had several errors, which led to the destruction of most copies by order of the Dutch authorities. Some of the surviving copies were used with handwritten corrections and/or augmented by an errata in the form of a warning to the reader, written by Almeida in 1683. A second revised edition was published in 1693, after Almeida’s death, followed by others in 1712 and 1773.
The present reconstruction is based on an original copy of the first 1681 version from the National Library of Portugal in Lisbon.

Almeida also partially translated the Old Testament until his death in 1691, and the translation was completed by the Dutch pastor Jacobus op den Akker in 1694. The Old Testament was published in two volumes, in 1748 and 1753, respectively. The set of both the New and Old Testament translations was published in one volume in 1812 by the British and Foreign Bible Society. Since then, the so-called Almeida Bible has been revised and republished several times and currently is the most popular among Portuguese-speaking Protestant churches. It may be regarded as equivalent in importance to King James’ Bible for the English language and Reina-Valera’s Bible for the Spanish language.