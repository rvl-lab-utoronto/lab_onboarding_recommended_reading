# Required reading materials to start research at RVL
A curated collection of papers and research materials that students need to be aware of when they are getting started with research in the lab. They are categorized here in terms of topics:

## HOW TO MOVE

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

## HOW TO SIMULATE
All of these course are about physics-based animation, how to simulate realistic motion, and how to handle contacts, deformable objects. 
* [UofT](https://github.com/dilevin/CSC2549-physics-based-animation)
* [CMU](http://graphics.cs.cmu.edu/courses/15-869-F07/)
* [Waterloo](https://cs.uwaterloo.ca/~c2batty/courses/CS888_2014/)
* [Stanford](http://graphics.stanford.edu/courses/cs348c/)

To understand some of the material in these courses you will need to understand classical physics and mechanics. A good resource is
* [Clasical physics](https://www.youtube.com/playlist?list=PL5E4E56893588CBA8) by V. Balakrishnan at IIT Madras.

## HOW TO SEE


