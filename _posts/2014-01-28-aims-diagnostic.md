---
title: AIMS Diagnostic (doctoral thesis)
layout: post
permalink: aims-diagnostic
---

![AIMSPhotographs](/images/AIMSPhotographsCombined.png){: .inline-img}

<p> For my doctoral research I developed a novel in-situ ion-accelerator-based diagnostic technique for
studying plasma-materials interactions in the Alcator C-Mod tokamak (MIT's fusion experiment). This essentially involved integrating a particle accelerator with a fusion reactor to allow us to make ion beam measurements of materials in the reactor. These measurements allow us dynamically measure how the plasma within the fusion device changes the composition of surfaces that come in contact with the plasma. This work was a collaboration with Z.S.Hartwig, B.N.Sorbom, and D.G.Whyte. My contributions to this project focused on development of the accelerator hardware, controls, and power system as well as particle beam dynamics modeling.</p>

![nsideAlcatorPhoto](/images/InsideAlcatorPhoto.png){: .inline-img}

<p> This new diagnostic is referred to as Accelerator-based In-situ Materials Surveillance (AIMS). The AIMS diagnostic injects a 900 keV deuterium ion beam into the tokamak's vacuum vessel between plasma discharges while magnetic fields are used to steer the ion beam to plasma facing component (PFC) surfaces. Spectroscopic analysis of neutrons and gamma rays from the induced nuclear reactions provides a quantitative, spatially resolved map of the PFC surface composition that includes boron (B) and deuterium (D) content. Since AIMS is sensitive to low-Z elements and C-Mod regularly plasma coats PFCs with boron to improve plasma performance, the evolution of B and D on PFCs can be used to directly study erosion, deposition, and fuel retention in response to plasma operations and wall conditioning processes. </p>

![AIMSCADcutaway](/images/AIMSCADcutaway.png){: .inline-img}

<p>This is the first diagnostic to provide in-situ, spatially-resolved measurements of the effects
of plasma-materials interactions in a fusion reactor. This has many important implications for magnetic
fusion energy science and will provide critical information on how optimize plasma conditions and material choices to ensure the longevity of fusion reactors.</p>

<p>Through this project, I also developed a strong background in accelerator engineering and particle
beam modeling. I rebuilt and upgraded a radio frequency quadrupole accelerator, including its control
and power systems. In addition, I developed my own ion beam dynamics simulation tools.  These tools are capable of modeling for modeling classical and relativistic ion beams in the complex 3D magnetic fields of devices like tokamaks.</p>

3D simulation of particle trajectory for beam targeting:

![AIMSSimulationPlot1](/images/AIMSSimulationPlot1.png){: .inline-img}

Predicted beam distribution on target based on 6D phase-space beam dynamics simulation: 

![AIMSSimulationPlot2](/images/AIMSSimulationPlot2.png){: .inline-img}

The simulation tools were written in python and are available from my github repository: <a href='https://github.com/hbar/python-BeamDynamicsTools'>python-BeamDynamicsTools</a>. These tools are functional and have been validated against Los Alamos beam transport codes for overlapping test cases but are still a work in progress.  I am in the process of adding more advanced features and improving user-friendliness. 

We are currently in the process of upgrading the beam steering power supplies to improve the spatial extent of our measurements. This is an ongoing process involving beam optics simulation, the implementation of active focusing, and DC power engineering which will dramatically improve the capabilities of this diagnostic.

![AIMSUpgradePlot2](/images/BeamCoveragewithTFUpgrade.png){: .inline-img}


