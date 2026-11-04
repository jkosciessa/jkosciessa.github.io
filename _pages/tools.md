---
title: "Tools"
layout: textlay
description: "Open-source tools by Julian Q. Kosciessa: eBOSC, PRESTUS, mMSE, MAAT and CARL."
sitemap: false
permalink: /tools
---

<h2>Open tools and materials</h2>

Open-source software and experimental materials from my projects, shared so that others can reproduce and build on this work.

<div class="tool-card">
<div class="tool-thumb">
<img src="https://github.com/jkosciessa/PRESTUS_bin/raw/main/img/logo_PRESTUS.png" alt="PRESTUS logo">
</div>
<div class="tool-body" markdown="1">

### PREprocessing & Simulations for Transcranial Ultrasound Stimulation (PRESTUS)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15095860.svg)](https://doi.org/10.5281/zenodo.15095860)
{: .badges}

**Kosciessa, J. Q.**, Chetverikov, A., Cornelissen, M., Carpino, E., van der Zee, K., Wimmers, M., Adelhoefer, N., Meijer, S., & Verhagen, L. (2026). PRESTUS (Version v0.6.0) [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.20392907

<i class="fa-solid fa-award" aria-hidden="true"></i> This software was honored with the inaugural [Donders Open Research Output Award](https://www.ru.nl/en/donders-institute/news/donders-day-2026-science-community-and-recognition) (2026) for maintaining open research software for TUS.
{: .tool-award}

PRESTUS is an open-source MATLAB toolbox that aims to streamline imaging-informed simulations of Transcranial Ultrasound Stimulation (TUS): from the segmentation of T1-weighted MRI head scans and mapping of medium tissue properties (possibly informed for skull via (pseudo-)CT images) in a simulation grid, to the execution of acoustic and thermal simulations using the widely adopted k-Wave engine. High-performance computing (HPC) support via SLURM enables efficient parallelization and large-scale analyses. Output 3D NIfTI images are automatically mapped to a standard template (MNI) space to facilitate group reporting.

[Code](https://github.com/Donders-Institute/PRESTUS)
[Poster]({{ site.url }}{{ site.baseurl }}/downloads/2025-FUN25-PRESTUS.pdf)
[Lecture: personalized simulations](https://nteucampus.org/lesson/personalised-and-precision-stimulation-tus)
[Course: TUS Foundations (NeuroTechEU)](https://nteucampus.org/course/transcranial-ultrasonic-stimulation-tus-foundations)
{: .pub-links}

</div>
</div>

<div class="tool-card">
<div class="tool-thumb">
<img src="{{ site.url }}{{ site.baseurl }}/images/rhythm.png" alt="Detected rhythmic episode (red) within a neural time series">
</div>
<div class="tool-body" markdown="1">

### extended Better OSCillation Detection (eBOSC)

[![DOI](https://zenodo.org/badge/138600886.svg)](https://zenodo.org/badge/latestdoi/138600886) [![DOI](https://zenodo.org/badge/342610969.svg)](https://zenodo.org/badge/latestdoi/342610969)
{: .badges}

**Kosciessa, J. Q.**, Grandy, T. H., Garrett, D. D., & Werkle-Bergner, M. (2020). Single-trial characterization of neural rhythms: Potential and challenges. NeuroImage, 206, 116331. doi:10.1016/j.neuroimage.2019.116331

eBOSC is a toolbox that detects the occurrence of rhythms in continuous signals (i.e., at the single trial level). It uses a static aperiodic ‘background’ spectrum as the basis to define a ‘power threshold’ that continuous signals have to exceed in order to qualify as ‘rhythmic’, and an optional ‘duration threshold’. The main goal of the code is to produce a list of rhythmic episodes, i.e., when and for how long rhythms occur.

[Code (MATLAB)](https://github.com/jkosciessa/eBOSC)
[Wiki](https://github.com/jkosciessa/eBOSC/wiki)
[Code (Python)](https://github.com/jkosciessa/eBOSC_py)
[PyPI](https://pypi.org/project/ebosc/)
{: .pub-links}

</div>
</div>

<div class="tool-card">
<div class="tool-thumb">
<img src="{{ site.url }}{{ site.baseurl }}/images/mse.png" alt="Multiscale entropy pattern matching illustration">
</div>
<div class="tool-body" markdown="1">

### modified MultiScale Entropy (mMSE)

[![DOI](https://zenodo.org/badge/204967802.svg)](https://zenodo.org/badge/latestdoi/204967802)
{: .badges}

**Kosciessa, J. Q.**, Kloosterman, N. A., & Garrett, D. D. (2020). Standard multiscale entropy reflects neural dynamics at mismatched temporal scales: What's signal irregularity got to do with it? PLoS Computational Biology, 16(5), e1007885. doi:10.1371/journal.pcbi.1007885

[Code](https://github.com/LNDG/mMSE)
[Tutorial (FieldTrip)](https://www.fieldtriptoolbox.org/example/entropy_analysis)
{: .pub-links}

</div>
</div>

<div class="tool-card">
<div class="tool-thumb">
<img src="{{ site.url }}{{ site.baseurl }}/images/MAAT.gif" alt="Multi-attribute attention task trial animation">
</div>
<div class="tool-body" markdown="1">

### Multi-attribute attention task (MAAT)

**Kosciessa, J. Q.**, Lindenberger, U., & Garrett, D. D. (2021). Thalamocortical excitability modulation guides human perception under uncertainty. Nature Communications, 12(1), 2430. doi:10.1038/s41467-021-22511-7

Multi-attribute task used in Kosciessa, J. Q., Lindenberger, U., & Garrett, D. D. (2021).

[Code](https://git.mpib-berlin.mpg.de/LNDG/multi-attribute-task)
{: .pub-links}

</div>
</div>

<div class="tool-card">
<div class="tool-thumb">
<img src="https://github.com/jkosciessa/carl/raw/main/util/logo.png" alt="CARL logo">
</div>
<div class="tool-body" markdown="1">

### Computer-Assisted Response Labeler (CARL)

[![DOI](https://zenodo.org/badge/444434425.svg)](https://zenodo.org/badge/latestdoi/444434425)
{: .badges}

Voice is a naturalistic response mode in psychological experiments, but labeling thousands of word responses, sometimes from continuous recordings, requires time and patience. CARL has been designed to make the manual labeling process smoother and more time-efficient, as well as to provide measures of voice on- and offset times, e.g., by automatically pre-labeling word on- and offsets based on sound energy and allowing quick manual refinement via drag and drop.

[Code](https://github.com/jkosciessa/carl)
{: .pub-links}

</div>
</div>
