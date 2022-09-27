---
title: "Electromechanics of Heart Muscle"
excerpt: "How an electrical impulse propagates through the domain and induces deformation at its wake"
collection: portfolio
---

We say that during a heartbeat, the Heart contracts and relaxes. But what actually happens at the microscopic level? The Heart muscle is mainly made of two different types of muscle cells:
* Myocytes which contract
* Pacemaker cells which generate electrical signals

A Myocyte contains specific ions (mainly sodium, potassium and calcium). The difference in distribution of these ions inside and outside the cell creates a potential difference. To maintain this potential at rest, there are channels/pumps in the boundaries of the cells which add or remove the ions. These channels are peculiar, in the sense that they get activated only when a particular potential difference is reached. These are called *[voltage-gated ion channels](https://en.wikipedia.org/wiki/Voltage-gated_ion_channel)*. When the pacemaker cells generate electrical signals, they propagate all throughout the Heart. This propagation happens because when the signal reaches a myocyte, there is a change in the potential difference. During this unrest inside the cell, the *[myofibrils](https://en.wikipedia.org/wiki/Myofibril)* which make up the myocytes, contract. This effect propagates to the next cell and the chain of events lead to what we see as the contraction of the Heart. But, this contraction is not permanent. We know that, the Heart relaxes after the contraction and the cycle repeats. 


This cyclic behaviour divides the study into two parts. Firstly, the Electrophysiology part where there is one agent which activates the flow of ions inside the cell leading to the contraction, and another agent which inhibits the contraction bringing the Heart back to normal. Secondly, the mechanics part where the material which makes up the Heart has the ability to deform and return back to its original state, hinting at the elastic nature. [^1] [^2] [^3] [^4]


My work was to simulate the one-way coupling between the electrophysiology and solid mechanics. One-way coupling is when the electrical signal induces a deformation in the domain. Two-way coupling is when the deformation in turn affects the propagation of the signal leading to a feedback loop. I used [COMSOL](https://www.comsol.com/) for all my simulations.


> This work was done as part of my first thesis project, under the guidance of [Dr. Yong Wang](https://bmewang.com/) at [Max-Planck Institute for Dynamics and Self-Organization](https://www.ds.mpg.de/en). The work was done remotely.


If I still have your interest, then you can check out all the details of this project in the document below.

<embed src="{{ site.baseurl }}/files/Heart coupling_ankush copy.pdf" width="600" height="700" type='application/pdf'>


[^1]: [Pinto, J. G., & Fung, Y. C. (1973). Mechanical properties of the heart muscle in the passive state. Journal of biomechanics, 6(6), 597-616.](https://www.sciencedirect.com/science/article/abs/pii/0021929073900171)
[^2]: [Huxley, H. E. (1965). The mechanism of muscular contraction. Scientific American, 213(6), 18-27.](https://www.jstor.org/stable/24931213)
[^3]: [Nash, M. P., & Panfilov, A. V. (2004). Electromechanical model of excitable tissue to study reentrant cardiac arrhythmias. Progress in biophysics and molecular biology, 85(2-3), 501-522.](https://www.sciencedirect.com/science/article/pii/S0079610704000239)
[^4]: Wit, A. L., Boyden, P. A., Josephson, M. E., & Wellens, H. J. (2020). Electrophysiological Foundations of Cardiac Arrhythmias: A Bridge Between Basic Mechanisms and Clinical Electrophysiology. Cardiotext Publishing.