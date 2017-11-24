

[TOC]



# Textbook


## Robotics

#### Robotics, vision and control
- Matlab toolbox
- Foundation of robotics (representation, Time and motion)
- Mobile robots (navigation, localization)
- Manipulator robot (Kinematics, dynamics)
- Computer vision (image processing, feature extraction)
- Vision based control (visual servoing)

- Features: 
  - Good textbook, color, figure, examples
  - Matlab toolbox: http://www.petercorke.com/RVC

## Math

#### Springer handbook of Math
- from Math ABC to functional analysis
- Chapter for variation calculus, statistics
- Easy to lookup
- Clear and approachable explanation, not hard to follow
- With examples

## AI

####  Handbook of computational intelligence

__Content Overview__ 
- Fuzzy logic
  - An approach to computer based on "degrees of truth", rather than the usual "true or false" logic which modern computer is based
  - Seems closer to the way brain works
    - We aggregate data and form a number of partial truths which we aggregate further into higher truths which in turn, when certain thresholds are exceeded, cause certain further results such as motor reaction.
- Rough set
- Neural networks
- Evolutionary computation (genetic algorithm)
  - A genetic algorithm (GA) is a method for solving both constrained and unconstrained optimization problems based on a natural selection process that mimics biological evolution.
  - Algorithm
    - The algorithm repeatedly modifies a population of individual solutions.
    - At each step, the genetic algorithm randomly selects individuals from the current population and uses them as parents to produce the children for the next generation.
    - Over successive generations, the population "evolves" toward an optimal solution.
    - https://www.mathworks.com/discovery/genetic-algorithm.html

- Swarm intelligence
  - SI systems consist typically of a population of simple agents or boids interacting locally with one another and with their environment. The inspiration often comes from nature, especially biological systems.
  - The agents follow very simple rules, and although there is no centralized control structure dictating how individual agents should behave, local, and to a certain degree random, interactions between such agents lead to the emergence of "intelligent" global behavior, unknown to the individual agents.
    Examples in natural systems of SI include ant colonies, bird flocking, animal herding, bacterial growth, fish schooling and microbial intelligence.
- Hybrid system
  - A hybrid system is a dynamical system that exhibits both continuous and discrete dynamic behavior – a system that can both flow (described by a differential equation) and jump (described by a state machine or automaton).
  - Often, the term "hybrid dynamical system" is used, to distinguish over hybrid systems such as those that combine neural nets and fuzzy logic, or electrical and mechanical drivelines.
  - A hybrid system has the benefit of encompassing a larger class of systems within its structure, allowing for more flexibility in modeling dynamic phenomena.
  - In general, the state of a hybrid system is defined by the values of the continuous variables and a discrete mode. The state changes either continuously, according to a flow condition, or discretely according to a control graph.

- Very interesting, collection of algorithms

## Control

### Introduction to Control Theory

#### An Introduction to Control Theory Applications with Matlab (2015)

https://www.researchgate.net/publication/281374146_An_Introduction_to_Control_Theory_Applications_with_Matlab

#### Feedback Systems: An Introduction for Scientists and Engineers (2008)

Karl J. Astrom; Richard M. Murray
http://www.cds.caltech.edu/~murray/books/AM08/pdf/am08-complete_28Sep12.pdf

#### Mathematical Systems Theory I – Modelling, State Space Analysis, Stability and Robustness (2005)

https://link.springer.com/book/10.1007%2Fb137541

### Optimal Control theory

#### Optimal Control (2016)

Authors: Leonid T. Aschepkov,

#### Optimal Control with Engineering Applications

https://link.springer.com/book/10.1007%2F978-3-540-69438-0

#### Principles of Optimal Control - MIT course

https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-323-principles-of-optimal-control-spring-2008/lecture-notes/


## Optimization

#### Engineering Optimization: Theory and Practice 4th Edition (2009)

by Singiresu S. Rao (Author)
http://dl.hieng.ir/bot/165287498_1498287980.pdf



## Mechatronics

#### The mechatronics handbook

http://www.profesaulosuna.com/data/files/ELECTRONICA/CIRCUITOS%20MECATRONICOS/The.Mechatronics.Handbook.pdf


## Motion Study

### Handbook of Biomechanics and Human Movement Science

https://link.springer.com/book/10.1007%2F978-1-4614-8576-6
Notes: undergrad textbook

------

# Tutorial

## Control

### Optimal Control

#### Approximate solution of linear optimal control problem with fixed ends (2017)

https://www.ripublication.com/gjpam17/gjpamv13n5_07.pdf

#### Lecture Notes - Optimal and Learning Control for Autonomous Robots - ETH

https://arxiv.org/abs/1708.09342

http://www.adrl.ethz.ch/doku.php/adrl:education:lecture

#### Control System Advanced Methods, Second Edition

http://197.14.51.10:81/pmb/CHIMIE/The%20Control%20Handbook%20Second%20Edition.pdf


## Math

### Probabilistic Theory

#### Technical Introduction: A primer on probabilistic inference
https://cocosci.berkeley.edu/tom/papers/tutorial.pdf
https://cloudfront.escholarship.org/dist/prd/content/qt66k020gh/qt66k020gh.pdf

#### Probabilistic inference for solving (PO) MDPs
https://pdfs.semanticscholar.org/d557/62d364e9ccc8aab12f0fe698efa607cf01b6.pdf
Bayesian Reasoning and Machine Learning
http://web4.cs.ucl.ac.uk/staff/D.Barber/textbook/090310.pdf

### Formal Method

#### An Overview of Formal Methods Tools and Techniques - Springer
https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=16&cad=rja&uact=8&ved=0ahUKEwjJ56uhyInWAhXM2SYKHdFlCCoQFgh7MA8&url=http%3A%2F%2Fwww.springer.com%2Fcda%2Fcontent%2Fdocument%2Fcda_downloaddocument%2F9780857290175-c2.pdf%3FSGWID%3D0-0-45-1053837-p174029011&usg=AFQjCNEnQM6bNXc1B43YnzMfNJcqPDkX7w

#### Matlab formal method - Formal methods apply theoretical computer science fundamentals to solve difficult problems in software, such as proving that software will not fail with a run-time error 
https://www.mathworks.com/discovery/formal-methods.html

## Motion planning

### Trajectory planning

#### Trajectory Planning in Robotics
https://link.springer.com/article/10.1007/s11786-012-0123-8

#### Slies: Trajectory planning
https://www.dis.uniroma1.it/~deluca/rob1_en/13_TrajectoryPlanningJoints.pdf

#### Planning algorithm - Ch14
http://planning.cs.uiuc.edu/ch14.pdf

#### Trajectory planning for manipulator robot
http://www-lar.deis.unibo.it/people/cmelchiorri/Files_Robotica/FIR_07_Traj_1.pdf

## Motion Force Controller

### PD control
#### PD control with on-line gravity compensation for robots with elastic joints (2005)
https://www.dis.uniroma1.it/~labrob/pub/papers/Automatica05_PDEJ.pdf
#### Learning Gravity Compensation in Robots (1993, tutorial)
http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.536.8651&rep=rep1&type=pdf
#### PD Control with Gravity Compensation (2005, advanced textbook)
https://link.springer.com.ezproxy.wpi.edu/content/pdf/10.1007%2F1-85233-999-3_9.pdf

### Gravity Compensation

#### Passive gravity compensation mechanism
http://ieeexplore.ieee.org.ezproxy.wpi.edu/stamp/stamp.jsp?arnumber=131834
#### A New Energy-free Gravity-compensation Adaptive System
http://www.iftomm2015.tw/IFToMM2015CD/PDF/OS13-038.pdf
#### A novel mechanism design for gravity compensation in three dimensional space
http://ieeexplore.ieee.org.ezproxy.wpi.edu/stamp/stamp.jsp?arnumber=1225089
#### Gravity Compensation, Static Balancing and Dynamic Balancing of Parallel Mechanisms
https://link.springer.com.ezproxy.wpi.edu/content/pdf/10.1007%2F978-1-84800-147-3_2.pdf

##  Sensing

### EMG

The ABC of EMG
http://bme2.aut.ac.ir/~towhidkhah/MotorControl/Notes/EMG.pdf



## Coding

### ROS

#### Learning ROS for Robotics Programming

http://www.ict.griffith.edu.au/~vlad/teaching/robotics.d/READINGS/Learning%20ROS%20for%20Robotics%20Programming%20[eBook].pdf

#### ROS by example

http://files.cnblogs.com/files/cv-pr/ros_by_example_vol1_indigo.pdf
http://files.cnblogs.com/files/cv-pr/ros_by_example_vol2_indigo.pdf