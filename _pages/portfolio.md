---
layout: archive
title: "Research interests"
permalink: /portfolio/
author_profile: true
keywords: "phase-field models, computational materials science, solidification microstructures"
---


## Computational workflows
 
Numerical algorithms and associated meta-data are the backbone of simulations in engineering problems, where, practically, different methods are chained to design workflows. In this work we analyze general and particular components and provides an abstract multi-layered description of CSE workflows: Each component will be characterized through an input/output description so that model, code, and data can be used interchangeably and, in the best case, redundantly. A working proof of concept has been published recently, and can be accessed [here](http://arxiv.org/abs/2405.00028).


<img src="/images/workflow.png" style="display: block; margin: 0 auto; width: 400px;">


## Phase-field modeling 

Phase-field approach is a popular method of choice to model complex microstructures observed during solidification. The principal idea of any phase-field model is to characterize the phases using a non-conserved order parameter that varies smoothly across the diffuse interface. In general, the governing equation ensures that the interface profile evolves in order to minimize the free energy of the system with time, and it is then coupled to the diffusion field near the solid-liquid interface. Below are some research topics addressed through the phase-field approach.

* ### Liquid grooving at grain boundaries

Grain boundaries (GB) are of considerable scientific and technological interest due to their significant influence on the final microstructural and material properties. Apart from initiating preferential diffusion pathways, and assisting void formation, the deepening of grain boundary grooves at multigrain junctions is widely suggested as the primary mechanism
for thin film breakup. In this study, a multiphase-field model was employed, wherein the Beckermann approach  was followed in order to incorporate melt convection in the model formulation. As shown in the below figure, the symmetric groove developed under diffusive regime translated into an asymmetric form under the presence of lateral flow in the domain. This work has been published in *Acta Materialia* and can be accessed [here](https://www.sciencedirect.com/science/article/abs/pii/S1359645420309228). More recently, we studied the  effect of interfacial surface anisotropy, published in *Journal of Applied Physics*, can be accessed [here](https://www.sciencedirect.com/science/article/abs/pii/S1359645420309228). 

**Note:** Inclusion of mass transport along the grain-boundaries and its effect on liquid grooves is a topic of ongoing research, further details shall be shared here soon. 
 

| <br/><img src='/images/liquid_groove2.png'> | 
|:--:| 
| *Liquid grooving at grain boundaries* |
 
 
 
* ### Dendritic growth competition
In this study, we investigated the prediction of inter-dendritic growth competition at the grain boundary. Commonly observed during the production of single crystal Ni-based turbine blades, the overgrowth behaviors of misoriented columnar dendrites at the grain boundary was simulated and analyzed under isothermal solidifications. Moreover, through microstructural selection maps, it was also concluded that solidification parameters such as misorientation angle and interfacial anisotropy largely controlled the critical melt velocity to predict the overgrowth dynamics at the grain boundary. Besides, we also briefly studied the role of lateral convection on the prediction of inter-dendritic arm spacing among columnar dendrites. This work has been published in *Computational Materials Science* and can be accessed [here](https://www.sciencedirect.com/science/article/abs/pii/S0927025620304559). 


| <br/><img src='/images/dendrite_growth.png'> | 
|:--:| 
| *Inter-dendritic growth competition* |

* ### Tip splitting microstructures
One of the foci of my doctoral research was on tip splitting microstructures in energetically isotropic interfaces whereby the lack of interfacial anisotropy promotes an uninhibited, omnidirectional growth, and exhibits profuse irregular branching and splittings of an evolving solid-liquid interface. The simulated microstructures generally evolved towards an extremely complex interfacial pattern, and resemble a *seaweed*, *coral*, or other natural growth forms. This work has been published in two different articles, and can be accessed via [article 1](https://www.sciencedirect.com/science/article/abs/pii/S0927025619304951) & [article 2](https://www.mdpi.com/2075-4701/12/3/376).

| <br/><img src='/images/seaweed_micro2.png'> | 
|:--:| 
| *Tip splitting microstructures* |

