# Recommended reading materials to start research at RVL
A curated collection of papers and research materials that students need to be aware of when they are getting started with research in the lab. Students are not expected to read all of them, only the resources that are most related to their work. They are categorized here in terms of topics:


<br/>

## Robotics and ML Seminar Series
[UofT Robotics Institute Seminar Series](https://www.youtube.com/playlist?list=PLVWCqm4X2vZYsiSxf0auCRvgK97YDyZuX)
[MIT Robotics Seminars](https://www.youtube.com/@MITRoboticsSeminar)
[Robotics Today](https://www.youtube.com/@RoboticsTodaySeminar)
[MIT Embodied Intelligence](https://www.youtube.com/@mitembodiedintelligence8675)
[CMU Robotics Seminars](https://www.youtube.com/@cmurobotics)
[CMU AI Seminars](https://www.youtube.com/@cmuaiseminar1950)
[Montreal Robotics](https://www.youtube.com/@MontrealRobotics)
[UPenn GRASP Lab Seminars](https://www.youtube.com/@grasplab)
[ETH Zurich Autonomy Talks](https://www.youtube.com/@autonomytalks)
[Vector Institute Visitor Talks](https://www.youtube.com/playlist?list=PLc9Df8nOsXg6QvnoL5DPZc-fHft20SiH4)
[Control meets learning seminar series](https://www.youtube.com/@controlmeetslearning)
[RL Theory Seminars, virtual](https://sites.google.com/view/rltheoryseminars)



## HOW TO MOVE

<img src="https://github.com/rvl-lab-utoronto/lab_onboarding_recommended_reading/blob/master/motionplanning.png" width="30%">

### Motion Planning
Week 5, Motion Planning, from Florian's [CSC477](http://www.cs.toronto.edu/~florian/courses/csc477_fall19/)  

Steve Lavalle's [book](http://lavalle.pl/planning/book.html) is the go-to reference in this field. 

[LazySP](https://arxiv.org/abs/1710.04101)

Sidd Srinivasa's [talk](https://www.youtube.com/watch?v=adrVlZegiR0) 

[Informed RRT*](https://arxiv.org/abs/1404.2334)

[BIT*](https://ieeexplore.ieee.org/abstract/document/7139620)

### Task and Motion Planning 

[Hierarchical TAMP in the now](http://people.csail.mit.edu/lpk/papers/hpn2.pdf)

[Logic Geometric Programming and differentiable modes](http://roboticsproceedings.org/rss14/p44.pdf)

[PDDLStream](https://arxiv.org/abs/1802.08705)

### Control theory and learning
Week 3, PID Control, from Florian's [CSC477](http://www.cs.toronto.edu/~florian/courses/csc477_fall19/)

Week 4, LQR, from Florian's [CSC477](http://www.cs.toronto.edu/~florian/courses/csc477_fall19/)

Lecture 2 on LQR, iterative LQR, and model-based RL, from Florian's [grad course](http://www.cs.toronto.edu/~florian/courses/imitation_learning/)  

[Underactuated robotics course at MIT](https://www.youtube.com/channel/UChfUOAhz7ynELF-s_1LPpWg/playlists), 2020 version, from Russ Tedrake. Also check out his [online book](http://underactuated.mit.edu/underactuated.html) on the same topic. 

All of Steve Brunton's [videos](https://www.youtube.com/channel/UCm5mt-A4w61lknZ9lCsZtBw/playlists) on learning for control are interesting, but the following playlists in particular are worth understanding: 
* [Koopman Analysis](https://www.youtube.com/watch?v=K5CRbC4yqnk&list=PLMrJAkhIeNNSVXUvppZTYNHKQUD-oWys9), which turns nonlinear dynamics problems into linear. 
* [Data-Driven Dynamical Systems](https://www.youtube.com/watch?v=Kap3TZwAsv0&list=PLMrJAkhIeNNR6DzT17-MM1GHLkuYVjhyt), which presents techniques for learning dynamical systems from data
* [Data-Driven Control](https://www.youtube.com/watch?v=oulLR06lj_E&list=PLMrJAkhIeNNQkv98vuPjO2X2qJO_UPeWR), which presents techniques for learning controllers from data, using learned dynamical systems.

Jean Jacques Slotine's [grad course on nonlinear control](http://web.mit.edu/nsl/www/videos/lectures.html). It covers stability and convergence of nonlinear systems, adaptive control, system identification, and when can you approximate a nonlinear system by a linear system.

Nikolai Matni's [grad course on learning and control](https://nikolaimatni.github.io/courses/ese680-fall2019/index.html)

Advanced [dynamics course from Zac Manchester](https://www.youtube.com/playlist?list=PLZnJoM76RM6ItAfZIxJYNKdaR_BobleLY) 

[AA 203: Optimal and Learning-Based Control](http://asl.stanford.edu/aa203/)

[Control meets learning seminar series](https://sites.google.com/view/control-meets-learning/) and the associated [Youtube channel](https://www.youtube.com/@controlmeetslearning)

[gradSim (differentiable physics and rendering)](https://openreview.net/forum?id=c_E8kFWfhp0&noteId=c_E8kFWfhp0) for system identification


### Manipulation Robotics

[Robotic Manipulation, Russ Tedrake](https://manipulation.csail.mit.edu/index.html)

[Topics in Advanced Robotic Manipulation, Jeannette Bohg](http://web.stanford.edu/class/cs326/)

[Advanced Robotic Manipulation, Oussama Khatib](https://www.ce.cit.tum.de/fileadmin/w00cgn/rm/pdf/AdvancedRoboticManipulation.pdf)

[Learning for Adaptive and Reactive Robot Control: A Dynamical Systems Approach](https://mitpress.mit.edu/9780262046169/), by Aude Billard, Sina Mirrazavi, Nadia Figueroa

### Imitation learning
Florian's [imitation learning seminar course](http://www.cs.toronto.edu/~florian/courses/imitation_learning/). Look at the slides. 

Yisong Yue's [imitation learning talk](https://www.youtube.com/watch?v=QW0I10a2T54&ab_channel=ControlMeetsLearning)

### Reinforcement learning
[RL course at UCL](https://www.davidsilver.uk/teaching/), by David Silver. Check out the slides and youtube videos. This course is good for discrete RL in games like chess and Go, so definitely not tailored to robotics.

[Deep RL course at Berkeley](http://rail.eecs.berkeley.edu/deeprlcourse/), by Sergey Levine. Check out the youtube videos. This course is good for both discrete and continuous state and action RL, so it is applicable to robotics.

What is a good state representation/encoding for RL? See these papers and their related works to get started: 
* https://arxiv.org/abs/2207.08229 (state encoding should be predictive of the next action in a multi-step inverse dynamics model)
* https://arxiv.org/abs/2212.14511 (state encoding should be predictive of rewards)
* https://arxiv.org/abs/1811.04551 (state encoding should be predictive of next states, rewards, and able to reconstruct observations)

[Exploration strategies in deep RL](https://lilianweng.github.io/posts/2020-06-07-exploration-drl/)

Monotonic improvement in model-based RL: see https://arxiv.org/abs/1807.03858 and https://arxiv.org/abs/1805.10755 

[RL Theory Seminars, virtual](https://sites.google.com/view/rltheoryseminars)

[Lessons from AlphaZero for Optimal, Model-Predictive, and Adaptive Control (Bertsekas)](https://web.mit.edu/dimitrib/www/LessonsfromAlphazero.pdf)





### Learning to plan/search
These courses are about having controllers/policies/planning algorithms that get better over time, as they solve more problems. These two courses are unique in the world and very much bleeding edge.

David Duvenaud's [seminar course](https://duvenaud.github.io/learning-to-search/). Combining Monte Carlo Tree Search with neural networks, learning from expensive algorithms.

Yisong Yue's [seminar course](https://sites.google.com/view/cs-159-spring-2020/home). Learning for branch and bound optimizers, learning A* heuristics. Lots of good stuff here.



### Safety considerations in learning for control
Scaling probabilistically safe imitation learning, Scott Niekum, [online talk](https://bluejeans.com/playback/s/zOSHqyZzGhSdPRQPl0448lckmbprGAmzQoTUKOGB5xjntbBZji0GHw2yZelRFH7K), which can also be found [here](https://youtu.be/slGmQv_pWs0).

Safe Learning MPC, by Melanie Zeilinger, [online talk](https://www.sciencedirect.com/science/article/pii/S1367578817301232)

Safety-critical continuous and discrete-continuous systems, by Aaron Ames, [online talk](https://www.youtube.com/watch?v=ZC3T_P_8xpE&ab_channel=InstituteforPure%26AppliedMathematics%28IPAM%29)

Backwards reachability for control, via the Hamilton-Jacobi-Bellman equation [survey paper](https://arxiv.org/abs/1709.07523) and [tutorial](https://www.youtube.com/watch?v=iWsfc107nRc). Note that these approaches do not scale in more than 10-15 dimensions.

Introduction to reachability for linear systems, [a tutorial](http://www.dii.unimo.it/~zanasi/didattica/Teoria_dei_Sistemi/Luc_TDS_ING_2016_Reachability_and_Controllability.pdf).

How should a robot assess risk? Towards an axiomatic theory of risk in robotics, by Anirudha Majumdar. [paper](http://asl.stanford.edu/wp-content/papercite-data/pdf/Majumdar.Pavone.ISRR17.pdf) 

A [survey paper](http://jmlr.org/papers/v16/garcia15a.html) on safe RL

Constrained Policy Optimization [paper](https://arxiv.org/abs/1705.10528)

[Conservative Safety Critics for Exploration](https://openreview.net/forum?id=iaO86DUuKi)




### Active learning and information gathering behaviors

Roger Grosse's seminar [course](https://csc2541-f17.github.io/) on uncertainty modeling and active learning

[VIME: Variational Information Maximizing Exploration](https://arxiv.org/abs/1605.09674)

<br/>

## HOW TO SIMULATE MOTION AND PERCEPTION

<img src="https://github.com/rvl-lab-utoronto/lab_onboarding_recommended_reading/blob/master/deepmimic.jpg" width="60%">

### Physics-based animation
All of these course are about physics-based animation, how to simulate realistic motion, and how to handle contacts, deformable objects. 
* [UofT](https://github.com/dilevin/CSC2549-physics-based-animation)
* [CMU](http://graphics.cs.cmu.edu/courses/15-869-F07/)
* [Waterloo](https://cs.uwaterloo.ca/~c2batty/courses/CS888_2014/)
* [Stanford](http://graphics.stanford.edu/courses/cs348c/)

To understand some of the material in these courses you will need to understand classical physics and mechanics. A good resource is
* [Classical physics](https://www.youtube.com/playlist?list=PL5E4E56893588CBA8) by V. Balakrishnan at IIT Madras.

[DiffTaichi: Differentiable Programming for Physical Simulation](https://arxiv.org/abs/1910.00935)

[Awesome multibody dynamics simulation](https://github.com/jslee02/awesome-multibody-dynamics-simulation)

### Sim-to-real and real-to-sim transfer

[The frontier of simulation-based inference](https://arxiv.org/abs/1911.01429)

[BayesSim: adaptive domain randomization via probabilistic inference for robotics simulators](https://arxiv.org/abs/1906.01728)

Domain randomization [blog post](https://lilianweng.github.io/lil-log/2019/05/05/domain-randomization.html)

[Neural ODEs](https://arxiv.org/abs/1806.07366)

### Differentiable rendering

[NeRF: neural radiance fields](http://www.matthewtancik.com/nerf)

[3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/)

[Learning to Predict 3D Objects with an Interpolation-based Differentiable Renderer](https://arxiv.org/abs/1908.01210)

[Soft Rasterizer: A Differentiable Renderer for Image-based 3D Reasoning](https://arxiv.org/abs/1904.01786)

[DIB-R](https://nv-tlabs.github.io/DIB-R/) 

Mitsuba2: A Retargetable Forward and Inverse Renderer [paper](https://rgl.epfl.ch/publications/NimierDavidVicini2019Mitsuba2) 


### Scene representation
[Scene representation networks](https://arxiv.org/abs/1906.01618)

[Neural scene representation and rendering](https://deepmind.com/blog/article/neural-scene-representation-and-rendering)

[Neural point based graphics](https://saic-violet.github.io/npbg/)

[SCALOR: Generative World Models with Scalable Object Representations](https://arxiv.org/abs/1910.02384)

[Generative Hierarchical Models for Parts, Objects, and Scenes](https://arxiv.org/abs/1910.09119)

[SPACE: Unsupervised Object-Oriented Scene Representation via Spatial Attention and Decomposition](https://arxiv.org/abs/2001.02407)

[Animesh Garg's graduate seminar course on 3D and Geometric Deep Learning](https://www.pair.toronto.edu/csc2547-w21/)


<br/>

## HOW TO SEE

<img src="https://github.com/rvl-lab-utoronto/lab_onboarding_recommended_reading/blob/master/thermorathaus.jpg" width="30%">

### Merging LiDAR pointclouds and RGB image representations
[Joint 3D Proposal Generation and Object Detection from View Aggregation](https://arxiv.org/abs/1712.02294)

[Multi-View 3D Object Detection Network for Autonomous Driving](https://arxiv.org/abs/1611.07759)

### Pointcloud representations
[PointFlow: 3D Point Cloud Generation with Continuous Normalizing Flows](https://arxiv.org/abs/1906.12320)

[PointNetVLAD: Deep Point Cloud Based Retrieval for Large-Scale Place Recognition](https://arxiv.org/abs/1804.03492)

[SE(3)-Transformers: 3D Roto-Translation Equivariant Attention Networks](https://arxiv.org/abs/2006.10503)

### Contrastive representation learning and similarity search
[One-Shot Informed Robotic Visual Search in the Wild](https://arxiv.org/abs/2003.10010). See the related works section.

[A Metric Learning Reality Check](https://arxiv.org/abs/2003.08505)

[A Theoretical Analysis of Contrastive Unsupervised Representation Learning](https://arxiv.org/abs/1902.09229)

[Understanding Contrastive Representation Learning through Alignment and Uniformity on the Hypersphere](https://arxiv.org/abs/2005.10242)

### Unsupervised object discovery, detection, and tracking
[SCALOR: Generative World Models with Scalable Object Representations](https://arxiv.org/abs/1910.02384)

<br/>

## STATE ESTIMATION

[State Estimation for Robotics](http://asrl.utias.utoronto.ca/~tdb/bib/barfoot_ser17.pdf), by Tim Barfoot, Professor, University of Toronto

[Bayesian Filtering and Smoothing](https://users.aalto.fi/~ssarkka/pub/cup_book_online_20131111.pdf), by Simo Sarkka, Professor, Aalto University

[Factor Graphs for Robotic Perception](http://www.cs.cmu.edu/~kaess/pub/Dellaert17fnt.pdf), by Profs. Frank Dellaert and Michael Kaess


<br/>

## GENERATIVE MODELS & INFERENCE METHODS

[Variational Inference: a Review for Statisticians](https://arxiv.org/abs/1601.00670)

Tutorials on Variational Autoencoders (VAEs): https://arxiv.org/abs/1606.05908 and https://jaan.io/what-is-variational-autoencoder-vae-tutorial/

[Deep Learning Book](https://www.deeplearningbook.org/)

[Deep Generative Modelling](https://link.springer.com/book/10.1007/978-3-030-93158-2)

[What are diffusion models?](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/)

[]

<br/>


## HOW TO WRITE EFFECTIVELY

[The art of writing effectively](https://www.youtube.com/watch?v=vtIzMaLkCaM&list=PLG5oXmrs-KA3EhXr_82Yy9dPGImBTbmuv), by Larry McEnerney, Director of the University of Chicago's Writing Program

[Writing beyond the Academy](https://www.youtube.com/watch?v=aFwVf5a3pZM&list=PLG5oXmrs-KA3EhXr_82Yy9dPGImBTbmuv&index=2), by Larry McEnerney, Director of the University of Chicago's Writing Program

<br/>

## ADVICE FOR GRADUATE STUDENTS (& their supervisors)
[Eight lessons learned in two years of PhD](https://ai.engin.umich.edu/2023/08/17/eight-lessons-learned-in-two-years-of-ph-d/), by Muhammad Khalifa, PhD student, U. Michigan

[Principles for productive group meetings](https://bounded-regret.ghost.io/principles-for-productive-group-meetings/), by Jacob Steinhardt, Assistant Professor, UC Berkeley

[How I read research papers](https://www.let-all.com/assets/slides/How-to-ALT22-Aaditya.pdf), by Aaditya Ramdas, Assistant Professor, CMU

[Principles for a PhD program](https://github.com/coallaoh/Principles/tree/main/principles/phd), by Seong Joon Oh, group leader, U. of Tuebingen 

[How to achieve success in a machine learning PhD](https://kidger.site/thoughts/just-know-stuff/), by Patrick Kidger, PhD student, Oxford.









