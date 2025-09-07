# awesome-learning
A list of topics of interest. This list includes some very useful and recommended open books, platforms, tools and websites for AI technologies, computer vision, simultaneous localization and mapping(SLAM), control technologies of robotics and some very useful tutorials for robot technologies.

## Contents

- [Basic theory](#Basic-theory)
- [Learning](#Learning)
- [Robotics](#Robotics)
- [Programming](#Programming)
- [Platform](#Platforms)
- [Tools](#Tools)
- [Websites](#Websites)

## Basic theory

- [Basic applied math]()
  - [AI book library](https://www.deeplearningbook.org/) - The most recommended book for machine learning. 
    - [Dive into deep learning](https://zh.d2l.ai/) - A useful tool book for deep learning and implementation. There is a tutorial course with video for this book.
    - [Machine learning book](https://github.com/aburkov/theMLbook) - The hundred-page machine learning book with code.
  - [Robotics coursework](https://github.com/mithi/robotics-coursework)
- [Implementation and application]()
  - [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) - Most recommended for understanding and getting started with algorithms.
  - [Eigen](https://gitlab.com/libeigen/eigen/-/releases) or [this site](http://eigen.tuxfamily.org/) - A C++ tool for matrix operation.
  - [Ceres](http://ceres-solver.org/) - An open-source C++ library for modeling and solving large, complicated optimization problems. There are binding tools for Python to use Ceres. It is [Pyceres](https://github.com/cvg/pyceres) which is based on [ceres_python_bindings](https://github.com/Edwinem/ceres_python_bindings).
  - [G2O](https://github.com/RainerKuemmerle/g2o) - An open-source C++ library for general graph optimization.
  - [Sophus](https://github.com/strasdat/Sophus) - A C++ implementation of Lie groups based on Eigen, commonly used for 2d and 3d geometric problems.
  - [GTSAM](https://gtsam.org/) - A C++ library that implements sensor fusion for robotics and computer vision applications, including SLAM, VO, and SFM (Structure from Motion). It uses factor graphs and Bayes networks as the underlying computing paradigm rather than sparse matrices to optimize for the most probable configuration or an optimal plan.
  - [miniSAM](https://github.com/dongjing3309/minisam) - An open-source C++/Python framework for solving factor graph-based least squares problems inspired by GTSAM but more lightweight. Some tutorials on factor graph-based optimization problems should be very useful. 
  - [Mosek](https://www.mosek.com/) - Powerful solver to optimization problems. And [Yalmip](https://yalmip.github.io/) - A tool for optimization problems. [Here](https://yalmip.github.io/solver/mosek/) is how it works with Mosek.
  - [OOQP](https://pages.cs.wisc.edu/~swright/ooqp/) - An object-oriented C++ package, based on a primal-dual interior-point method, for solving convex quadratic programming problems (QPs).
  - [NLopt](https://nlopt.readthedocs.io/en/latest/) - A free/open-source library for nonlinear optimization, providing a common interface for a number of different free optimization routines available online as well as original implementations of various other algorithms.
  - [Suitesparse](https://people.engr.tamu.edu/davis/suitesparse.html) - A sparse Matrix software suite.
  - [SciPy](https://scipy.org/) - SciPy is a math function library that uses NumPy. This library provides algorithms for optimization, integration, interpolation, eigenvalue problems, algebraic equations, differential equations, statistics, and many other classes of problems.
  - [cvxpy](https://github.com/cvxpy/cvxpy) - A Python-embedded modeling language for convex optimization problems. It allows you to express your problem in a natural way that follows the math, rather than in the restrictive standard form required by solvers. `Most recommended as Mosek and Yalmip! for Python users`.
  - [Pyomo](https://pyomo.readthedocs.io/en/stable/solving_pyomo_models.html) - Python Optimization Modeling Objects ([Pyomo](https://github.com/Pyomo/pyomo)) supports a diverse set of optimization capabilities for formulating and analyzing optimization models. Pyomo can be used to define symbolic problems, create concrete problem instances, and solve these instances with standard solvers. Pyomo supports a wide range of problem types, including: Linear, Quadratic, Nonlinear, Mixed-integer and Constraint programming and so on.
  - [CVXOPT](https://cvxopt.org/) - A free Python software package for convex optimization.
  - [Regularization Tools](https://www.imm.dtu.dk/~pcha/Regutools/) - Or find an old copy [here](https://github.com/hadiTab/regu).
  - [Optimization tool in Python](), There are many optimization tool used for SLAM, machine leraning and so on: [g2opy](https://github.com/uoip/g2opy) is only for SLAM and it is a python binding of graph optimization C++ frameworkb `g2o`; The recently emerged and maintained [pypose](https://github.com/pypose/pypose) (by Wang Chen) and [cvxpylayers](https://github.com/cvxgrp/cvxpylayers), [theseus](https://github.com/facebookresearch/theseus) from `Meta AI` may be the most remarkable ones.  
  - [SymPy](https://github.com/sympy/sympy) - A Python library for symbolic mathematics, a computer algebra system like `Maple` and `Mathematica` that can be used to symbolically differentiate the objective function and generate the C++ to evaluate them.
  - [wxMaxima](https://wxmaxima-developers.github.io/wxmaxima/) - A document based interface for the computer algebra system `Maxima`. wxMaxima provides menus and dialogs for many common maxima commands, autocompletion, inline plots and simple animations. The tensor calculation of `Ralativity` is one of the main usages of wxMaxima.
  - [Manopt](https://www.manopt.org/) - A tool for optimization on manifolds. There is a Python version [PyManopt](https://pymanopt.org/). 

## Learning

- [AI](https://github.com/owainlewis/awesome-artificial-intelligence)
  - [Tutorial for CNN](https://github.com/vzhou842/cnn-from-scratch) - Most recommended, the easiest tutorial for CNN, or [Neural network from scratch](https://github.com/vzhou842/neural-network-from-scratch).
  - [Understanding backpropagation](https://mattmazur.com/2015/03/17/a-step-by-step-backpropagation-example/)
  - [AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) - From Microsoft.
  - [Machine learning beginner](https://github.com/fengdu78/machine_learning_beginner) - A road map and tutorial for machine learning beginners. In Chinese.
  - [Awesome deep learning](https://github.com/ChristosChristofidis/awesome-deep-learning) - A list of resources for deep learning (Updating).
  - [Awesome machine learning](https://github.com/josephmisiti/awesome-machine-learning) - A list of resources for machine learning (Updating).
  - [PINNs from scratch](https://github.com/LiuxhRobotAI/PINNs-from-scratch) - A simple example for physics-informed neural networks (PINNs), using the damped harmonic oscillator(mass spring damper model) as a case study. Some more examples and analysis can be found [here](https://github.com/benmoseley/FBPINNs).
  - [Augment physics-based models]() - An example of augment physics-based models (APBM) can be found [here](https://github.com/neu-spiral/APBM-TAES2023).
- [XAI]() - Explainable or interpretable AI
  - [LIME](https://github.com/marcotcr/lime) - A local interpretable model-agnostic explanations (LIME).
  - [SHAP](https://github.com/shap/shap) - A game theoretic approach to explain the output of any machine learning model.
- [Excellent demo]()
  - [ChatGPT](https://openai.com/blog/chatgpt)
  - [ChatGPT desktop](https://github.com/lencx/ChatGPT)
  - [VQA](https://github.com/vzhou842/easy-VQA-keras) - Visual question answering, a simple example to build your chatbot.
- [AI frameworks]()
  - [Pytorch tutorials](https://pytorch.org/tutorials/beginner/pytorch_with_examples.html)- Build a neural network from scratch with automatic differentiation.
  - [TensorFlow tutorials](https://www.tensorflow.org/guide/eager?hl=zh-cn)
  - [Hugging Face](https://huggingface.co/docs/transformers/zh/quicktour) - Transformers.
  - [keras](https://keras.io/guides/making_new_layers_and_models_via_subclassing) - A tool for learning implementaion and [some documents](https://wizardforcel.gitbooks.io/keras-cn/content/docs/layers/writting_layer.html) for beginners.
  - [Scikit-Learn](https://scikit-learn.org/stable/getting_started.html)
  - [MXNet](https://mxnet.apache.org/versions/1.9.1/api/python/docs/tutorials/getting-started/crash-course/2-nn.html)
  - [Caffe](https://caffe.berkeleyvision.org/tutorial/net_layer_blob.html)

## Robotics 

- [Awesome robotics](https://github.com/Kiloreux/awesome-robotics#readme)
  - [Awesome robotics libraries](https://github.com/jslee02/awesome-robotics-libraries)
- [Localization]() 
  - [SLAM](https://github.com/changh95/visual-slam-roadmap) - Roadmap for SLAM beginner.
    - [SLAM arts](https://github.com/autodriving-heart/Awesome-SLAM) - A summary of SLAM, including basic theories and practical examples and visual, lidar SLAM.
    - [SLAM using Python](https://atsushisakai.github.io/PythonRobotics/) - Many topics on robotics including SLAM.  
  - [UWB localization](https://github.com/cliansang/uwb-tracking-ros) - Or [this](https://github.com/TIERS/ros-dwm1001-uwb-localization)
- [Control]()
  - [Mothin planning](https://github.com/zhm-real/MotionPlanning/blob/master/README.md)
  - [Path following]()
  - [Trajectory tracking](https://github.com/DongChen06/PathTrackingBicycle)
- [Computer vision](https://github.com/jbhuang0604/awesome-computer-vision)
  -[Step by step tutorial for visual SLAM using Python](https://github.com/varyshare/easy_slam_tutorial) 
- [Object detecting and tracking ](https://github.com/visionml/pytracking) or with [LIDAR](https://github.com/HuangCongQing/3D-LIDAR-Multi-Object-Tracking) and [LIDAR simulation](https://github.com/SS47816/lidar_obstacle_detector)
- [Journals and conferences]() - Collection of papers
  - [Journals]()
  - [Conferences]()
    - [CVPR](https://github.com/extreme-assistant/CVPR2023-Paper-Code-Interpretation).

## Programming

- [Language](https://learnxinyminutes.com/) - Learn X in Y minutes
  - [Python](https://learnxinyminutes.com/docs/python/) - learnpython.py
  - [C++](https://learnxinyminutes.com/docs/c++/)
  - [MATLAB](https://learnxinyminutes.com/docs/matlab/)
  - [Objective-C](https://learnxinyminutes.com/docs/c/)

## Platforms

- [Linux](https://github.com/inputsh/awesome-linux#readme)
  - [Containers](https://github.com/Friz-zy/awesome-linux-containers#readme)
- [Windows](https://github.com/Awesome-Windows/Awesome#readme)
  - [WSL](https://github.com/sirredbeard/Awesome-WSL) Here is a collection of Windows Subsystem for Linux (WSL) information, distributions, and tools.
- [ROS](https://docs.ros.org/)
  - [ROS1](http://wiki.ros.org/ROS/Installation)
  - [ROS2](https://docs.ros.org/)
  
## Tools

- [webots](https://github.com/cyberbotics/webots) - A robot simulator that provides a complete development environment to model, program and simulate robots, vehicles and mechanical systems. Robot may be programmed in C, C++, Python, Java, MATLAB, or ROS with a simple API covering all the basic robotics needs.
- [Jackal Robot simulation platform](http://docs.ros.org/en/latest-available/api/jackal_tutorials/html/simulation.html) - A simulator for mobile robots.
- [OpenCV](https://opencv.org/) - The world's biggest computer vision library.
- [evo](https://github.com/MichaelGrupp/evo) - A tool for evaluating and comparing the trajectory output of odometry and SLAM algorithms.
- [Pangolin](https://github.com/stevenlovegrove/Pangolin) - A 3D visualization tool that includes a set of lightweight and portable utility libraries for prototyping 3D, numeric, or video-based programs and algorithms used quite widely in the field of Computer Vision.
- [BoW] - The bag-of-words (BOW) model.
- [COLMAP](https://colmap.github.io/) - A general-purpose Structure-from-Motion (SfM) and Multi-View Stereo (MVS) pipeline with a graphical and command-line interface, which is very useful for SLAM.
- [YOLO](https://pjreddie.com/darknet/yolo/) - A real-time object detection system, which is very useful for automatic driving and SLAM. Now it updates as YOLOv10, and has a YOLOv4-tiny.
- [MatrixCalculus](https://www.matrixcalculus.org/) - An online tool that computes vector and matrix derivatives (matrix calculus).
- Math Video Production Tools: Microsoft [Clipchamp](https://clipchamp.com/en/) is easy to use. Some other useful examples: Graphing Software: [GeoGebra](https://www.geogebra.org/), Recording Software: [Open Broadcaster Software, OBS](https://obsproject.com/), Animation Production: [ScreenToGif](https://www.screentogif.com/), Video Source: Convert Markdown text to HTML, using Edge's built-in voice-to-speech feature. 

## Websites

- [PapersWithCode](https://paperswithcode.com/sota) - Code !!
- [PaperDigest](https://www.paperdigest.org/review/)
- [RunDocs](https://rundocs.github.io/starter/) - Documentation your projects. [Here](https://zhuanlan.zhihu.com/p/323457078) is a tutorial on how to create a website page document for your projects using [GitHub Page](https://pages.github.com/) and [RunDocs](https://github.com/rundocs/rundocs.io/tree/master/docs)
