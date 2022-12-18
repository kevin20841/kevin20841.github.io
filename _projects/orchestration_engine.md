---
layout: page
title: the Orchestration Engine
description: a computer-aided orchestration tool.
img: assets/img/spectra_clb_quart.png
importance: 3
category: work
---

The Orchestration Engine is tool for computer-aided orchestration. It takes as input an arbitrary reference sound, and outputs an orchestration that best approximates the tambre of the input subject to instrumentation constraints. I have utilized this tool to write my own [pieces](/music/).


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/orchestration_example.PNG" title="Orchestration Example" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An excerpt from my piece <i> Looking out the airplane window</i>. To obtain this orchestration, I fed the sound of a plane rumbling into the tool, and then combined the resulting output with another consonant orchestration that I wrote.
</div>


### Motivation
Historically, composers have used “recipes” for orchestration. These “recipes” can be thought of as general rules of thumb for what combinations of instruments blend, or clash. For example, the bassoon blends well with the cello when doubled, and the oboe blends well with brass instruments at unison or in octaves. However, because these “recipes” were developed for tonal music, they do not integrate well with modern musical aesthetics. As a result, composers have searched for a more systematic way to approach orchestration. 

Because orchestration is fundamentally about how different sounds interact when played at the same time, it can be viewed as through the lens of electronic processing of music. Computer aided orchestration and electronic ideas in composition have influenced acoustic composition since the development of electronic music. In fact, one of the first landmark pieces in the spectral style, Grisey’s Partiels, was written by orchestrating a sonogram analysis of the sound of a trombone playing a low E2. Other pieces do not directly utilize sonogram analysis but instead utilize analogues of common electronic music synthesis techniques. For example, Tristan Murail’s Gondwana utilizes an analogue of FM synthesis to generate rich and interesting timbres. Utilizing analysis of sound properties to write music is an interest for many in the compositional community, because it provides a musical language that is more systematic and sophisticated than that provided by general intuition and can complement philosophical and aesthetic decisions made by the composer.

### Current Status of the Project
The project was implemented in python3 and node.js. Currently, all algorithmic functionality is completed and the GUI design of the application is also completed. What remains to be done is to link the backend and frontend together. Expect a preliminary release of the program sometime next year!


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/orchestration_engine_screenshot.PNG" title="Orchestration Engine GUI" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The GUI of the Orchestration Engine, developed in collaboration with Juan-Pablo Lopez.
</div>
