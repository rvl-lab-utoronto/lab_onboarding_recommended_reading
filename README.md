# Recommended reading materials to start research at RVL
A curated collection of papers and research materials that students need to be aware of when they are getting started with research in the lab. Students are definitely not expected to read all of them, but the resources that are most related to their work. They are categorized here in terms of topics:


<br/>

## HOW TO MOVE

<img src="https://github.com/rvl-lab-utoronto/lab_onboarding_recommended_reading/blob/master/motionplanning.png" width="30%">

### Planning
Week 5, Motion Planning, from Florian's [CSC477](http://www.cs.toronto.edu/~florian/courses/csc477_fall19/)  

Steve Lavalle's [book](http://lavalle.pl/planning/book.html) is the go-to reference in this field. 

### Control Theory and Learning
Week 3, PID Control, from Florian's [CSC477](http://www.cs.toronto.edu/~florian/courses/csc477_fall19/)

Week 4, LQR, from Florian's [CSC477](http://www.cs.toronto.edu/~florian/courses/csc477_fall19/)

Lecture 2 on LQR, iterative LQR, and model-based RL, from Florian's [grad course](http://www.cs.toronto.edu/~florian/courses/imitation_learning/)  

[Underactuated robotics course at MIT](https://www.youtube.com/channel/UChfUOAhz7ynELF-s_1LPpWg/playlists), 2020 version, from Russ Tedrake. Also check out his [online book](http://underactuated.mit.edu/underactuated.html) on the same topic. 

All of Steve Brunton's [videos](https://www.youtube.com/channel/UCm5mt-A4w61lknZ9lCsZtBw/playlists) on learning for control are interesting, but the following playlists in particular are worth understanding: 
* [Koopman Analysis](https://www.youtube.com/watch?v=K5CRbC4yqnk&list=PLMrJAkhIeNNSVXUvppZTYNHKQUD-oWys9), which turns nonlinear dynamics problems into linear. 
* [Data-Driven Dynamical Systems](https://www.youtube.com/watch?v=Kap3TZwAsv0&list=PLMrJAkhIeNNR6DzT17-MM1GHLkuYVjhyt), which presents techniques for learning dynamical systems from data
* [Data-Driven Control](https://www.youtube.com/watch?v=oulLR06lj_E&list=PLMrJAkhIeNNQkv98vuPjO2X2qJO_UPeWR), which presents techniques for learning controllers from data, using learned dynamical systems.

Jean Jacques Slotine's [grad course on nonlinear control](http://web.mit.edu/nsl/www/videos/lectures.html). It covers stability and convergence of nonlinear systems, adaptive control, system identification, and when can you approximate a nonlinear system by a linear system.

### Imitation Learning
Florian's [imitation learning seminar course](http://www.cs.toronto.edu/~florian/courses/imitation_learning/). Look at the slides. 

### Reinforcement Learning
[RL course at UCL](https://www.davidsilver.uk/teaching/), by David Silver. Check out the slides and youtube videos. This course is good for discrete RL in games like chess and Go, so definitely not tailored to robotics.

[Deep RL course at Berkeley](http://rail.eecs.berkeley.edu/deeprlcourse/), by Sergey Levine. Check out the youtube videos. This course is good for both discrete and continuous state and action RL, so it is applicable to robotics.

### Learning to Plan/Search
These courses are about having controllers/policies/planning algorithms that get better over time, as they solve more problems. These two courses are unique in the world and very much bleeding edge.

David Duvenaud's [seminar course](https://duvenaud.github.io/learning-to-search/). Combining Monte Carlo Tree Search with neural networks, learning from expensive algorithms.

Yisong Yue's [seminar course](https://sites.google.com/view/cs-159-spring-2020/home). Learning for branch and bound optimizers, learning A* heuristics. Lots of good stuff here. 

### Safety Considerations in Learning for Control
Scaling probabilistically safe imitation learning, Scott Niekum, [online talk](https://bluejeans.com/playback/s/zOSHqyZzGhSdPRQPl0448lckmbprGAmzQoTUKOGB5xjntbBZji0GHw2yZelRFH7K), which can also be found [here](https://youtu.be/slGmQv_pWs0).

Backwards reachability for control, via the Hamilton-Jacobi-Bellman equation [survey paper](https://arxiv.org/abs/1709.07523) and [tutorial](https://www.youtube.com/watch?v=iWsfc107nRc). Note that these approaches do not scale in more than 10-15 dimensions.

Introduction to reachability for linear systems, [a tutorial](http://www.dii.unimo.it/~zanasi/didattica/Teoria_dei_Sistemi/Luc_TDS_ING_2016_Reachability_and_Controllability.pdf).

How should a robot assess risk? Towards an axiomatic theory of risk in robotics, by Anirudha Majumdar. [paper](http://asl.stanford.edu/wp-content/papercite-data/pdf/Majumdar.Pavone.ISRR17.pdf) 


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
* [Clasical physics](https://www.youtube.com/playlist?list=PL5E4E56893588CBA8) by V. Balakrishnan at IIT Madras.

DiffTaichi: Differentiable Programming for Physical Simulation, https://arxiv.org/abs/1910.00935

### Sim-to-real and real-to-sim transfer

The frontier of simulation-based inference, https://arxiv.org/abs/1911.01429

BayesSim: adaptive domain randomization via probabilistic inference for robotics simulators, https://arxiv.org/abs/1906.01728

Domain randomization [blog post](https://lilianweng.github.io/lil-log/2019/05/05/domain-randomization.html)

Neural ODEs, https://arxiv.org/abs/1806.07366

### Differentiable rendering

Nerf: neural radiance fields, http://www.matthewtancik.com/nerf

Learning to Predict 3D Objects with an Interpolation-based Differentiable Renderer, https://arxiv.org/abs/1908.01210

Soft Rasterizer: A Differentiable Renderer for Image-based 3D Reasoning, https://arxiv.org/abs/1904.01786

### Scene representation
Scene representation networks, https://arxiv.org/abs/1906.01618

Neural scene representation and rendering, https://deepmind.com/blog/article/neural-scene-representation-and-rendering

Neural point based graphics, https://saic-violet.github.io/npbg/

SCALOR: Generative World Models with Scalable Object Representations, https://arxiv.org/abs/2001.02407

Generative Hierarchical Models for Parts, Objects, and Scenes, https://arxiv.org/abs/1910.09119

SPACE: Unsupervised Object-Oriented Scene Representation via Spatial Attention and Decomposition, https://arxiv.org/abs/2001.02407

<br/>

## HOW TO SEE

<img src="https://github.com/rvl-lab-utoronto/lab_onboarding_recommended_reading/blob/master/thermorathaus.jpg" width="30%">

### Merging LiDAR pointclouds and RGB image representations
Joint 3D Proposal Generation and Object Detection from View Aggregation, https://arxiv.org/abs/1712.02294

### Pointcloud representations
PointFlow: 3D Point Cloud Generation with Continuous Normalizing Flows, https://arxiv.org/abs/1906.12320

PointNetVLAD: Deep Point Cloud Based Retrieval for Large-Scale Place Recognition, https://arxiv.org/abs/1804.03492

### Similarity Search
One-Shot Informed Robotic Visual Search in the Wild, https://arxiv.org/abs/2003.10010 See the related works section.

A Metric Learning Reality Check, https://arxiv.org/abs/2003.08505

### Unsupervised object discovery, detection, and tracking
SCALOR: Generative World Models with Scalable Object Representations, https://arxiv.org/abs/2001.02407





