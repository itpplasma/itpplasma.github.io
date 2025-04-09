---
layout: newdefault
---

## Research outline

Coupled dynamics of charged particles with electromagnetic fields are crucial for the theoretical understanding of nuclear fusion devices, where hot plasmas are confined in strong magnetic fields. Of particular importance for future fusion reactors are transport processes related to particle dynamics, propagation of waves and their resonant and non-resonant interaction with the plasma. These transport phenomena are governed by either fluid equations (MHD) or by kinetic equations (Boltzmann-Equation with Coulomb collision operator.

In addition, the system is closed by Maxwell's equations for the electromagnetic field. The numerical simulation represents a high dimensional problem where extremely different time and space scales are involved. It has to be solved for toroidal geometry with complex topology including stochasticity of the magnetic field. Typically, those systems cannot be solved without reducing the dimensionality of the problem. This is accomplished by proper averaging procedures and mappings between Poincare cuts.

Our research is embedded into the international fusion energy research
programme that aims to develop a fusion power plant. Our main contribution
are on kinetic models in non-axisymmetric magnetic plasma confinement devices:
Stellarators and tokamaks with 3D magnetic perturbations. These models help
to understand how to control the plasma in order to avoid instabilities and
how to keep energetic particles confined so they can self-heat the plasma.

You can find a list of our publications on [Zotero](https://www.zotero.org/itpplasma).

----

## Main topics

----

### Stellarator physics `STEL`

#### Optimizer metrics for stellarators `STEL/OPT`

* Team: Sergei Kasilov, Christopher Albert
* Our codes: [SIMPLE](https://github.com/itpplasma/SIMPLE), [NEO-RT](https://github.com/itpplasma/NEO-RT), NEO-2
* Other codes: [STELLOPT](https://github.com/PrincetonUniversity/STELLOPT), ROSE, [simsopt](https://github.com/hiddenSymmetries/simsopt)


#### Resonant effects in Wendelstein-7X `STEL/W7-X`

* Team: Winfried Kernbichler, Christopher Albert, Sergei Kasilov, Markus Markl
* Our codes: KiLCA/QL-BALANCE
* Other codes: [VMEC](https://github.com/PrincetonUniversity/STELLOPT), DKES, HINT


#### Physics and technology of small stellarators `STEL/ALPS`

* Team: Christopher Albert, Georg Harrer (TU Wien)

----

### Tokamak physics `TOK`

#### 3D plasma equilibria and plasma rotation in EU-DEMO `TOK/DEMO`
The EUROfusion task on DEMO aims at the design of a demonstrator fusion power plant, currently an upscaled version of the ITER tokamak.
The of our contribution is to evaluate the current design for error field correction (EFC) coils in terms of toroidal rotation braking by neoclassical toroidal viscous (NTV) torque.
In collaboration with Leonardo Pigatto (Padova) the current setup for EFC coils in DEMO is investigated.
The current engineering design aims to use coils in a single row in the midplane with various radii.
The questions we want to answer is, how severe are the side-effects of this setup in terms of braking the plasma rotation via NTV torque.
Towards this goal we need to create 3D magnetohydrodynamic equilibria, which are then used by NEO-2 and [NEO-RT](https://github.com/itpplasma/NEO-RT) to compute the torque on the plasma. Our group is currently responsible for the nonlinear variant of this computation in the code VMEC.

* Team: Christopher Albert, Georg Grassler
* Our codes: NEO-2, [NEO-RT](https://github.com/itpplasma/NEO-RT)
* Other codes: MARS-Q, [VMEC](https://github.com/PrincetonUniversity/STELLOPT)

#### Plasma response to resonant magnetic pertubations `TOK/RMP`
Future fusion reactors built on the tokamak principle, e.g. ITER, are projected to be afflicted by instabilities occuring at the plasma edge. These so-called edge localized modes can be suppressed by disturbing the magnetic equilibrium, confining the plasma, with additional externally generated magnetic fields. However, the exact physical mechanism behind the supression is yet unknown.
To fully understand the mechanism of the suppression of the edge localized modes,we study the plasma response to magnetic pertubations. For this investigation, we employ kinetic theory which, in contrast to the macroscopic fluid theory. covers more physical processes that are potentially important. With numerical and analytical tools we advance the understanding of the suppression of edge localized modes in tokamak plasmas which is crucial for the safe operation of future reactors.

* Team: Markus Markl, Sergei Kasilov, Christopher Albert
* Our codes: KiLCA/QL-BALANCE, MEPHIT
* Other codes: GPEC, MARS-F

#### Kinetic ions in the plasma edge region `TOK/EDGE`
Team: Jonatan Schatzlmayr

* Our codes: [GORILLA](https://github.com/itpplasma/GORILLA), MEPHIT
