---
title: "Kosciessa - Tools"
layout: textlay
excerpt: "Tools"
sitemap: false
permalink: /tools
---

<h2>Open tools and materials</h2>

Projects I have worked on produced multiple tools that I hope are useful for scientific purposes with no guarantees that tools are or will remain working as intended.

<br />

### extended Better OSCillation Detection (eBOSC)

**Kosciessa, J. Q.**, Grandy, T. H., Garrett, D. D., & Werkle-Bergner, M. (2020). Single-trial characterization of neural rhythms: Potential and challenges. NeuroImage, 206, 116331. doi:10.1016/j.neuroimage.2019.116331

<img class="img-responsive" src="{{ site.url }}{{ site.baseurl }}/images/rhythm.jpeg" style="width: 100%">

Rhythmic patterns in neural time series provide a window on the neural dynamics that shape perception, cognition and action, and therefore are a major signal of interest in the cognitive, computational and systems neurosciences. However, typical descriptions of rhythmicity lack detail, e.g., failing to indicate when and for how long rhythms occur. Such lack of detail becomes problematic in the face of non-stationarities in rhythmic engagement, i.e., when the presence of rhythms varies over time. To overcome resulting pitfalls, there is a need for methods that identify the occurence of non-stationary rhythmic periods in a systematic manner.

eBOSC (extended Better OSCillation detection) is a toolbox (or a set of scripts) that can be used to detect the occurrence of rhythms in continuous signals (i.e., at the single trial level). It uses a static aperiodic ‘background’ spectrum as the basis to define a ‘power threshold’ that continuous signals have to exceed in order to qualify as ‘rhythmic’. As such, it leverages the observation that stochastic components of the frequency spectrum of neural data are characterized by a '1/f'-like power spectrum. An additional ‘duration threshold’ can be set up in advance, or rhythmic episodes can be filtered by duration following detection to ensure that detected rhythmic episodes have a rather sustained vs. transient appearance. The main goal of the code is to produce a list of rhythmic episodes.

The code is provided [here](https://github.com/jkosciessa/eBOSC).
A wiki is provided [here](https://github.com/jkosciessa/eBOSC/wiki).

<br />

### modified MultiScale Entropy (mMSE)

**Kosciessa, J. Q.**, Kloosterman, N. A., & Garrett, D. D. (2020). Standard multiscale entropy reflects neural dynamics at mismatched temporal scales: What's signal irregularity got to do with it? PLoS Computational Biology, 16(5), e1007885. doi:10.1371/journal.pcbi.1007885

<img class="img-responsive" src="{{ site.url }}{{ site.baseurl }}/images/mse.png" style="width: 100%">

The code is provided [here](https://github.com/LNDG/mMSE).
A short tutorial is provided [here](https://www.fieldtriptoolbox.org/example/entropy_analysis).

<br />

### Multi-attribute attention task (MAAT)

**Kosciessa, J. Q.**, Lindenberger, U. & Garrett, D. D. (2020). Thalamocortical excitability adjustments guide human perception under uncertainty. Manuscript submitted for publication.

<img class="img-responsive" src="{{ site.url }}{{ site.baseurl }}/images/MAAT.gif" style="width: 100%">

Multi-attribute-task used in Kosciessa, J. Q., Lindenberger, U., & Garrett, D. D. (2020). Thalamocortical excitability adjustments guide human perception under uncertainty.

The code is provided [here](https://git.mpib-berlin.mpg.de/LNDG/multi-attribute-task).