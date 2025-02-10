

https://github.com/user-attachments/assets/3c8929a1-fc0a-4e00-a0e6-9113cbb631f7

# G4XrayPolarimeter
In my earlier post-doctoral work 🧑‍🎓, I participated in a conceptual study in simulating an optimal detector configuration for a Polarimeter to measure X-ray polarization emitted from extreme magnetic and gravitational fields in astrophysical sources 🚀🌌🕳️🌟.

The proposed design was based on Thomson scattering principle which involves a central scatterer (of low Z) surrounded by X-ray detectors to measure the azimuthal distribution of scattered photons. However, one of the design constraints ⚖️ required the scatterer to have sufficient depth in the direction of incident photons 🏄 to cause the primary Thomson scattering interaction but thin enough 🎣 in the perpendicular direction so as to avoid loss of the scattered photon within the scatterer itself. These necessitate simulating an optimal detector geometry to obtain a minimum detectable polarization (MDP) and a good figure-of-merit (FoM) 🎯.

A standard toolkit ⚒️, Geant4, is used for simulating interaction of radiation with matter in complex geometries. It is written in C++ and contains a plethora of physics processes. Thus, it is the onus of the developer to code the geometry and the relevant physics. Six geometrical configurations involving different shapes for the scatter and the surrounding detectors were simulated for 3 different materials viz., Beryllium, Lithium and Lithium Hydride; a range of thicknesses; range of energies (5-30 keV) for the incident photons; and polarizations angles from 0 to 90 degrees. The optimal configuration included a conical scatterer made of Lithium and surrounded by a cylindrical detector, followed by others.

Details can be found in the following publication: http://dx.doi.org/10.1016/j.nima.2010.02.116
