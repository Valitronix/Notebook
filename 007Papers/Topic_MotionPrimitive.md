

[TOC]

### 2017 

#### Gaussian Mixture Model for 3-DoF orientations (2017)

http://www.sciencedirect.com/science/article/pii/S0921889015302244

#### An Approach for Imitation Learning on Riemannian Manifolds (2017)

http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7829369

#### Learning and correcting robot trajectory keypoints from a single demonstration (2017)
http://ieeexplore.ieee.org/abstract/document/7942660/

Learning movement primitive libraries through probabilistic segmentation (Jan Peters, 2017)
http://journals.sagepub.com/doi/pdf/10.1177/0278364917713116



#### Using probabilistic movement primitives in robotics (2017)

https://link.springer.com/content/pdf/10.1007%2Fs10514-017-9648-7.pdf

#### Probabilistic Prioritization of Movement Primitives (ICRA 2017, Jan Peter)

http://ieeexplore.ieee.org/document/7973083/
Movement prioritization is a common approach to combine controllers of different tasks for redundant robots, where each task is assigned a priority. The priorities of the tasks are often handtuned or the result of an optimization, but seldomly learned from data. This letter combines Bayesian task prioritization with probabilistic movement primitives (ProMPs) to prioritize full motion sequences that are learned from demonstrations. ProMPs can encode distributions of movements over full motion sequences and provide control laws to exactly follow these distributions. The probabilistic formulation allows for a natural application of Bayesian task prioritization. We extend the ProMP controllers with an additional feedback component that accounts inaccuracies in following the distribution and allows for a more robust prioritization of primitives. We demonstrate how the task priorities can be obtained from imitation learning and how different primitives can be combined to solve even unseen task-combinations. Due to the prioritization, our approach can efficiently learn a combination of tasks without requiring individual models per task combination. Furthermore, our approach can adapt an existing primitive library by prioritizing additional controllers, for example, for implementing obstacle avoidance. Hence, the need of retraining the whole library is avoided in many cases. We evaluate our approach on reaching movements under constraints with redundant simulated planar robots and two physical robot platforms, the humanoid robot “iCub” and a KUKA LWR robot arm.

#### DMP and GMR based teaching by demonstration for a KUKA LBR robot (ICAC 2017)

http://ieeexplore.ieee.org/document/8081982/
This paper investigates the problem of Teaching by Demonstration (TbD) on a KUKA lightweight robot (LBR). Motions are recorded by a human operator, and then the data is used to model a nonlinear system, i.e., the dynamic motor primitive (DMP). In order to learn from multiple demonstrations, Gaussian Mixture Models (GMM) are employed rather than using conventional Gaussian process for the evaluation of the non-linear term of the DMP. Then the Gaussian mixture regression (GMR) algorithm is applied to generate a synthesized trajectory with smaller position errors in 3D space. The proposed approach is tested and demonstrated by performing two tasks with KUKA iiwa robot.

### Phase estimation for fast action recognition and trajectory generation in human–robot collaboration (IJRR,2017)
http://journals.sagepub.com/doi/abs/10.1177/0278364917693927
This paper proposes a method to achieve fast and fluid human–robot interaction by estimating the progress of the movement of the human. The method allows the progress, also referred to as the phase of the movement, to be estimated even when observations of the human are partial and occluded; a problem typically found when using motion capture systems in cluttered environments. By leveraging on the framework of Interaction Probabilistic Movement Primitives, phase estimation makes it possible to classify the human action, and to generate a corresponding robot trajectory before the human finishes his/her movement. The method is therefore suited for semi-autonomous robots acting as assistants and coworkers. Since observations may be sparse, our method is based on computing the probability of different phase candidates to find the phase that best aligns the Interaction Probabilistic Movement Primitives with the current observations. The method is fundamentally different from approaches based on Dynamic Time Warping that must rely on a consistent stream of measurements at runtime. The resulting framework can achieve phase estimation, action recognition and robot trajectory coordination using a single probabilistic representation. We evaluated the method using a seven-degree-of-freedom lightweight robot arm equipped with a five-finger hand in single and multi-task collaborative experiments. We compare the accuracy achieved by phase estimation with our previous method based on dynamic time warping.

### 2016

#### A Probabilistic Representation of Dynamic Movements Primitives (2016, Stefan Schaal)

https://arxiv.org/pdf/1612.05932.pdf
Dynamic Movement Primitives have successfully been used to realize imitation learning, trial-and-error learning, reinforcement learning, movement recognition and segmentation and control. Because of this they have become a popular representation for motor primitives. In this work, we showcase how DMPs can be reformulated as a probabilistic linear dynamical system with control inputs. Through this probabilistic representation of DMPs, algorithms such as Kalman filtering and smoothing are directly applicable to perform inference on proprioceptive sensor measurements during execution. We show that inference in this probabilistic model automatically leads to a feedback term to online modulate the execution of a DMP. Furthermore, we show how inference allows us to measure the likelihood that we are successfully executing a given motion primitive. In this context, we show initial results of using the probabilistic model to detect execution failures on a simulated movement primitive dataset.

#### A Dynamical System Approach for Softly Catching a Flying Object: Theory and Experiment (2016)

http://ieeexplore.ieee.org/abstract/document/7439839/

#### Adaptive human-inspired compliant contact primitives to perform surface–surface contact under uncertainty (2016 IJRR)

http://journals.sagepub.com/doi/abs/10.1177/0278364916648389

#### Gaussian Processes for Dynamic Movement Primitives with Application in Knowledge-based Cooperation (IROS, 2016)
http://ieeexplore.ieee.org/document/7759576/
Dynamic Movement Primitives (DMPs) represent stable goal-directed or periodic movements, which are learned from observations or demonstrations. They rely on proper function approximators, which are sufficiently flexible to represent arbitrary movements but also ensure goal convergence in point-to-point motions. This work shows that Gaussian Processes (GPs) are suitable as a regressor for learning movements with DMPs ensuring stability. In addition, GPs provide a measure for the uncertainty about the current movement, which we exploit by proposing a new cooperation scheme for DMPs: For better reproduction of demonstrations, we follow the intuition, that individuals with more knowledge lead towards the goal, while others follow and focus on cooperation. Along with simulation results, we validate the presented methods in a robotic cooperative object manipulation task.

#### Online Incremental Learning of Manipulation Tasks for Semi-Autonomous Teleoperation (IROS 2016)
http://www.ajaytanwani.com/docs/irosWS2016havoutis.pdf
We present an approach for online incremental learning of manipulation tasks. A Bayesian clustering algorithm is used to build an online
hidden semi-Markov model (HSMM) that captures state transition and state duration probabilities of demonstrated motions. Motions are then generated by stochastically sampling from the learned model and tracked using an infinite-horizon linear quadratic regulator (LQR), with varying stiffness and damping characteristics learned from the demonstrations. Our approach provides a compact skill representation that is learned online and can be used in a semi-autonomous teleoperation setting, where direct teleoperation is infeasible due to large communication latency or failure. We present a planar drawing example to highlight the flexibility of our approach, and demonstrate how our solution can be used for a hot-stabbing motion in an underwater teleoperation scenario. We evaluate the performance of our approach over multiple trials and report high accuracy and repeatability, resulting to consistently successful hot-stabbing motions.

#### Learning from demonstration with partially observable task parameters using Dynamic Movement Primitives and Gaussian Process Regression (2016, Advanced Intelligent Mechatronics (AIM))
http://ieeexplore.ieee.org/document/7576881/
The problem of learning from demonstration in the case of partially observable external task parameters is addressed in this paper. Such a situation could be present in the daily life scenarios, where information regarding some task parameters are missing or partially available. In the first step, one dynamic movement primitives (DMP) model is learned for each demonstration trajectory. The parameters of the learned DMP model are recorded together with the corresponding external task parameters (query points), to create a database. Then Gaussian process regression (GPR) is used to create a model for the external task parameters and the DMP parameters. During reproduction, DMP parameters are retrieved by providing the new external task parameters and are used to regenerate the trajectory. It is shown how the learning approach could be adapted to deal with the partially observable external task parameters and regenerate the proper trajectory. The proposed methodology is applied to learn a via-point passing experiment with a lightweight robot manipulator (KUKA robot) to illustrate the efficacy of the proposed approach.

#### Adaptive learning of dynamic movement primitives through demonstration (IJCNN, 2016)
http://ieeexplore.ieee.org/document/7727316/
Complex robotics task such as biped walking, tennis-like swing, object grasping etc, depend on state prediction, complex motion generation and stable execution of motion command. Predictions of states get more accurate over time, hence the robot behavior need to be updated continuously. Such state updates cannot be incorporated straight forwardly in most trajectory generation solutions. dynamic movement primitives (DMP) provides such a flexible formulation which can adapt to spacial and temporal variations. In this paper, we present a novel algorithm for adaptive learning of DMP that can be used to generate complex trajectories required by the robot to perform a complex task. The proposed technique uses a piece-wise linear canonical system (PLCS) instead of the standard exponential canonical system (ECS) for learning the DMP parameters. We show that the proposed PLCS learns the parameters faster and has a smaller mean squared error (MSE) as compared to ECS. Proposed learning technique coupled with PLCS uniquely learns DMP parameters as compared to other state of art techniques. The proposed technique is used to learn the primitive trajectories via imitation (learning from demonstration) and an unseen primitive is generated by a kernel based mixture model. In this paper, we present results from a real 4 degree-of-freedom (DOF) Barrett WAM robotic arm and show that the proposed system is able to hit a ball randomly thrown at it.

#### A tutorial on task-parameterized movement learning and retrieval (Springer, Intelligence service robot, 2015, Sylvain Calinon)
https://link.springer.com/article/10.1007/s11370-015-0187-9?no-access=true
Task-parameterized models of movements aim at automatically adapting movements to new situations encountered by a robot. The task parameters can, for example, take the form of positions of objects in the environment or landmark points that the robot should pass through. This tutorial aims at reviewing existing approaches for task-adaptive motion encoding. It then narrows down the scope to the special case of task parameters that take the form of frames of reference, coordinate systems or basis functions, which are most commonly encountered in service robotics. Each section of the paper is accompanied by source codes designed as simple didactic examples implemented in Matlab with a full compatibility with GNU Octave, closely following the notation and equations of the article. It also presents ongoing work and further challenges that remain to be addressed, with examples provided in simulation and on a real robot (transfer of manipulation behaviors to the Baxter bimanual robot). The repository for the accompanying source codes is available at http://www.idiap.ch/software/pbdlib/

#### Incremental Learning of Skills in a Task-Parameterized Gaussian Mixture Model (Springer, Journal of Intelligent & Robotic Systems, 2015)
https://link.springer.com/article/10.1007/s10846-015-0290-3
Programming by demonstration techniques facilitate the programming of robots. Some of them allow the generalization of tasks through parameters, although they require new training when trajectories different from the ones used to estimate the model need to be added. One of the ways to re-train a robot is by incremental learning, which supplies additional information of the task and does not require teaching the whole task again. The present study proposes three techniques to add trajectories to a previously estimated task-parameterized Gaussian mixture model. The first technique estimates a new model by accumulating the new trajectory and the set of trajectories generated using the previous model. The second technique permits adding to the parameters of the existent model those obtained for the new trajectories. The third one updates the model parameters by running a modified version of the Expectation-Maximization algorithm, with the information of the new trajectories. The techniques were evaluated in a simulated task and a real one, and they showed better performance than that of the existent model.

### 2015

#### Probabilistic progress prediction and sequencing of concurrent movement primitives (IROS, 2015, Jan Peter)
http://ieeexplore.ieee.org/document/7353411/
Classical approaches towards learning coordinated movement tasks often represent a movement in a sequential and exclusive fashion. Introducing concurrency allows to decompose such tasks into a number of separate sequences, for instance for two different end-effectors. While this results in a compact and generic representation of the individual movement primitives (MPs), it is a hard problem to learn their temporal and causal organization. This paper presents a concept for learning movement tasks that require the coordination of several controlled effectors of a robot. We firstly introduce a concept to learn and estimate the progress of individual MPs from a low number of demonstrations. Secondly, we propose a representation of the task that incorporates several concurrent sequences of MPs. Combining these two elements allows to learn and reproduce coordinated bi-manual movement tasks robustly. The synchronization of the concurrent MPs is achieved implicitly using the progress prediction. The approach is evaluated in two simulation studies with a 25 degrees of freedom two-arm robot performing a pick-and-place task

#### Learning Trajectories for Robot Programing by Demonstration Using a Coordinated Mixture of Factor Analyzers (2015)

http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7069239

### 2014

#### Coupling Movement Primitives: Interaction With the Environment and Bimanual Tasks (2014)
http://ieeexplore.ieee.org/document/6748918/
The framework of dynamic movement primitives (DMPs) contains many favorable properties for the execution of robotic trajectories, such as indirect dependence on time, response to perturbations, and the ability to easily modulate the given trajectories, but the framework in its original form remains constrained to the kinematic aspect of the movement. In this paper, we bridge the gap to dynamic behavior by extending the framework with force/torque feedback. We propose and evaluate a modulation approach that allows interaction with objects and the environment. Through the proposed coupling of originally independent robotic trajectories, the approach also enables the execution of bimanual and tightly coupled cooperative tasks. We apply an iterative learning control algorithm to learn a coupling term, which is applied to the original trajectory in a feed-forward fashion and, thus, modifies the trajectory in accordance to the desired positions or external forces. A stability analysis and results of simulated and real-world experiments using two KUKA LWR arms for bimanual tasks and interaction with the environment are presented. By expanding on the framework of DMPs, we keep all the favorable properties, which is demonstrated with temporal modulation and in a two-agent obstacle avoidance task.

#### Statistical Learning of Task Modulated Human Movements Through Demonstration (2014, Thesis)
https://www.researchgate.net/profile/Tohid_Alziadeh/publication/276898289_Statistical_Learning_of_Task_Modulated_Human_Movements_Through_Demonstration/links/555b1f0b08ae6943a87873cf.pdf
Making the robots to be well integrated into the domestic environments is one of the challenging issues in the robotics field of research. There are several aspects concerning this issue, one of which is the difficulty in the interaction with and programming the robots. Manually programming a robot is a complex and tedious job. One way to make the programming a robot easier is to use programming by demonstration techniques. It would be much more convenient to just show the robot what to do, and for the robot to learn and imitate the required behaviour automatically. In this way, the end user does not need to be an expert in robotics or programming. The problem of teaching a robot to learn a task is considered in this thesis. There are several approaches to solve such a problem, however, the approaches which are investigated and developed in this thesis are mainly statistical approaches. Special effort is given here to the tasks for which the movement is modulated by some task parameters. This makes the developed approaches to encompass bigger family of the tasks. Task-parameterized Gaussian mixture model (TP-GMM) is proposed as a solution of the problem, eventually. The proposed approach has better generalization properties compared to other similar methods. Even though the TP-GMM offers a suitable solution for the problem, it still has its own limitation. One of the main limitations which is tackled in this thesis is the lack of information in the task parameters. Evolving another step ahead, the case of partially observable task parameters is investigated and the proposed approach is modified in order to take into account the availability of the task parameters. This increases the generalization property of the approach in some sense, making the approach even more suitable for practical scenarios, in which not all the needed information, regarding the task parameters, are available all the time. The proposed approaches are evaluated using real world experiments with robotic platforms. Dynamic movement primitives (DMP) have been used extensively in the filed of learning by imitation. Mixture models are proposed to act as the core of dynamic movement primitives. By using mixture models instead of the conventional LWR approaches for learning a DMP, several advantages are achieved, including the reduced complexity of the model.

#### One-shot robot programming by demonstration using an online oriented particles simulation (Robotics and Biomimetics ROBIO, 2014)
http://ieeexplore.ieee.org/document/7090323/
To provide robots for a wide range of users, there needs to be an easy and intuitive way to program them. This issue is addressed by the robot programming by demonstration paradigm, where the user demonstrates the task to the robot. While there exist a lot approaches that use multiple demonstrations for the learning procedure, single-shot robot programming by demonstration is still a niche. Also, all available approaches in this niche have severe drawbacks. The main contribution of this work is a novel one-shot programming by demonstration approach, that performs an online adaption of a provided trajectory to a new situation. For that, the system regards every sample of the trajectory and every reference (object) in the scene as a particle. These particles interfere with each other by forces and torques that arise from inherent potential fields. Thus, in a new situation the trajectory will adapt to the potential fields of the relocated references and converge to a minimum energy state. We evaluated the approach qualitatively and quantitatively using cross validation.

#### A task-parameterized probabilistic model with minimal intervention control (ICRA 2014, Sylvain Calinon)
http://ieeexplore.ieee.org/abstract/document/6907339/
We present a task-parameterized probabilistic model encoding movements in the form of virtual spring-damper systems acting in multiple frames of reference. Each candidate coordinate system observes a set of demonstrations from its own perspective, by extracting an attractor path whose variations depend on the relevance of the frame at each step of the task. This information is exploited to generate new attractor paths in new situations (new position and orientation of the frames), with the predicted covariances used to estimate the varying stiffness and damping of the spring-damper systems, resulting in a minimal intervention control strategy. The approach is tested with a 7-DOFs Barrett WAM manipulator whose movement and impedance behavior need to be modulated in regard to the position and orientation of two external objects varying during demonstration and reproduction.

### 2013

#### Dynamic Movement Primitives for Human-Robot interaction: Comparison with human behavioral observation (2013)
http://ieeexplore.ieee.org/abstract/document/6696498/

#### Probabilistic Movement Primitives (NIPS 2013)
http://papers.nips.cc/paper/5177-probabilistic-movement-primitives
Movement Primitives (MP) are a well-established approach for representing modular and re-usable robot movement generators. Many state-of-the-art robot learning successes are based MPs, due to their compact representation of the inherently continuous and high dimensional robot movements. A major goal in robot learning is to combine multiple MPs as building blocks in a modular control architecture to solve complex tasks. To this effect, a MP representation has to allow for blending between motions, adapting to altered task variables, and co-activating multiple MPs in parallel. We present a probabilistic formulation of the MP concept that maintains a distribution over trajectories. Our probabilistic approach allows for the derivation of new operations which are essential for implementing all aforementioned properties in one framework. In order to use such a trajectory distribution for robot movement control, we analytically derive a stochastic feedback controller which reproduces the given trajectory distribution. We evaluate and compare our approach to existing methods on several simulated as well as real robot scenarios.

### 2012

#### Movement Segmentation and Recognition for Imitation Learning (2012, Stefan Schaal)
http://proceedings.mlr.press/v22/meier12/meier12.pdf
In human movement learning, it is most common to teach constituent elements of complex movements in isolation, before chaining them into complex movements. Segmentation and recognition of observed movement could thus proceed out of this existing knowledge, which is directly compatible with movement generation. In this paper, we address exactly this scenario. We assume that a library of movement primitives has already been taught, and we wish to identify elements of the library in a complex motor act, where the individual elements have been smoothed together, and, occasionally, there might be a movement segment that is not in our library yet. We employ a flexible machine learning representation of movement primitives based on learnable nonlinear attractor system. For the purpose of movement segmentation and recognition, it is possible to reformulate this representation as a controlled linear dynamical system. An Expectation-Maximization algorithm can be developed to estimate the open parameters of a movement primitive from the library, using as input an observed trajectory piece. If no matching primitive from the library can be found, a new primitive is created. This process allows a straightforward sequential segmentation of observed movement into known and new primitives, which are suitable for robot imitation learning. We illustrate our approach with synthetic examples and data collected from human movement.

#### Statistical dynamical systems for skills acquisition in humanoids (Humanoid Robot 2012)
http://ieeexplore.ieee.org/document/6651539/
Learning by imitation in humanoids is challenging due to the unpredictable environments these robots have to face during reproduction. Two sets of tools are relevant for this purpose: 1) probabilistic machine learning methods that can extract and exploit the regularities and important features of the task; and 2) dynamical systems that can cope with perturbation in real-time without having to replan the whole movement. We present a learning by imitation approach combining the two benefits. It is based on a superposition of virtual spring-damper systems to drive a humanoid robot's movement. The method relies on a statistical description of the springs attractor points acting in different candidate frames of reference. It extends dynamic movement primitives models by formulating the dynamical systems parameters estimation problem as a Gaussian mixture regression problem with projection in different coordinate systems. The robot exploits local variability information extracted from multiple demonstrations of movements to determine which frames are relevant for the task, and how the movement should be modulated with respect to these frames. The approach is tested on the new prototype of the COMAN compliant humanoid with time-based and tim'e-invariant movements, including bimanual coordination skills.

### 2011

#### Online movement adaptation based on previous sensor experiences (IROS 2011, Stefan Schaal)
http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6095059
Personal robots can only become widespread if they are capable of safely operating among humans. In uncertain and highly dynamic environments such as human households, robots need to be able to instantly adapt their behavior to unforseen events. In this paper, we propose a general framework to achieve very contact-reactive motions for robotic grasping and manipulation. Associating stereotypical movements to particular tasks enables our system to use previous sensor experiences as a predictive model for subsequent task executions. We use dynamical systems, named Dynamic Movement Primitives (DMPs), to learn goal-directed behaviors from demonstration. We exploit their dynamic properties by coupling them with the measured and predicted sensor traces. This feedback loop allows for online adaptation of the movement plan. Our system can create a rich set of possible motions that account for external perturbations and perception uncertainty to generate truly robust behaviors. As an example, we present an application to grasping with the WAM robot arm.

#### Handling of multiple constraints and motion alternatives in a robot programming by demonstration framework (Humanoid Robot, 2009)
http://ieeexplore.ieee.org/document/5379592/
We consider the problem of learning robust models of robot motion through demonstration. An approach based on Hidden Markov Model (HMM) and Gaussian Mixture Regression (GMR) is proposed to extract redundancies across multiple demonstrations, and build a time-independent model of a set of movements demonstrated by a human user. Two experiments are presented to validate the method, that consist of learning to hit a ball with a robotic arm, and of teaching a humanoid robot to manipulate a spoon to feed another humanoid. The experiments demonstrate that the proposed model can efficiently handle several aspects of learning by imitation. We first show that it can be utilized in an unsupervised learning manner, where the robot is autonomously organizing and encoding variants of motion from the multiple demonstrations. We then show that the approach allows to robustly generalize the observed skill by taking into account multiple constraints in task space during reproduction.

Learning stable nonlinear dynamical systems with gaussian mixture models (2011) -TRO

https://infoscience.epfl.ch/record/166322/files/Khansari_Billard_TRO11_1.pdf

### 2010
Learning Stylistic Dynamic Movement Primitives from multiple demonstrations (2010)
http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=5651049

---



