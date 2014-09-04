---
title: Beam Simulation Tools (doctoral thesis)
layout: post
permalink: beam-simulation
---

UNDER CONSTRUCTION
==================

To design and support the AIMS diagnostic developed in my doctoral thesis work, I developed suite of ion beam dynamics simulation tools.  These tools are capable of modeling modeling classical and relativistic ion beam trajectories in the complex 3D magnetic fields. In addition, the code can model the 6D dynamics of the of the beam's phase space distrubiton as it evolves due to beam curvature, magnetic field gradients, and space charge effects. This code has also been extended to include relivistic effects that are important from high energy ion beams and moderate to high energy electron beams. 

![AIMSSimulationPlot1](/images/AIMSSimulationPlot1.png){: .inline-img}

The simulation tools were written in python and are available from my github repository: <a href='https://github.com/hbar/python-BeamDynamicsTools'>python-BeamDynamicsTools</a>. These tools are functional and have been validated against Los Alamos beam transport codes for overlapping test cases but are still a work in progress.  I am in the process of adding more advanced features and improving user-friendliness. 

3D Trajectory Calcuation:
----------------------

A 3D simulation of particle trajectory for beam targeting is shown bellow. The trajectories can be calculated with either with the Euler integration method or the <a href='http://en.wikipedia.org/wiki/Leapfrog_integration'> leapfrog integration</a> method to reduce first order error. 

![TrajectoryProjection](/images/Simulation-TrajectoryProjection.png)

While calculating the trajectory, the local position, velocity, and basis vectors along with the magnetic fields and gradiets are calculated to be used later in the dynamics calculation. For accurate trajectories to be calculated, the magnetic fields must be modeled.  In the case of tokamak, which is symmetric about the z-axis, the symmetry can be exploited allowing 2D field models to be used.

The toroidal field is calculated using a model that represents the each toroidal field coil a vertical current filaments. The equations and field magnitude plot are shown below. 

![TFMagnitudePlot](/images/Simulation-ToroidalFieldPlot.png)

The vertical field is calculated using the elliptic integral solution for off axis current loops. The equations and field plots are shown below.

![VFMagnitudePlot](/images/Simulation-VerticalField.png)

From observing the beams trajectory through the magnetic fields, it is clear that the beam experiences strong field gradients and non-uniformities as it passes the coil sets in the tokamak which can cause complex focusing/defocusing effects. 

![FieldMap](/images/Simulation-VerticalToroidalFieldMap.png)

The code can be further generalized by applying field maps that are calculated in using other finite element analysis packages.

6D Dynamics Calculation
-----------------------

Predicted beam distribution on target based on 6D phase-space beam dynamics simulation: 

![AIMSSimulationPlot2](/images/AIMSSimulationPlot2.png){: .inline-img}



We are currently in the process of upgrading the beam steering power supplies to improve the spatial extent of our measurements. This is an ongoing process involving beam optics simulation, the implementation of active focusing, and DC power engineering which will dramatically improve the capabilities of this diagnostic.

![AIMSUpgradePlot2](/images/BeamCoveragewithTFUpgrade.png){: .inline-img}

![LaminarSpaceCharge1](/images/Simulation-LaminarVsNonLaminar.png)
![LaminarSpaceCharge2](/images/Simulation-SpaceChargeVsEmittance.png)



![TransferMatrices](/images/Simulation-TransferMatrices.png)
![TransferMatricesDef](/images/Simulation-TransferMatricesDefCombined.png)
![Validation1](/images/Simulation-Validation1.png)
![Validation2](/images/Simulation-Validation2.png)



