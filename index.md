<!-- You can use the [editor on GitHub](https://github.com/yifanyin11/yifanyin11.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files. -->

**Welcome to my site!** I am a graduate assistant at [_Laboratory for Computational Sensing and Robotics_](https://lcsr.jhu.edu/), the Johns Hopkins University. My academic interests are on **_perception and cognitive systems_** in Robotics applications. I love involving in creative work or exploring the depth on interesting topics. Feel free to browse in the site and learn things about me.

## Academic Life

### Work Experience

**Research Assistant – Visual Perception and Robotics** \
Laboratory for Computational Sensing and Robotics, Johns Hopkins University \
_Feb. 2022 – Present_  

* Working on the visual perception of a micro-dissection system using ROS, camera calibrations, object detection, feature extraction, semantic segmentation, visual-servoing control and perception systems
* Designed and implemented calibration-free visual servos for robot homing and surface safe approaching to save operation time by ~37% using key-point detection, feature extraction and finite-state machines
* Developed a ROS service for the subpixel level detection and localization of the robot tooltip to improve the accuracy of hand-eye calibration by ~14% using key-point detection algorithms (Mask R-CNN) 
* Designed and implemented a 2D domain randomization pipeline for data augmentation and image label refinements, capable of generating ~800 images per minute with supplied backgrounds 
* Developed a 3D domain randomization to generate simulated images from different camera views using Unity 3D simulation, and perform domain adaptation to transfer those images into real domain using Cycle GAN
* Maintained data stream organization by developing a framework for integrated data management during network training, inference and evaluation


### Courses
Computer Vision  
Augmented Reality \
Reinforcement Learning  
Statistical Learning   
Robot Devices, Kinematics, Dynamics, and Control  
Algorithms for Sensor-Based Robotics \
Vision as Bayesian Inference

### Projects

**Ro-robotic Ultrasound Mammography**
_May. 2022 – Present_

* Built an ultrasound auto-scanning robot manipulator system for the diagnosis and varification of the breast cancer with ROS, kinematics, motion planning, camera calibration, image registration, visual servoing, robot control
* Performed accurate camera calibration, ultrasound calibration and pivot calibration, which achieved an overall system accuracy of <4mm in vision-guided robot manipulations
* Designed and implemented image processing and segmentation algorithms for the localization and segmentation of the lesion areas in ultrasound images using classical and deep-learning based methods
* Developed an automatic camera calibration algorithm that demonstrated to save a calibration time of over 80%
* Implemented visual guided motion planning algorithms that are capable of finding jump-free paths in ~99% of time with ROS, rapidly-exploring random tree (RRT), stereo cameras, MoveIt, Aruco markers
* Implemented control algorithms for approaching scanning regions and performing ultrasound scanning ‘Wobble motion’ with ROS, kinematics and resolved-rate control algorithms

**Trajectory Planning and Medical Data Visualization in Ultrasound-Based Facet Joint Injection** \
_Mar. 2022 – Present_

* Built a Head-Mounted Augmented Reality application for assisting lesion localization, surgical planning and trajectory visualization during facet joint injections using C# programming, Unity 3D, TCP communication; awarded the Honorary Mentioned Demo in final presentation
* Designed and built AR scenes for augmenting a virtual monitor that displays slices of the preoperative lumbar spine images (CT/MRI) in real-time as scanning the patient’s back with a registered tool 
* Added intuitive user interfaces for viewing image/text records for each injection target under previous clinical visits for intraoperative reference using Microsoft Mixed Reality Toolkit (MRTK)
* Implemented a data management system for the generation, storage and extraction of clinical records using C# and object-oriented programming, capable of saving/invoking one record within 0.3ms
* Designed and implemented a TCP communication pipeline between HoloLens2 and the operation computers for efficient transfer of preoperative medical images
* Developed algorithms for the planning and visualization of injection trajectories, giving an error of smaller than 2mm 
* Improved depth perception during alignment of surigical tools with planned trajectories by augmenting a window on the patient’s skin that can look virtually inside the body at injection target positions

**Game Playing of ‘Flappy Bird’ with Double Deep Q Network** \
_Nov. 2021 – Dec. 2021_

* Designed and implemented an intelligent agent that can play the game ‘Flappy Bird’ forever using deep Q reinforcement learning, image processing, Markov Decision Process, convolutional neural networks (CNNs)
* Constructed convolutional neural network models from scratch for game action classifications at each frame with an AUC of 0.85+ using the PyTorch framework
* Added time-varying reward settings to the Markov Decision Process to avoid convergence of the neural networks to extreme solutions and brought a ~2000 epochs earlier convergence 
* Added an image preprocessing pipeline to ~26% decrease computational cost of training neural networks
* Enhanced performance by 10% to 12% using Double Deep-Q networks and Experience Replay buffers



### Publications
1. [Study on the Boost Converter with Parasitic Parameters of SiC MOSFET](https://iopscience.iop.org/article/10.1088/1742-6596/1846/1/012061) 

  Yin, Yifan. "Study on the Boost Converter with Parasitic Parameters of SiC MOSFET." Journal of Physics: Conference Series. Vol. 1846. No. 1. IOP Publishing, 2021.

