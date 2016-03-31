# robotics_resources
A repo containing links of various tutorials, courses, and papers I've read, or partially read, at some point of time.

#### Deep Learning

##### Understanding convolutions
- [A guide to convolution arithmetic for deep learning](http://arxiv.org/abs/1603.07285v1) 
- [Understanding Convolution in Deep Learning](http://timdettmers.com/2015/03/26/convolution-deep-learning/)
- [What does the convolution step in a Convolutional Neural Network do?](http://stats.stackexchange.com/questions/116362/what-does-the-convolution-step-in-a-convolutional-neural-network-do)
- [Understanding convolutional neural networks](http://stats.stackexchange.com/questions/85767/understanding-convolutional-neural-networks)
###### Transposed convolutions / fractionally strided convolutions / deconvolutions/ upconvolutions / insert fancy or misleading name here, in context of semantic segmentation
- [CS 231n, W16, L13, start at 17:10](https://www.youtube.com/watch?v=ByjaPdWXKJ4&feature=youtu.be&t=17m10s)
- [Supplementary Materials, Generating images with recurrent adversarial networks. Pg 12 onwards](http://arxiv.org/pdf/1602.05110v2.pdf)
- [A guide to convolution arithmetic for deep learning](http://arxiv.org/abs/1603.07285v1) (repeated on purpose)
- [Lecture 8 and 9](https://computing.ece.vt.edu/~f15ece6504/#schedule) by Prof. Dhruv Batra

##### CNN
- [Using CNNs to detect facial keypoints tutorial](http://danielnouri.org/notes/2014/12/17/using-convolutional-neural-nets-to-detect-facial-keypoints-tutorial/#id10) : nolearn, lasagne

##### RNN/LSTM 
###### Text
- [Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
- [Recurrent Networks in Lasagne](http://colinraffel.com/talks/hammer2015recurrent.pdf)    

##### Generative
- [Enhancing images using Deep Convolutional Generative Adversarial Networks (DCGANs)](https://swarbrickjones.wordpress.com/2016/01/13/enhancing-images-using-deep-convolutional-generative-adversarial-networks-dcgans/)
- [Generative Adversarial Autoencoders in Theano](https://swarbrickjones.wordpress.com/2016/01/24/generative-adversarial-autoencoders-in-theano/)

###### Music
- [Composing Music With Recurrent Neural Networks](http://www.hexahedria.com/2015/08/03/composing-music-with-recurrent-neural-networks/)
- [Composing Music with LSTM Recurrent Networks - Blues Improvisation](http://people.idsia.ch/~juergen/blues/)
- [Modeling and generating sequences of polyphonic music with the RNN-RBM¶](http://deeplearning.net/tutorial/rnnrbm.html)

##### Deep Belief Nets/RBMs 
- [A Tutorial on Deep Neural Networks for Intelligent Systems](http://arxiv.org/pdf/1603.07249v1.pdf)

##### Convolution v/s correlation confusion
- [Correlation and Convolution
Class Notes for CMSC 426, Fall 2005, David Jacobs  ](http://www.cs.umd.edu/~djacobs/CMSC426/Convolution.pdf)
- Ctrl+f in links under "Understanding Convolutions" section

#### RL
##### Deep
- [Demystifying deep reinforcement learning](http://www.nervanasys.com/demystifying-deep-reinforcement-learning/)  

##### Not so deep
- [Adversarial Bandits and the Exp3 Algorithm](http://jeremykun.com/2013/11/08/adversarial-bandits-and-the-exp3-algorithm/) : Math ∩ Programming blog     
  Related - [SeqOpt by Debadeepta Dey et al](https://www.ri.cmu.edu/pub_files/2012/7/aaai12.pdf)
   
##### General 
- [Escaping saddlepoints](http://www.offconvex.org/2016/03/22/saddlepoints/)
-[What is the difference between convolutional neural networks, restricted Boltzmann machines, and auto-encoders?](http://stats.stackexchange.com/questions/114385/what-is-the-difference-between-convolutional-neural-networks-restricted-boltzma)
- [Deep learning in a nutshell - nvidia blogposts](https://devblogs.nvidia.com/parallelforall/deep-learning-nutshell-core-concepts/)

##### NLP
- [Deep-Learning-for-NLP-Resources](https://github.com/shashankg7/Deep-Learning-for-NLP-Resources)

#### SLAM 
##### Tutorials
- [CVPR 2014 tutorial on Visual SLAM](http://frc.ri.cmu.edu/~kaess/vslam_cvpr14/)

##### Algos
- [ElasticFusion](https://github.com/mp3guy/ElasticFusion)
- [ORB-SLAM2](https://github.com/raulmur/ORB_SLAM2) and [ORB-SLAM1](https://github.com/raulmur/ORB_SLAM)

#### Blogs to follow
- [Google](http://googleresearch.blogspot.com/)
- [inFERENCe](http://www.inference.vc/)
- [karpathy](http://karpathy.github.io/)
- [nervana](http://www.nervanasys.com/blog/)
- [Math ∩ Programming](http://jeremykun.com/)

#### Uncategorized cool stuff
- [Pictures combined by CNNs](http://imgur.com/gallery/BAJ8j)

#### Courses
- [robotics 1](http://www.diag.uniroma1.it/~deluca/rob1_en/material_rob1_en.html), Prof. Alessandro De Luca
   - Aims: This course provides the basic tools for the kinematic analysis, trajectory planning, and programming of motion tasks for robot manipulators in industrial and service environments.
   - Contents: Typical robotic systems are illustrated through examples of manipulators and mobile-base robots in industrial and service applications. The basic functional components of a robot are presented: mechanics for manipulation, actuators, proprio- and exteroceptive sensing devices, control architecture, and programming. Direct, inverse, and differential kinematic models of robot manipulators are analyzed. Trajectory planning methods both in the joint and in the task (Cartesian) space are then explored. Simple control schemes are introduced, including kinematic control for robot arms and decentralized dynamic control for the single axes of a manipulator.
- [robotics](http://www.diag.uniroma1.it/~deluca/rob2_en/material_rob2_en.html) 
   - Aims: This course provides tools for: Advanced kinematics and dynamic analysis of robot manipulators; Design of feedback control laws for free motion and interaction tasks, including visual servoing.
   - Contents: Advanced kinematics for robot manipulators (calibration, redundancy resolution). Derivation and use of the dynamic model of robots (Euler-Lagrange and Newton-Euler formulations). Identification of dynamic coefficients. Inclusion of joint transmission elasticity. Linear and nonlinear control schemes for set-point regulation (PD with gravity compensation, saturated PID, iterative learning) and for trajectory tracking (feedback linearization and decoupling, passive control, robust control, adaptive control) in free motion tasks, as well as for interaction tasks with the environment (compliance control, impedance control, hybrid force/velocity control). Image- and position-based visual servoing (kinematic treatment). Special topics will be presented in a seminarial way: diagnosis of robot actuator faults; detection of physical collisions and safe reaction.

#### Software
##### Linux kernel
- [linux-insides gitbook](https://0xax.gitbooks.io/linux-insides/content/index.html)
