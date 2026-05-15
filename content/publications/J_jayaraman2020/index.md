---
title: "Direct Numerical Simulation of Turbulence over Two-Dimensional Waves"

authors:
  - Balaji Jayaraman
  - me

date: "2020-02-21"
publishDate: "2020-02-21"

publication_types: ["article-journal"]

publication: "*AIP Advances 10*, 025034"
publication_short: ""

hugoblox:
  ids:
    doi: 10.1063/1.5140000

abstract: |
  Knowledge of turbulent flows over non-flat surfaces is of major practical interest in diverse applications. Significant work continues to be reported in the roughness regime at high Reynolds numbers where the cumulative effect of surface undulations on the averaged and integrated turbulence quantities is well documented. Even for such cases, the surface topology plays an important role for transitional roughness Reynolds numbers that is hard to characterize. In this work, we explore in detail the mechanisms underlying turbulence generation and transport, particularly within the region of the turbulent boundary layer affected by the surface. We relate surface shape with turbulence generation mechanisms and Reynolds stress transport, which has implications to drag increase. We accomplish this using a suite of direct numerical simulations of fully developed turbulent flow between two infinitely wide, two-dimensional sinusoidally wavy surfaces at a friction Reynolds number, \(Re_\tau = 180\), with different mean surface slopes, \(\zeta\) and fixed inner-scaled undulation height, \(a^+ = 13\), corresponding to the “waviness” regime. The increase in wave slope enhances near surface turbulent mixing, resulting in increased total drag, higher fraction of form drag, faster approach to isotropy, and thereby modulation of the buffer layer. The primary near-surface streamwise and vertical turbulence production occurs in the leeward and windward sides of the wave, respectively. Furthermore, this production structure shows significant dispersion effects. However, the primary generation process of vertical and spanwise variance occurs through pressure–strain rate mechanism in the windward side.

summary: |
  DNS study of turbulent flow over two-dimensional sinusoidal waves, focusing on how wave slope affects near-surface turbulence generation, Reynolds stress transport, drag increase, and return to isotropy.

tags:
  - Computational Fluid Dynamics (Turbulence)
  - Direct Numerical Simulation
  - Wavy Surface Flow
  - Reynolds Stress Transport
  - Turbulence Generation
  - Immersed Boundary Method
  - High-Order Numerical Methods

featured: true

links:
  - type: pdf
    url: jayaraman2020.pdf

 # - type: source
 #   url: https://doi.org/10.1063/1.5140000

image:
  caption: "instantaneous vorticity field in turbulent channel for varying wave steepness factors"
  focal_point: "Center"
  preview_only: false

projects: []

slides: ""
---

This work extends the earlier publication
[Statistical Structure and Deviations from Equilibrium in Wavy Channel Turbulence](/publications/J_khan2019/)
by focusing specifically on Reynolds-stress transport physics and turbulence production mechanisms over sinusoidal surfaces. Using highly resolved direct numerical simulations (DNS) of fully developed turbulent channel flow between infinitely wide two-dimensional sinusoidal walls, the study systematically investigates how increasing wave slope alters the spatial structure of turbulence generation, pressure–strain redistribution, and anisotropy dynamics within the near-wall region.

Unlike the earlier study that primarily emphasized deviations from equilibrium turbulence structure and roughness characterization, this work performs a deeper transport-equation-level analysis of Reynolds stress budgets and identifies the distinct physical mechanisms responsible for streamwise, wall-normal, and spanwise turbulence production over wavy geometries. The simulations reveal that streamwise turbulence production is concentrated predominantly on the leeward side of the wave, while vertical turbulence production is amplified along the windward face due to strong pressure–strain interactions. The work further demonstrates how increased wave slope accelerates return toward isotropy, modifies buffer-layer dynamics, and increases the contribution of form drag relative to viscous drag.

The numerical simulations employ spectrally accurate compact finite-difference schemes together with immersed boundary methods to represent sinusoidal geometries without body-fitted meshing. The study provides detailed insight into turbulence transport physics over non-flat surfaces and contributes toward understanding drag generation mechanisms in the transitional waviness regime.