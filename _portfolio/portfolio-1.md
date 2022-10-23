---
title: "Active Nematics on Manifolds"
excerpt: "How liquid crystals (nematics, to be specific) behave on different geometries"
collection: portfolio
---

You may have heard the name Liquid Crystals. They are the building blocks of the Liquid Crystal Displays (LCDs). The interesting thing about liquid crystal molecules is that they are typically rod-shaped, which gives them the ability to interact with neighbouring liquid crystal molecules and establish order. This order is mostly orientational, meaning that an ordered system of liquid crystal molecules have a definite angle at which each molecule lies. The invention of LCDs happened because, scientists found that they can manipulate the orientational order of the molecules by applying an external electric/magnetic fields. Depending on the orientation, the liquid crystals show different properties. Such abilities make them neither liquids, nor crystals but somewhere in between. Hence, the name liquid crystals. 


My focus is on a specific type of liquid crystal, called **Nematics**. They are head-tail symmetric or in other words the up and down orientations of a molecule cannot be distinguished. This symmetry gives rise to different patterns (or *[defects](https://physics.stackexchange.com/questions/285731/what-is-a-topological-defect)*) which can be classified using Winding numbers. If we want to study such patterns, we need to quantify the orientational order of the system. This is where *Order Parameter* comes in. For a Nematic, due to its unique symmetry, the order parameter is a tensor quantity. This quantity encodes the magnitude of the order, and orientation, while being able to differentiate a nematic from other type of liquid crystal. 


Now, instead of applying external fields to manipulate the molecules, what if the system can manipulate the orientational order by itself? This is the trait of *Active Matter*, and every biological system is *active*. In recent years, researchers have found examples of Nematics in biological systems (cue, the name **Active Nematics**). [^1] [^2] [^3]


I am working on simulating the isotropic-nematic transition using the Landau - de Gennes equilibrium model on a 2D flat manifold first. Building on this, I will shift to a spherical domain, then include time-dependent terms, then add on active part, and finally hope to get them to work on an arbitrary geometry. Since this is a PDE model, I am using [Finite Element Method](https://en.wikipedia.org/wiki/Finite_element_method) to solve them. The simulations are done in the framework of [FEniCs](https://github.com/FEniCS).


>This is an ongoing project, done under the guidance of [Dr. Vijaykumar Krishnamurthy](https://www.icts.res.in/people/vijay-krishnamurthy) at [ICTS](https://www.icts.res.in/) in Bengaluru, India.

[^1]: [Doostmohammadi, A., Ignés-Mullol, J., Yeomans, J.M. et al. Active nematics. Nat Commun 9, 3246 (2018)](https://www.nature.com/articles/s41467-018-05666-8#citeas)
[^2]: [Shankar, S., Souslov, A., Bowick, M.J. et al. Topological active matter. Nat Rev Phys 4, 380–398 (2022)](https://www.nature.com/articles/s42254-022-00445-3#citeas)
[^3]: De Gennes, P. G., & Prost, J. (1993). The physics of liquid crystals (No. 83). Oxford university press.