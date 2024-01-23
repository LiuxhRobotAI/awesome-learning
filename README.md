# awesome-learning
A list of topics of interest. This list includes some very useful and recommended open books, platforms, tools and websites for AI technologies, computer vision, simultaneous localization and mapping(SLAM), control technologies of robotics and some very useful tutorials for robot technologies.
## I will update context related tools and everything in `Contents` in branch `main`, and update blogs in branch `gh-pages`.

## Contents

- [Basic theory](#Basic-theory)
- [Learning](#learning)
- [Robotics](#robotics)
- [Programming](#programming)
- [Platform](#Platform)
- [Tools](#Tools)
- [Websites](#Websites)

## Basic theory

- [Basic applied math]()
  - [AI book library](https://www.deeplearningbook.org/) - The most recommended book for machine learning. 
    - [Dive into deep learning](https://zh.d2l.ai/) - Useful tool book for deep learning and implementation. There is a tutorial course with video for this book.
    - [Machine learning book](https://github.com/aburkov/theMLbook) - The hundred-page machine learning book with code.
  - [Robotics coursework](https://github.com/mithi/robotics-coursework)
- [Implementation and application]()
  - [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) - Most recommended for understanding and getting starting algorithms.
  - [Eigen](https://gitlab.com/libeigen/eigen/-/releases) or [this site](http://eigen.tuxfamily.org/) - A C++ tool for matrix operation.
  - [Ceres](http://ceres-solver.org/) - An open-source C++ library for modeling and solving large, complicated optimization problems. There are binding tools for Python to use Ceres. It is [Pyceres](https://github.com/cvg/pyceres) which is based on [ceres_python_bindings](https://github.com/Edwinem/ceres_python_bindings).
  - [G2O](https://github.com/RainerKuemmerle/g2o) - An open-source C++ library for general graph optimization.
  - [Sophus](https://github.com/strasdat/Sophus) - A C++ implementation of Lie groups basic on Eigen, commonly used for 2d and 3d geometric problems.
  - [GTSAM](https://gtsam.org/) - A C++ library that implements sensor fusion for robotics and computer vision applications, including SLAM, VO, and SFM (Structure from Motion). It uses factor graphs and Bayes networks as the underlying computing paradigm rather than sparse matrices to optimize for the most probable configuration or an optimal plan.
  - [miniSAM](https://github.com/dongjing3309/minisam) - An open-source C++/Python framework for solving factor graph-based least squares problems inspired by GTSAM but more lightweight. Some tutorials on factor graph-based optimization problems should be very useful. 
  - [Mosek](https://www.mosek.com/) - Powerful solver to optimization problems. And [Yalmip](https://yalmip.github.io/) - A tool for optimization problems. [Here](https://yalmip.github.io/solver/mosek/) is how it works with Mosek.
  - [OOQP](https://pages.cs.wisc.edu/~swright/ooqp/) - An object-oriented C++ package, based on a primal-dual interior-point method, for solving convex quadratic programming problems (QPs).
  - [NLopt](https://nlopt.readthedocs.io/en/latest/) - A free/open-source library for nonlinear optimization, providing a common interface for a number of different free optimization routines available online as well as original implementations of various other algorithms.
  - [Suitesparse](https://people.engr.tamu.edu/davis/suitesparse.html) - A sparse Matrix software suite.
  - [SciPy](https://scipy.org/) - SciPy is a math function library that uses NumPy. This library provides algorithms for optimization, integration, interpolation, eigenvalue problems, algebraic equations, differential equations, statistics, and many other classes of problems.
  - [cvxpy](https://github.com/cvxpy/cvxpy) - A Python-embedded modeling language for convex optimization problems. It allows you to express your problem in a natural way that follows the math, rather than in the restrictive standard form required by solvers. `Most recommended as Mosek and Yalmip! for Python users`.
  - [Pyomo](https://pyomo.readthedocs.io/en/stable/solving_pyomo_models.html) - Python Optimization Modeling Objects.
  - [CVXOPT](https://cvxopt.org/) - A free Python software package for convex optimization.
  - [Regularization Tools](https://www.imm.dtu.dk/~pcha/Regutools/) - Or find an old copy [here](https://github.com/hadiTab/regu).

## Learning

- [AI](https://github.com/owainlewis/awesome-artificial-intelligence)
  - [Tutorial for CNN](https://github.com/vzhou842/cnn-from-scratch) - Most recommended, the easiest tutorial for CNN, or [Neural network from scratch](https://github.com/vzhou842/neural-network-from-scratch).
  - [Understanding backpropagation](https://mattmazur.com/2015/03/17/a-step-by-step-backpropagation-example/)
  - [AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) - From Microsoft.
  - [Machine learning beginner](https://github.com/fengdu78/machine_learning_beginner) - A road map and tutorial for machine learing beginner. In Chinese.
  - [Awesome deep learning](https://github.com/ChristosChristofidis/awesome-deep-learning) - A list of resource for deep learning (Updating).
  - [Awesome machine learning](https://github.com/josephmisiti/awesome-machine-learning) - A list of resource for machine learning (Updating).
- [XAI]() - Explainable or interpretable AI
  - [LIME](https://github.com/marcotcr/lime) - A local interpretable model-agnostic explanations (LIME).
  - [SHAP](https://github.com/shap/shap) - A game theoretic approach to explain the output of any machine learning model.
- [Excellent demo]()
  - [ChatGPT](https://openai.com/blog/chatgpt)
  - [ChatGPT desktop](https://github.com/lencx/ChatGPT)
  - [VQA](https://github.com/vzhou842/easy-VQA-keras) - Visual question answering, a simple example to build your chatbot.
- [Great projects]()
  - [keras](https://keras.io/guides/making_new_layers_and_models_via_subclassing) - A tool for learning implementaion and [some documents](https://wizardforcel.gitbooks.io/keras-cn/content/docs/layers/writting_layer.html) for beginners.

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

- [Jackal Robot simulation platform](http://docs.ros.org/en/latest-available/api/jackal_tutorials/html/simulation.html)
- [OpenCV](https://opencv.org/)
- [evo](https://github.com/MichaelGrupp/evo) - A tool for evaluating and comparing the trajectory output of odometry and SLAM algorithms.
- [Pangolin](https://github.com/stevenlovegrove/Pangolin) - A 3D visualization tool that includes a set of lightweight and portable utility libraries for prototyping 3D, numeric or video-based programs and algorithms used quite widely in the field of Computer Vision.
- [BoW] - The bag-of-words (BOW) model.
- [COLMAP](https://colmap.github.io/) - A general-purpose Structure-from-Motion (SfM) and Multi-View Stereo (MVS) pipeline with a graphical and command-line interface which is very useful for SLAM.

## Websites

- [PapersWithCode](https://paperswithcode.com/sota) - Code !!
- [PaperDigest](https://www.paperdigest.org/review/)
- [RunDocs](https://rundocs.github.io/starter/) - Documentation your projects. [Here](https://zhuanlan.zhihu.com/p/323457078) is a tutorial of how to create an website page document for your projects using [Gihub Page](https://pages.github.com/) and [RunDocs](https://github.com/rundocs/rundocs.io/tree/master/docs)
