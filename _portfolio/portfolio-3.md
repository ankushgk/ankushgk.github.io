---
title: "Growth of Filamentous Fungal Biofilms"
excerpt: "How different external conditions impact the growth dynamics of filamentous fungal biofilms"
collection: portfolio
---

There is a very high chance that you have seen a biofilm. You may not have known at the time. To jog your memory, if you have been to a river bed or a pond, you may have seen greenish layers on the rocks nearby. They are nothing but clusters of microorganisms, a.k.a biofilms. Why do they form this? It has been found that the quality of life is much better for a microorganism living as part of a biofilm. The biofilm provides resistance to anti-microbial agents, protection from the environment, an amazing network for nutrient transport. If the microorganism were to survive as an individual, its life would be quite adventurous. Almost all kinds of infections happen not because of one individual microorganism. There is usually a biofilm behind it. So in that sense there are life-threatening facets of biofilms where the properties and process of formation of biofilms becomes an important part of the study to come up with ways to eradicate them. 

Among many types of biofilms, this work focused on filamentous fungal biofilm. In this case, the fungal cells do not divide into two daughter cells, instead they elongate and form filament-like structures called *hypha*. When there are large number of such fungal cells, these hyphae interconnect and form networks forming a *mycelium*. These fabulous networks can be thought of as roads in a city, only much more efficient. 


I worked on simulating a mesoscopic model of filamentous fungal biofilm which focused on a corse-grained view with densities as variables and not focusing on individual hyphae. The model I worked with was a system of five coupled PDEs with the variables:
* Active Hyphal density - which is the main growing part of the biofilm
* Inactive Hyphal density - which are the parts that become inactive after certain threshold
* Hyphal Tip density - number of tips of hyphae per unit area since tips are the ones that extend
* Internal Substrate concentration - concentration of nutrients inside a hypha
* External Substrate concentration - concentration of nutrients outside the hyphae from which the biofilm feeds on to grow


Depending on the available external nutrients, the biofilm growth differs and forms different density patterns. To know more about this, check out the document below.
[^1] [^2] [^3]

>This work was done as part of my second thesis project, under the guidance of [Prof. Aravinda Raghavan](https://universe.bits-pilani.ac.in/Hyderabad/aravindaraghavan/profile) at [BITS Pilani Hyderabad Campus](https://www.bits-pilani.ac.in/hyderabad/).


<embed src="{{ site.baseurl }}/files/fungal biofilms_ankush copy.pdf" width="600" height="700" type='application/pdf'>

[^1]: [Sugai-Guérios, M. H., Balmant, W., Furigo, A., Krieger, N., & Mitchell, D. A. (2015). Modeling the growth of filamentous fungi at the particle scale in solid-state fermentation systems. Filaments in Bioprocesses, 171-221.](https://link.springer.com/chapter/10.1007/10_2014_299)
[^2]: [Mazza, M. G. (2016). The physics of biofilms—an introduction. Journal of Physics D: Applied Physics, 49(20), 203001.](https://iopscience.iop.org/article/10.1088/0022-3727/49/20/203001/meta?casa_token=vjkpMcKrPsoAAAAA:Rx4Y3U0jHnmAJHAkshLJXgT8lPXd8MjWt2QoQUB9ZWIEYXsXS4k9UZIQuo8MTHz6Yxf64vrNXRGMUxI)
[^3]: [Fischer, M. S., & Glass, N. L. (2019). Communicate and fuse: how filamentous fungi establish and maintain an interconnected mycelial network. Frontiers in microbiology, 10, 619.](https://www.frontiersin.org/articles/10.3389/fmicb.2019.00619/full)