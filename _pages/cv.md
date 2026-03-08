---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- taken from https://emiliendupont.github.io/resume/  -->

Updated Nov 2025.

Education 🎓
======

<!-- M.Sc -->
<div style="display:flex;">

  <div style="flex:0.5; padding-right:5%">
    <img src="{{ site.url }}/images/resume/JGU.png" style="align:left; border: 1px solid #d3d3d3; border-style: outset;">
  </div>

  <div style="flex:4;">
    <p style="margin:0px">
      <b style="font-size: 130%;">Johannes Gutenberg-Universität Mainz</b>
      <span style="float:right; font-size:80%; color:#7a7a7a;">2024</span>
    </p>
    M.Sc Physics (Research-Oriented)
    <div style="color:#7a7a7a">
    </div>
  </div>
</div>
<hr style="height:1em; margin:0em; visibility:hidden;" />

<!-- M.Sc -->
<div style="display:flex;">

  <div style="flex:0.5; padding-right:5%">
    <img src="{{ site.url }}/images/resume/KSV.png" style="align:left; border: 1px solid #d3d3d3; border-style: outset;">
  </div>

  <div style="flex:4;">
    <p style="margin:0px">
      <b style="font-size: 130%;">Kadi Sarva Vishwavidyalaya</b>
      <span style="float:right; font-size:80%; color:#7a7a7a;">2017 </span>
    </p>
    M.Sc Physics
    <div style="color:#7a7a7a">
    </div>
  </div>
</div>
<hr style="height:1em; margin:0em; visibility:hidden;" />


<!-- B.Sc -->
<div style="display:flex;">

  <div style="flex:0.5; padding-right:5%">
    <img src="{{ site.url }}/images/resume/GU.png" style="align:left; border: 1px solid #d3d3d3; border-style: outset;">
  </div>

  <div style="flex:4;">
    <p style="margin:0px">
      <b style="font-size: 130%;">Gujarat University</b>
      <span style="float:right; font-size:80%; color:#7a7a7a;">2015 </span>
    </p>
    B.Sc Physics
    <div style="color:#7a7a7a">
    </div>
  </div>
</div>
<hr style="height:1em; margin:0em; visibility:hidden;" />



Projects 💻
======

<!-- PWCP Project -->
<div style="display:flex;">
  <div style="flex:0.5; padding-right:5%">
    <img src="{{ site.url }}images/resume/PWCP.png" style="align:left; border: 1px solid #d3d3d3; border-style: outset;">
  </div>
  <div style="flex:4;">
    <p style="margin:0px">
      <b style="font-size: 130%;">Precision-Weighted Confidence Propagation (PWCP)</b>
      <span style="float:right; font-size:80%; color:#7a7a7a;">2025 – Present</span>
    </p>
    Independent Research Project
    <ul style="margin-top: 5px; padding-left: 1.2em; color:#7a7a7a">
      <li>Designed a neural network architecture that propagates <b>calibrated uncertainty in a single forward pass</b> via Bayesian inverse-variance message passing.</li>
      <li>Inspired by <b>Friston's predictive coding framework</b>; analytically tracks precision-weighted belief updates layer by layer.</li>
      <li>Achieves the <b>lowest Expected Calibration Error</b> across five baselines on MNIST and CIFAR-10 (5 seeds).</li>
      <li>Runs <b>11× faster than MC Dropout</b> at identical computational cost to a standard deterministic network.</li>
      <li><i>Manuscript in preparation.</i></li>
    </ul>
  </div>
</div>
<hr style="height:1em; margin:0em; visibility:hidden;" />

<!-- IceCube Tau Neutrino Project -->
<div style="display:flex;">
  <div style="flex:0.5; padding-right:5%">
    <img src="{{ site.url }}images/resume/IceCube.png" style="align:left; border: 1px solid #d3d3d3; border-style: outset;">
  </div>
  <div style="flex:4;">
    <p style="margin:0px">
      <b style="font-size: 130%;">Tau Neutrino Identification in IceCube | Bayesian SNN + Transformer</b>
      <span style="float:right; font-size:80%; color:#7a7a7a;">2025 – Present</span>
    </p>
    Independent Research Project
    <ul style="margin-top: 5px; padding-left: 1.2em; color:#7a7a7a">
      <li>Designed a <b>Hybrid Bayesian Spiking Neural Network–Transformer</b> for real-time τ neutrino classification in IceCube HESE data.</li>
      <li>SNN front-end encodes Cherenkov photon arrival times; Transformer integrates global spatial correlations across the DOM array.</li>
      <li>Achieves <b>5× efficiency improvement</b> over BDT baselines at astrophysically critical energies (≳100 TeV).</li>
      <li>Provides <b>per-event uncertainty quantification</b> via variational inference, enabling reliable rejection of atmospheric backgrounds.</li>
      <li><i>Manuscript in preparation.</i></li>
    </ul>
  </div>
</div>
<hr style="height:1em; margin:0em; visibility:hidden;" />

<!-- Anomaly Detection Project -->
<div style="display:flex;">
  <div style="flex:0.5; padding-right:5%">
    <img src="{{ site.url }}images/resume/Anomaly.png" style="align:left; border: 1px solid #d3d3d3; border-style: outset;">
  </div>
  <div style="flex:4;">
    <p style="margin:0px">
      <b style="font-size: 130%;">Bayesian Latent Diffusion for Collider Anomaly Detection</b>
      <span style="float:right; font-size:80%; color:#7a7a7a;">May 2025 – 2026</span>
    </p>
    Independent Research Project
    <ul style="margin-top: 5px; padding-left: 1.2em; color:#7a7a7a">
      <li>Developed a <b>physics-informed Bayesian latent diffusion model</b> to identify model-independent new-physics signatures in LHC jet data.</li>
      <li>Combines a <b>probabilistic encoder</b> with latent-space diffusion dynamics, enforcing <b>mass decorrelation</b> and latent-correlation regularisation.</li>
      <li>Ablation studies confirm complementary roles of diffusion, Bayesian regularisation, and physics-motivated losses for training stability.</li>
      <li>Future work: <b>transformer encoders</b> on RODEM jet constituents for fully unsupervised, model-agnostic new-physics searches at detector level.</li>
      <li><i><a href="https://www.dropbox.com/scl/fi/pw92ytpe6re9gxj1rshr8/AD.pdf?rlkey=p8k17hhh2g6nbauj2ktq1kqq6&st=7dsvo6el&dl=0" target="_blank">Submitted to arXiv, 06 March 2025.</a></i></li>
    </ul>
  </div>
</div>
<hr style="height:1em; margin:0em; visibility:hidden;" />


<!-- JGU Mainz Master Thesis -->
<div style="display:flex;">

  <div style="flex:0.5; padding-right:5%">
    <img src="{{ site.url }}/images/resume/JGU.png" style="align:left; border: 1px solid #d3d3d3; border-style: outset;">
  </div>

  <div style="flex:4;">
    <p style="margin:0px">
      <b style="font-size: 130%;"><a href="https://www.uni-mainz.de/" target="_blank" style="color: black;">Johannes Gutenberg University Mainz</a></b>
      <span style="float:right; font-size:80%; color:#7a7a7a;">Sep 2023 - Sep 2024</span>
    </p>
    Master Thesis Project
    <div style="color:#7a7a7a">
      <i>Supervisor: Prof. Dr. Wolfgang Gradl</i>
    </div>
    <div>
      Systematic studies on the signal yield determination in the decay <b>B → K<sup>*</sup>(892)(→ Kπ)ℓ<sup>+</sup>ℓ<sup>−</sup></b> at Belle II 
      (<a href="https://www.dropbox.com/scl/fi/ac03vek7c21n0boqmjn9f/JGU_MT_Final.pdf?rlkey=34ryj05t0v9nmdlkft403lghk&st=sjq55f1q&dl=0" target="_blank" style="color:RoyalBlue;">Thesis</a>)<br/>
      Developed a fit model for the decay channel focusing on precise signal and background separation across various <i>q²</i> regions. Applied <i>q²</i> vetoes to reduce contamination from resonances like J/ψ and ψ(2S). Validated using control channels and tested robustness with toy Monte Carlo studies. Demonstrated model effectiveness on realistic Belle II data, providing groundwork for future high-luminosity rare decay studies.
    </div>
  </div>
</div>
<hr style="height:1em; margin:0em; visibility:hidden;" />

<!-- IPR Master Thesis -->
<div style="display:flex;">

  <div style="flex:0.5; padding-right:5%">
    <img src="{{ site.url }}/images/resume/ipr.png" style="align:left; border: 1px solid #d3d3d3; border-style: outset;">
  </div>

  <div style="flex:4;">
    <p style="margin:0px">
      <b style="font-size: 130%;"><a href="https://www.ipr.res.in/" target="_blank" style="color: black;">Institute for Plasma Research (IPR)</a></b>
      <span style="float:right; font-size:80%; color:#7a7a7a;">Apr 2016 - Apr 2017</span>
    </p>
    Master Thesis Project
    <div style="color:#7a7a7a">
      <i>Supervisor: Dr. Balasubramanian C.</i>
    </div>
    <div>
      Synthesis of SiC 1D nanostructure by plasma arc method 
      (<a href="https://www.dropbox.com/scl/fi/2reem9g2byskaq7mjzi6v/KSV-Master-Thesis.pdf?rlkey=k0ld4mff2rjxqk37s55aoz0eb&st=64a9llzx&dl=0" target="_blank" style="color:RoyalBlue;">Thesis</a>)<br/>
      Used thermal plasma arc discharge to synthesize 1D SiC nanostructures, with plasma current playing a key role in morphology. XRD confirmed crystal structure; TEM revealed SiC nanorods/nanowires. EDAX and elemental mapping validated silicon and carbon distribution in samples.
    </div>
  </div>
</div>
<hr style="height:2em; margin:0em; visibility:hidden;" />



Research Experience 💼
======
<!--
<div style="display:flex; align-items: flex-start; margin-bottom: 1em;">

  <div style="flex:0.5; padding-right:5%;">
    <img src="{{ site.url }}/images/resume/slac-logo.png"
         alt="SLAC National Accelerator Laboratory Logo"
         style="max-width:100%; border: 1px solid #d3d3d3; border-style: outset;">
  </div>

  <div style="flex:4;">
    <p style="margin:0px;">
      <b style="font-size: 130%;">SLAC National Accelerator Laboratory</b>
      <span style="float:right; font-size: 80%; color: #7a7a7a;">Aug 2025 – Present</span>
    </p>
    <div style="color: #7a7a7a; margin-top: 5px;">
      Working on <b>Primary Vertex Timing Reconstruction</b> with the LAr Calorimeter
      for the <i>HL-LHC</i>, using <b>transformer-based models</b> to improve
      vertex–jet association and event reconstruction under high pile-up conditions
      (~200 collisions per bunch crossing).
    </div>
  </div>
</div>

<hr style="height:1em; margin:0em; visibility:hidden;" />
-->

<!-- INFN Padova -->
<div style="display:flex; align-items: flex-start; margin-bottom: 1em;">

  <div style="flex:0.5; padding-right:5%;">
    <img src="{{ site.url }}/images/resume/INFN_Padova.png" alt="INFN Padova Logo" style="max-width:100%; border: 1px solid #d3d3d3; border-style: outset;">
  </div>

  <div style="flex:4;">
    <p style="margin:0px;">
      <b style="font-size: 130%;">INFN Padova</b>
      <span style="float:right; font-size: 80%; color: #7a7a7a;">Feb 2025 – Present</span>
    </p>
    <i>Research Assistant</i>
    <div style="color: #7a7a7a; margin-top: 5px;">
      Contributing to the <a href="https://mode-collaboration.github.io/" target="_blank">MODE Collaboration</a> by applying generative machine learning models, particularly diffusion models, to detector design. Currently focused on optimizing sampling calorimeters and gaining hands-on experience in simulation, generative modeling, and detector physics for future collider experiments.
    </div>
  </div>
</div>
<hr style="height:1em; margin:0em; visibility:hidden;" />

<!-- TU Dortmund -->
<div style="display:flex;">

  <div style="flex:0.5; padding-right:5%">
    <img src="{{ site.url }}/images/resume/TUD.png" style="align:left; border: 1px solid #d3d3d3; border-style: outset;">
  </div>

  <div style="flex:4;">
    <p style="margin:0px">
      <b style="font-size: 130%;">TU Dortmund University</b>
      <span style="float:right; font-size:80%; color:#7a7a7a;">Dec 2024 - April 2025</span>
    </p>
    Intern
    <div style="color:#7a7a7a">
      Working on calibration of boosted W/Z boson tagging algorithms using ATLAS 13 TeV data. Focus on deriving scale factors and improving jet substructure-based tagging performance.
    </div>
  </div>
</div>
<hr style="height:1em; margin:0em; visibility:hidden;" />

<!-- JGU Mainz -->
<div style="display:flex;">

  <div style="flex:0.5; padding-right:5%">
    <img src="{{ site.url }}/images/resume/JGU.png" style="align:left; border: 1px solid #d3d3d3; border-style: outset;">
  </div>

  <div style="flex:4;">
    <p style="margin:0px">
      <b style="font-size: 130%;">Johannes Gutenberg University Mainz</b>
      <span style="float:right; font-size:80%; color:#7a7a7a;">Aug 2021 - Aug 2024</span>
    </p>
    Research Assistant (various projects)
    <div style="color:#7a7a7a">
      <ul style="margin: 0.5em 0 0 1em; padding: 0;">
        <li><b>Active Polarized Proton Target:</b> Studied SiPM behavior under varying temperatures to optimize detector sensitivity.</li>
        <li><b>τ SPECT Experiment:</b> Data analysis and hardware integration for UCN lifetime studies.</li>
        <li><b>ATLAS HGTD:</b> Evaluated flexible PCB stability under thermal/geometrical stress for precision timing detectors.</li>
        <li><b>JUNO Neutrino Experiment:</b> Validated RTD sensors and developed LabVIEW DAQ tools for integration with liquid scintillator systems.</li>
        <li><b>Axion Dark Matter Experiment (ADMX):</b> Analyzed test spectra using an alternate CERN setup. Contributed to SUPAX detector development by improving sensitivity and noise reduction techniques.</li>
      </ul>
    </div>
  </div>
</div>
<hr style="height:1em; margin:0em; visibility:hidden;" />

<!-- HIM Mainz -->
<div style="display:flex;">

  <div style="flex:0.5; padding-right:5%">
    <img src="{{ site.url }}/images/resume/him.png" style="align:left; border: 1px solid #d3d3d3; border-style: outset;">
  </div>

  <div style="flex:4;">
    <p style="margin:0px">
      <b style="font-size: 130%;">Helmholtz Institute Mainz</b>
      <span style="float:right; font-size:80%; color:#7a7a7a;">Jun 2021 - Sep 2021</span>
    </p>
    Research Assistant
    <div style="color:#7a7a7a">
      Contributed to the assembly of the PANDA Backward Electromagnetic Calorimeter for the FAIR experiment. Involved in detector construction and integration.
    </div>
  </div>
</div>
<hr style="height:2em; margin:0em; visibility:hidden;" />

Teaching Experience 💡 
======
<hr style="margin-top: 0.5em; margin-bottom: 1em;" />

<!-- KSV Teaching Assistant -->
<div style="display:flex;">

  <div style="flex:0.5; padding-right:5%">
    <img src="{{ site.url }}/images/resume/KSV.png" style="align:left; border: 1px solid #d3d3d3; border-style: outset;">
  </div>

  <div style="flex:4;">
    <p style="margin:0px">
      <b style="font-size: 130%;">Kadi Sarva Vishwavidyalaya</b><br/>
      <b style="font-size: 110%;">Teaching Assistant</b>
      <span style="float:right; font-size:80%; color:#7a7a7a;">Jun 2017 – Feb 2021</span>
    </p>
    <div style="color:#7a7a7a; margin-top: 0.5em;">
      Conducted undergraduate and graduate teaching in physics.
    </div>
    <p style="margin:0.8em 0 0.2em 0;"><b>Responsibilities:</b></p>
    <ul style="margin-top: 0.2em;">
      <li>Assisted in preparing <b>lecture notes and assignments</b> for undergraduate and graduate physics courses.</li>
      <li>Conducted <b>lectures, tutorials, and lab sessions</b> for Bachelor’s and Master’s students.</li>
      <li>Designed and delivered course materials for various physics subjects.</li>
    </ul>
    <p style="margin:0.8em 0 0.2em 0;"><b>Courses Taught:</b></p>
    <ul>
      <li>Applied Physics and Engineering Physics</li>
      <li>Electronics</li>
      <li>Nuclear and Particle Physics</li>
    </ul>
  </div>
</div>
<hr style="height:2em; margin:0em; visibility:hidden;" />

<!--   
Awards 
======
<ul>
  <li>
    <b>Knight-Hennessy Scholarship </b>
    <span style="float:right; font-size:80%; color:#7a7a7a;">2021</span> <br>
    <i>PhD funding</i>
  </li>
<!-- 
  <li>
    <b>Cambridge' Department of Engineering Scholarship </b>
    <span style="float:right; font-size:80%; color:#7a7a7a;">2018</span> <br>
    <i>MPhil funding</i>
  </li>
<!-- 
  <li>
    <b>Valedictorian </b>
    <span style="float:right; font-size:80%; color:#7a7a7a;">2018</span> <br>
    <i>MPhil funding</i>
  </li> -->

  <!-- <li>
    <b>Silicon Valley Startup Camp</b>
    <span style="float:right; font-size:80%;color:#7a7a7a;">2018</span> <br>
    <i>Trip organized for rising Swiss entrepreneurs.</i>
  </li> -->
