## Welcome to the Tapia 2019 Doctoral Consortium Website

The Doctoral Consortium is a one-day workshop that provides an opportunity for doctoral students to discuss and explore their research interests with a panel of established researchers in computing.

Doctoral students must have submitted an application during the Tapia 2019 Call for Participation to be selected for the Doctoral Consortium.

The Tapia 2019 doctoral consortium is Chair by [Dr. Alvitta Ottley](http://tapiaconference.org/about/committees/alvittaottley) and [Dr. Jerome McClendon](http://tapiaconference.org/about/committees/jerome-mcclendon).


#### Location
Wednesday, September 18, 2019 — 12:00PM - 5:00PM EST <br/>
[Marriott Marquis San Diego Marina](http://tapiaconference.org/venue/) <br/>
Room: TBD <br/>


### Schedule:

| Session | Start | End | :---: | |
| --- | --- | --- | :---: | |
|**Lunch** | 12p | 1p | x | |
|Opening/Intro | 1p | 1:15p | x | |
|Session 1| 1:15p | 1:45p | [Saoni Mukherjee](#saoni-mukherjee) | |
|Session 2| 1:45p | 2:15p | [Jomara Sandbulte](#jomara-sandbulte) | |
|**Break**| 2:15p | 2:30p | | | 
|Session 3| 2:30p | 3:00p | [Harsha Gwalani](#harsha-gwalani) | |
|Session 4| 3:00p | 3:30p | [Brianna B. Posadas](#brianna-b-posadas)| |
|**Break**| 3:30p | 3:45p | | | 
|Session 5| 3:45p | 4:15p | [Lara J. Martin](#lara-j-martin) | |
|Discussion| 4:15p | 4:45p | x | |
|Closing| 4:45p | 5:00p | x | |
|Optional Networking| 5:00p | 5:30p | x | |


---


### For Presenters

- The room will not have a laptop. If possible, please be prepared to use your own laptop to present.
- Each presenter will give a 20 minute presentation with about 10 minutes for panel comments.
- Please add your **1-slide/1-minute self-introduction slide** directly to the presentation document, or you may send it to the Doctoral Consortium co-chair alvitta@wustl.edu before **Monday, September 16 midnight US pacific time**. Please follow the [slide template](https://docs.google.com/presentation/d/1TFiIjDPAEzvBFrKKokhPCOrfF-kaaLX4tcF-uR4E4uk/edit?usp=sharing) to prepare your slide. This slide will be presented by you during the opening of the Doctoral Consortium to allow other consortium attendees to know more about you before the networking throughout the consortium.
- Please refer to [this blog post](http://programanalysis.blogspot.com/2012/10/splash-2012-doctoral-symposium.html) when preparing your 20-minute presentation at the Doctoral Consortium (advice information on [Tao Xie's advice portal](http://web.engr.illinois.edu/~taoxie/advice/) can be also useful).
- Include a slide that details your primary concerns and feedback you hope to recieve from the judges. 

### Panelists

TBD


### Presenters

| Names | Affiliation | Title |
| ------------ |------------------ | --------------------------------------- |
| Saoni Mukherjee | Northeastern University | [GIPSim: low level power modeling for resiliency in Side Channel attack on GPUs](#soani-mukherjee) |
| Jomara Sandbulte | Pennsylvania State University | [Design and Evaluation of Intergenerational Health Collaboration System within the Family](#jomara-sandbulte) |
| Harsha Gwalani | University Of North Texas | [Spatial Partitioning: From Macro To Nano Scale](#harsha-gwalani) |
| Brianna B. Posadas | University of Florida | [Crowdsourcing Big Data Applications in Agriculture](#brianna-b-posadas) |
|  Lara J. Martin | Georgia Institute of Technology | [Using Storytelling to Understand the Technological and Experiential Requirements of Interactive Improvisational Agents](#lara-j-martin) | 


#### Saoni Mukherjee
Graphic Processing Units (GPUs) are able to accelerate a wide range of applications. Given the massive number of compute cores on these devices, GPUs have become an attractive platform to accelerate security and cryptography applications. While performance is an important quality to prevent online attacks, current accelerators are ill-equipped to protect against side-channel attacks. This class of attacks exploits the physical implementation of a cryptographic algorithm, rather than the inherent theoretical weaknesses of the algorithm. Power modeling of GPU devices has been well studied by the computer architecture community. It has been shown that by recording the amount of energy consumed by a GPU during encryption or decryption, an attacker can capture secret information. If we can understand how the underlying microarchitecture leaks side-channel information to an attacker, we can build much more robust obfuscation approaches. In this thesis, our aim is not to build yet another GPU power model. Instead, we deliver GIPSim, a framework to enable security researchers to reason about side-channel leakage present in the context of a GPU execution-driven simulator. We show how researchers can capture detailed power estimates while running CUDA programs on a Kepler-family GPU and use the information to obfuscate power by adding noise to the power estimate. This, in turn, reduces the vulnerability present in this context. Our goal is to design a system that can thwart side-channel attacks. We demonstrate that we can model data-dependent power dissipation, capturing the hamming distance of data values used during the execution of AES encryption. This same approach is used in power-based side-channel attacks. GIPSim is one of the first simulation environments that can be used for evaluating power side-channel resiliency and help build a more secure system.

#### Jomara Sandbulte
Researchers in HCI have investigated the family realm and how family members have used technology in different contexts including health care. Though the literature has explored different strategies to support families, more research is necessary to better support intergenerational families on healthy living. We argue that our work could be broadly applicable to HCI researchers interested in how families collaborate to achieve health goals. In this research proposal, we turn our focus towards intergenerational interactions between non-collocated elderly parents and adult children. We aim to complement previous HCI research by examining how technological solutions can support intergenerational family members on active living. For this dissertation, we have conducted two rounds of qualitative studies that informed the design of a solution of an intergenerational health collaboration system within the family. Our goal is to ultimately empower family members in their efforts to promote healthy behaviors within their families.

#### Harsha Gwalani
Spatial partitioning is the process of dividing an n-dimensional space into non-overlapping sub-regions. This research aims to use spatial partitioning algorithms in two different problem domains: resource distribution for emergency response plans and compositional analysis of alloys. For optimal distribution of prophylactics during a bio-emergency, locations of ad-hoc clinics or service centers need to be identified and the population demand needs to be distributed between them such that the entire affected population is served as soon as possible and demand constraints at the clinics are satisfied. For the scenario in which locations of the ad-hoc clinics are already known, we present a novel greedy heuristic algorithm to balance the demand across the facilities. If the locations are not known, then the problem is translated into a p-median problem and solved using existing heuristic or meta-heuristic, which is selected based on the input parameters. In the second problem, we aim to use spatial partitioning algorithms to analyze the atomic composition of alloys. The properties exhibited by alloys are dictated by the concentration, type, and arrangement of atoms in the material. A new binning algorithm, the Uniform Partitioning Algorithm(UPA) is proposed to perform frequency distribution analyses and detect heterogeneities in the material. UPA is shown to be more efficient in capturing spatial correlations than existing algorithms. This research demonstrates various algorithms to store and manipulate two and three-dimensional spatial data. These methods are being used to assist public health planners to create feasible emergency response plans, and material scientists to establish correlations between microstructures in materials and their functional/physical properties.

#### Brianna B. Posadas
Big data has become an integral aspect of precision agriculture and modern farming in the United States. While farmers have been collecting data about various conditions of their farm for decades, new technologies have been able to store, analyze, and create new software from the data to help farmers make better predictions about their yields and better manage their farm. One of the challenges of using big data in agriculture is the dependence on people to create the ground truth data, or geophysical parameter data, to create the training data for precision agriculture machine learning algorithms. As it has become cheaper and easier to collect aerial images and other remote sensing data, it is still vital that someone physically inspect the area to identify the target, i.e. identify the vegetation, disease, or pest of interest. Ground truthing requires a lot of labor that farmers and researchers alone cannot satisfy. A solution to alleviating the labor shortage is to crowdsource the ground truthing. Other crowdsourcing techniques have been used to help train machine learning algorithms to identify plants and assist in discovering protein folding techniques. This dissertation will generate a prototype to 1) teach the user about the desired characteristics to be identified or “ground truthed” 2) direct the user to GPS coordinates 3) allow the user to make a real-world classification and report it and 4) allow for the user to verify classifications of other users to ensure data quality.

#### Lara J. Martin
Games research has been pushing the boundaries of what Artificial Intelligence can do and beating expert players at their respective games. The next important challenge is improvisational storytelling in open worlds. Storytelling is an important form of human communication, yet it is often missing in conversational agents. While older storytelling systems were constrained in the types of stories that they could tell, state-of-the-art storytelling systems often favor grammatical sentences over coherence. My approach uses linguistic features to abstract sentences into an event representation and addresses causality through a "bootstrapped" deep reinforcement learner (DRL). By separating events from the surface level of the sentence, I concentrate on coherence separately from grammar and provide a flexible, low-level representation which increases the types of stories told. The DRL steers the story toward a specified goal while pulling in external information to determine what events are valid. My thesis combines classical & neural AI methods and looks at how they improve improvisational story generation. Specifically, I look at the generation of event sequences, using human feedback and automated metrics to determine the quality of the story plots.

