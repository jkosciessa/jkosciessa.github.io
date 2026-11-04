---
title: "Home"
layout: homelay
description: "Julian Q. Kosciessa, cognitive computational neuroscientist at the Donders Institute, Radboud University: thalamic control of flexible perception and cognition, EEG, fMRI and transcranial ultrasound stimulation."
sitemap: false
permalink: /
---

<div class="hero">
<div class="hero-logo">
<img src="{{ site.url }}{{ site.baseurl }}/images/logo_lab.svg" alt="Cognitive Neurodynamics logo: layered neural signals beside a head with a brain network">
</div>
<div class="hero-text" markdown="1">

I study how brain dynamics keep perception and cognition adaptive in uncertain and changing environments. My research tests how thalamic circuits adjust the precision of cortical processing, combining experimental tasks and behavioral modeling with multimodal neuroimaging (EEG, fMRI) and image-guided transcranial ultrasound stimulation (TUS).

<a class="btn btn-default btn-sm btn-cv" href="{{ site.url }}{{ site.baseurl }}/downloads/cv_kosciessa.pdf"><i class="fa-solid fa-file-pdf" aria-hidden="true"></i>Download CV (PDF)</a>
<a class="btn btn-default btn-sm btn-cv" href="https://www.ru.nl/en/departments/donders-centre-for-cognition/cognitive-neurodynamics"><i class="fa-solid fa-flask" aria-hidden="true"></i>Lab website</a>

</div>
</div>

<h2>About</h2>

I am a cognitive computational neuroscientist and Research Fellow at the [Donders Institute for Brain, Cognition and Behaviour](https://www.ru.nl/donders/) at Radboud University in Nijmegen, the Netherlands. I lead the [Cognitive Neurodynamics](https://www.ru.nl/en/departments/donders-centre-for-cognition/cognitive-neurodynamics) group at the Donders Centre for Cognition, with close associations to the [Cognitive Neuromodulation](https://www.verhagenlab.com/) group.

Before moving to Nijmegen, I completed my PhD in the [IMPRS COMP2PSYCH](https://www.mps-ucl-centre.mpg.de/comp2psych) program of the [Max Planck UCL Centre for Computational Psychiatry and Ageing Research](https://www.mps-ucl-centre.mpg.de/en) and worked as a postdoc in the [Lifespan Neural Dynamics Group](https://www.mps-ucl-centre.mpg.de/en/about-the-centre/research-groups/lifespan-neural-dynamics-group) at the [Max Planck Institute for Human Development](https://www.mpib-berlin.mpg.de/en) in Berlin. I earned an M.Sc. in the [Berlin School of Mind and Brain](http://www.mind-and-brain.de/home/) at Humboldt-Universität zu Berlin and a B.Sc. in Psychology at [Freie Universität Berlin](https://www.fu-berlin.de/en/).

<h2>Research Interests</h2>

<details class="ri" markdown="1">
<summary markdown="span">General</summary>

Brains are not static input-output machines, but dynamic systems that adapt perception, cognition, and action to changing demands. My research bridges cognitive, computational, and systems neuroscience to uncover the neural mechanisms underlying this flexibility.

To interpret and respond to the world, the brain generates a rich repertoire of dynamics, from synchronous network oscillations to stochastic "noise". While neural oscillations are well-established markers of brain function with recognized computational roles, the origins and functional significance of other neural dynamics remain less understood. I investigate how to measure, functionally characterize, and modulate neural dynamics as substrates of cognitive and brain function. A central goal is to specify and influence brain states, thereby tuning neurocognitive computations across the human lifespan.

These computational principles span cognitive domains, including working memory ([Garrett et al., 2022]({{ site.url }}{{ site.baseurl }}/publications/#garrett-2022); [Kosciessa, Grandy, et al., 2020]({{ site.url }}{{ site.baseurl }}/publications/#kosciessa-grandy-2020)), perception and attention ([Kosciessa et al., 2021]({{ site.url }}{{ site.baseurl }}/publications/#kosciessa-2021)), decision-making ([Kloosterman et al., 2020]({{ site.url }}{{ site.baseurl }}/publications/#kloosterman-2020); [Kosciessa et al., 2024]({{ site.url }}{{ site.baseurl }}/publications/#kosciessa-2024)), and episodic memory ([Hämmerer et al., 2018]({{ site.url }}{{ site.baseurl }}/publications/#hammerer-2018)). I study how brain function and cognition change across the adult lifespan, with a focus on individual differences. My methods include computational modeling of behavior, electroencephalography (EEG), structural and functional magnetic resonance imaging (s/fMRI), pupillometry, transcranial ultrasound stimulation (TUS), and numerical simulations.

</details>

<details class="ri" markdown="1">
<summary markdown="span">Flexible perceptual and cognitive control under uncertainty</summary>

In our uncertain world, brains must adapt to varying degrees of unpredictability, including uncertainty about what should receive priority in processing. Combining EEG and fMRI during a multi-attribute uncertainty task, my work identified neural "noise" as a characteristic of flexible decisions and proposed cortical excitability adjustments as a candidate mechanism ([Kosciessa et al., 2021]({{ site.url }}{{ site.baseurl }}/publications/#kosciessa-2021)). These results advance computational "noise" as an underappreciated characteristic of adaptive biological (and plausibly artificial) agents. Neural variability also compresses as beliefs become more precise during Bayesian inference ([Skowron et al., 2025]({{ site.url }}{{ site.baseurl }}/publications/#skowron-2025)). In older adults, the neural response to uncertainty is dampened, and its maintenance is associated with higher cognitive flexibility ([Kosciessa et al., 2024]({{ site.url }}{{ site.baseurl }}/publications/#kosciessa-2024)), indicating the promise of this circuit model for computational psychiatry and aging research.

</details>

<details class="ri" markdown="1">
<summary markdown="span">Neural rhythms and "noise"</summary>

Oscillations are a key signature of neural information coordination, but they are not constantly present and coexist with irregular components traditionally dismissed as background noise. To re-characterize signal and noise in brain function, I develop analysis tools that detect rhythmic episodes in single trials ([eBOSC]({{ site.url }}{{ site.baseurl }}/tools); [Kosciessa, Grandy, et al., 2020]({{ site.url }}{{ site.baseurl }}/publications/#kosciessa-grandy-2020)) and characterize signal irregularity at matched temporal scales ([mMSE]({{ site.url }}{{ site.baseurl }}/tools); [Kosciessa, Kloosterman, et al., 2020]({{ site.url }}{{ site.baseurl }}/publications/#kosciessa-kloosterman-2020)). Applications range from rhythm contributions to working memory ([Kosciessa, Grandy, et al., 2020]({{ site.url }}{{ site.baseurl }}/publications/#kosciessa-grandy-2020)) to brain signal variability that tracks liberal shifts in decision bias ([Kloosterman et al., 2020]({{ site.url }}{{ site.baseurl }}/publications/#kloosterman-2020)).

<i class="fa-brands fa-youtube" aria-hidden="true"></i> Keynote: [Signs, signals, and noise in human brain dynamics](https://www.youtube.com/watch?v=7sWdT7zttso) (CuttingEEG 2023)
{: .ri-media}

</details>

<details class="ri" markdown="1">
<summary markdown="span">Thalamic influences on cortical dynamics and cognition</summary>

The deep brain thalamus is ideally suited to dynamically regulate specific computations in cortex, but it has long been difficult to study in humans. Computational and non-human animal models indicate that different thalamic subdivisions support flexible perception and cognition via shared principles: by regulating the excitability and computational fidelity of their cortical counterparts. Combining the high temporal resolution of EEG with the high spatial resolution of fMRI, my work linked thalamic engagement to dynamic cortical states during perceptual decisions under uncertainty (Kosciessa et al., [2021]({{ site.url }}{{ site.baseurl }}/publications/#kosciessa-2021), [2024]({{ site.url }}{{ site.baseurl }}/publications/#kosciessa-2024)). This work bridges cognitive, computational, and systems neuroscience, and has inspired cross-species collaboration to resolve these circuit mechanisms in detail.

</details>

<details class="ri" markdown="1">
<summary markdown="span">Transcranial ultrasound stimulation (TUS)</summary>

Maladaptive brain dynamics are central to many mental disorders, which calls for approaches that can reshape them. The thalamus orchestrates widespread brain dynamics, but its small size, differentiated structure, and deep location have long limited its investigation, and targeted interventions, in humans. A Radboud Excellence Fellowship (2022–2024) enabled me to extend my research to TUS, a non-invasive brain stimulation technique that can reach deep brain structures with high spatial specificity. I use image-guided TUS, including concurrent fMRI to assess target engagement, to test how thalamic circuits contribute to flexible perception and cognition, and to help define best practices for this approach. To support rigorous TUS research, I develop the open-source simulation toolbox [PRESTUS]({{ site.url }}{{ site.baseurl }}/tools) for planning TUS studies, and teach acoustic simulation in the NeuroTechEU course [TUS: Foundations](https://nteucampus.org/course/transcranial-ultrasonic-stimulation-tus-foundations).

<i class="fa-solid fa-chalkboard-user" aria-hidden="true"></i> Lecture: [Personalised and precision stimulation with TUS](https://nteucampus.org/lesson/personalised-and-precision-stimulation-tus) (NeuroTechEU)
{: .ri-media}

</details>

<details class="ri" markdown="1">
<summary markdown="span">Open and reproducible neuroscience</summary>

Beyond my theoretical interests, I aim to improve the reproducibility and data management of complex neuroscientific projects. For example, preprocessing and analysis choices for high-dimensional EEG data vary between analysts, which questions the robustness of outcomes. I contributed a reproducible workflow that links version-controlled code and data to the EEGManyPipelines project, which assesses the impact of such variability across the community ([Cesnaite et al., 2026]({{ site.url }}{{ site.baseurl }}/publications/#cesnaite-2026)). Across projects, I follow FAIR principles (Findable, Accessible, Interoperable, Reusable) and treat code, data, and materials as primary scientific outputs. I develop and maintain open-source [tools]({{ site.url }}{{ site.baseurl }}/tools), and teach research data management, including as a [ReproNim/INCF fellow](https://repronim.org/fellowship/).

<i class="fa-brands fa-youtube" aria-hidden="true"></i> Talk: [Neuroscientific data management using DataLad](https://www.youtube.com/watch?v=aFfrx9LHjzE) (distribits 2024)
{: .ri-media}

</details>

{::nomarkdown}
<details class="ri section-toggle rm-toggle">
<summary>Research locations</summary>
{% include research_map.html %}
</details>
{:/}

<details class="ri section-toggle" markdown="1">
<summary markdown="span">Awards and fellowships</summary>

- 2026 · [Donders Open Research Output Award](https://www.ru.nl/en/donders-institute/news/donders-day-2026-science-community-and-recognition) (inaugural)
- 2025 · Gold Poster Award, Focused Ultrasound Neuromodulation Conference (FUN25)
- 2022 · [Otto Hahn Medal](https://www.mpib-berlin.mpg.de/award/julian-kosciessa-was-awarded-the-otto-hahn-medal-2022) of the Max Planck Society
- 2022 · [Radboud Excellence Initiative Fellowship](https://www.ru.nl/en/staff/researchers/support-and-development/radboud-excellence-initiative)
- 2022 · [ReproNim/INCF Fellowship](https://repronim.org/fellowship/)
- 2021 · [DGPA Brain Products Young Scientist Award](https://pressrelease.brainproducts.com/dgpa21/)
- 2021 · Merit Abstract Award, OHBM Annual Meeting
- 2018 · IBRO Poster Award, Interpreting BOLD
- 2016–2020 · [IMPRS COMP2PSYCH](https://www.mps-ucl-centre.mpg.de/comp2psych) Fellowship

</details>

<br />
