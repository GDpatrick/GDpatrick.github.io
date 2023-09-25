---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hi, I am a PIMS-CNRS Postdoctoral Fellow under the supervision of [Prof. Anthony Wachs](https://personal.math.ubc.ca/~wachs/) at the University of British Columbia in Vancouver, Canada. My research is deeply rooted in applied mathematics and High-Performance Computing, using highly-resolved numerical methods for numerical investigation of multi-phase flows. The scope of my research is diverse, encompassing various domains such as the deformation of blood cells, the dynamics of solid angular particles in inertial flow, and droplet interactions with compressible flow, such as shock waves.  

&nbsp;

Biological flows
======
I’m currently working on the development of a Front-Tracking solver for elastic membranes surrounded by viscous fluids, an example being Red Blood Cells immersed in blood plasma. We describe the deformable capsules using an unstructured lagrangian mesh and compute the internal strains and stresses of the membrane. These stresses are transferred to the fluid with the Immersed Boundary Method (IBM), i.e. by means of a regularized Dirac function. We implement our code on the open-source multiphase flow solver [Basilisk](http://basilisk.fr/Front%20Page).  

The movie below depicts the dynamics of 200 elastic capsules in a simple shear flow.
<p align="center">
<iframe width="1200" height="500" src="https://www.youtube-nocookie.com/embed/rnASehfsVc4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>


&nbsp;

Particle-laden flows
======

My second research project pertains to the development, improvement and use of high-fidelity Finite Volume fictitious domain methods (DLM/FD) on [adaptive octree grid](http://basilisk.fr/sandbox/Antoonvh/The_Tree-Grid_Structure_in_Basilisk) to solve the Navier-Stokes equation with additional (Dirichlet) boundary conditions on embedded interfaces. I apply this
numerical method to flows laden with stationary or freely moving rigid particles. Parallel computations run on the supercomputers [Cedar](https://docs.alliancecan.ca/wiki/Cedar) and [Sockeye](https://arc.ubc.ca/ubc-arc-sockeye) on up to 1024 cores. We have unearthed remarkable insights into the interactions between angular particles and fluids, shedding light on novel physical phenomena.


Freely settling of a tetrahedron
------

Below is a depiction showcasing the wake structures of a freely settling tetrahedron, illustrated across varying Galileo numbers.
<div id="wrapper">
    <video id="home1" width="188" height="300" poster="images/Helix0.pdf" controls="controls">
        <source type="video/mp4" src="images/Helix0.mp4" />
    </video>
    <video id="home2" width="188" height="300" poster="images/Helix1.pdf" controls="controls">
        <source type="video/mp4" src="images/Helix1.mp4" />
    </video>
    <video id="home3" width="188" height="300" poster="images/Helix2.pdf" controls="controls">
        <source type="video/mp4" src="images/Helix2.mp4" />
    </video>
    <video id="home4" width="188" height="300" poster="images/Helix3.pdf" controls="controls">
        <source type="video/mp4" src="images/Helix3.mp4" />
    </video>
    <div class="clear"></div>
</div>


Inertial flow past a fixed particle
------

The video below presents the progression of vortex shedding structures as the Reynolds number increases, illustrating the dynamics of an inertial flow past an angular particle.
<p align="center">
<iframe width="1200" height="500" src="https://www.youtube-nocookie.com/embed/Q-iT4FfQdx4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

&nbsp;

Droplets interaction with shock waves
======

I started my passion for research during my graduate studies in the French Atomic Energy and Alternative Energies Commission ([CEA Saclay, France](https://www.cea.fr/paris-saclay/Pages/Accueil.aspx)). My [Ph.D. project](https://www.theses.fr/2020NORMIR14) under the supervision of [Prof. Abdellah Hadjadj](https://scholar.google.fr/citations?user=UZMCw3QAAAAJ&hl=fr) was dedicated to the development of mathematical models to investigate the effects of water spray systems on premixed hydrogen-air combustion in large-scale industrial applications, such as accidental explosions in nuclear power plants or offshore platforms. These developed numerical models are implemented in the large-scale numerical simulation codes at CEA, one of the world’s most advanced nuclear engineering research centers.


This figure elucidates the mechanism of a 1D shock wave impinging on a domain laden with water spray droplets, consequently generating both reflected and transmitted shock waves.
![Editing a markdown file for a talk](/images/JFMsketch.png)
