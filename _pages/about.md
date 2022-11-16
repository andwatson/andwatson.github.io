---
permalink: /
title: "Andrew Watson"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a final year postgraduate researcher in the Institute of Geophysics and Tectonics, School of Earth and Environment, University of Leeds. My research focuses on the use of InSAR, largely through the COMET-LiCS project (https://comet.nerc.ac.uk/COMET-LiCS-portal/), to measure surface deformation throughout Iran, both to understand the large-scale tectonics and the local seismic hazard.

I started out focusing on the Main Recent Fault, an 800 km long strike-slip fault in the Zagros Mountains, western Iran. We published the first InSAR-derived slip rate for the fault, and the first geodetically-determined estimate of the locking depth, both of which are key to assesments of the seismic potential of this major fault. We used fives `frames' from LiCS, covering an area of 400 x 200 km, to derive average surface velocities, which we in turn used to constrain a model for the fault through a bayesian inversion.

We have now expended our InSAR processing to cover all of Iran, using over 80,000 interferograms to map surface velocities across an area of 2.3 million km^2. The figure below shows decomposed East and Vertical velocities for Iran at a 1 km resolution. We aim to publish these results in 2023.

<img src="https://github.com/andwatson/andwatson.github.io/blob/master/images/decomp_east_up.png?raw=true" style="display: block; margin: auto;" />

I am an active member of COMET (https://comet.nerc.ac.uk/), a UK-wide research group, along with the Tectonics and Geodesy groups within the School of Earth and Environment. Before Leeds, I completed an undergraduate degree and a Masters degree at Durham University, the latter exploring multi-objective optimisation for the automated designing of low-cost GNSS networks.

On my github page, you'll find two main projects:
- A collection of jupyter notebook-based practicals covering [interseismic](https://github.com/andwatson/interseismic_practical), [coseismic](https://github.com/andwatson/coseismic_practical), and [volcanic](https://github.com/andwatson/volcano_practical) deformation signals in InSAR. These were written from the COMET InSAR workshops (2021, 2022), can be run from any web browser using [binder](https://mybinder.org/), are fully self-contained, and are published under the GNU General Public License v3.0.
- [decompose_insar_velocities](https://github.com/andwatson/decompose_insar_velocities) - a collection of Matlab scripts for decomposing line-of-sight InSAR velocities into East and Vertical components. These codes can utilise any number of overlapping InSAR velocity fields (easily produced by [LiCSBAS](https://github.com/yumorishita/LiCSBAS)), peform a range of intermediary steps such as grid unification and referencing to GNSS velocities, and then perform the decomposition using several methods and with error propagation. This package is under activate development (happy for feedback!) and is also published under the GNU General Public License v3.0.

Outside of work I'm normally doing some combination of badminton, reading, D&D, or trying to break a gravel bike.
