<!-- You can use the [editor on GitHub](https://github.com/yifanyin11/yifanyin11.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files. -->

**Welcome to my site!** I am a first-year Ph.D. student in [Computer Science](https://www.cs.jhu.edu/) at [Johns Hopkins University](https://www.jhu.edu/), advised by Professor [Tianmin Shu](https://www.tshu.io/). My research interests are in the areas of **_embodied AI_**, **_human robot interaction_** and **_robotic perception_**.

Before my Ph.D., I completed my M.S.E. degree with a major in Robotics in the [Laboratory for Computational Sensing and Robotics](https://lcsr.jhu.edu/) at Hopkins, under the supervision of Professor [Russell Taylor](https://www.cs.jhu.edu/~rht/) and Professor [Emad Boctor](https://malonecenter.jhu.edu/people/emad-boctor/). There, I conducted research on **_robotic perception and manipulation_** in medical applications.

I love involving in creative work or exploring the depth on interesting topics. Also, I'm always open to meeting incredible collaborators. If you're interested, feel free to send me an email!

## Academic Life

### Work Experience

**Computer Vision Internship** \
PediaMetrix, Rockville, MD \
_July. 2023 - _July. 2024_  
*	Developed and implemented a machine learning based classifier for statistical prediction of types of skull abnormalities, obtained a sensitivity of 94.6% and specificity of 99.3%.
*	Working on the improvement of the 3D reconstruction pipeline for cranial shape modeling with smart phone cameras by utilizing image processing, image registration, foreground estimation, instance segmentation techniques.

**Research Assistant – Visual Perception and Robotics** \
Laboratory for Computational Sensing and Robotics, Johns Hopkins University \
_Feb. 2022 – July. 2023_  

* Working on the visual perception of a micro-dissection system using ROS, camera calibrations, object detection, feature extraction, semantic segmentation, visual-servoing control and perception systems
* Designed and implemented calibration-free visual servos for robot homing and surface safe approaching to save operation time by ~37% using key-point detection, feature extraction and finite-state machines
* Developed a ROS service for the subpixel level detection and localization of the robot tooltip to improve the accuracy of hand-eye calibration by ~14% using key-point detection algorithms (Mask R-CNN) 
* Designed and implemented a 2D domain randomization pipeline for data augmentation and image label refinements, capable of generating ~800 images per minute with supplied backgrounds 
* Developed a 3D domain randomization to generate simulated images from different camera views using Unity 3D simulation, and perform domain adaptation to transfer those images into real domain using Cycle GAN
* Maintained data stream organization by developing a framework for integrated data management during network training, inference and evaluation

### Projects

**Ro-robotic Ultrasound Mammography** \
_May. 2022 – May. 2023_

* Built an ultrasound auto-scanning robot manipulator system for the diagnosis and varification of the breast cancer with ROS, kinematics, motion planning, camera calibration, image registration, visual servoing, robot control
* Performed accurate camera calibration, ultrasound calibration and pivot calibration, which achieved an overall system accuracy of <4mm in vision-guided robot manipulations
* Designed and implemented image processing and segmentation algorithms for the localization and segmentation of the lesion areas in ultrasound images using classical and deep-learning based methods
* Developed an automatic camera calibration algorithm that demonstrated to save a calibration time of over 80%
* Implemented visual guided motion planning algorithms that are capable of finding jump-free paths in ~99% of time with ROS, rapidly-exploring random tree (RRT), stereo cameras, MoveIt, Aruco markers
* Implemented control algorithms for approaching scanning regions and performing ultrasound scanning ‘Wobble motion’ with ROS, kinematics and resolved-rate control algorithms

**Trajectory Planning and Medical Data Visualization in Ultrasound-Based Facet Joint Injection** \
_Mar. 2022 – June. 2022_

* Built a Head-Mounted Augmented Reality application for assisting lesion localization, surgical planning and trajectory visualization during facet joint injections using C# programming, Unity 3D, TCP communication; awarded the Honorary Mentioned Demo in final presentation
* Designed and built AR scenes for augmenting a virtual monitor that displays slices of the preoperative lumbar spine images (CT/MRI) in real-time as scanning the patient’s back with a registered tool 
* Added intuitive user interfaces for viewing image/text records for each injection target under previous clinical visits for intraoperative reference using Microsoft Mixed Reality Toolkit (MRTK)
* Implemented a data management system for the generation, storage and extraction of clinical records using C# and object-oriented programming, capable of saving/invoking one record within 0.3ms
* Designed and implemented a TCP communication pipeline between HoloLens2 and the operation computers for efficient transfer of preoperative medical images
* Developed algorithms for the planning and visualization of injection trajectories, giving an error of smaller than 2mm 
* Improved depth perception during alignment of surigical tools with planned trajectories by augmenting a window on the patient’s skin that can look virtually inside the body at injection target positions


### Publications

*. [PartInstruct: Part-level Instruction Following for Fine-grained Robot Manipulation](https://openreview.net/pdf?id=Kb4fDvJBlj)

Yin, Y., Han, Z., Aarya, S., Xu, S., Wang, J., Peng, J., Wang, A., Yuille, A., & Shu, T. (2025). PartInstruct: Part-level Instruction Following for Fine-grained Robot Manipulation. 7th Robot Learning Workshop: Towards Robots with Human-Level Abilities.


*. [Enabling Mammography with Co-Robotic Ultrasound](https://arxiv.org/abs/2312.10309)

Chen, Y., Yin, Y., Brown, J., Wang, K., Wang, Y., Wang, Z., Taylor, R. H., Wu, Y., & Boctor, E. M. (2023). Enabling Mammography with Co-Robotic Ultrasound. arXiv preprint arXiv:2312.10309.

*. [Applications of Uncalibrated Image Based Visual Servoing in Micro-and Macroscale Robotics](https://ieeexplore.ieee.org/abstract/document/10260445)

Y. Yin, Y. Wang, Y. Zhang, R. H. Taylor and B. P. Vagvolgyi, "Applications of Uncalibrated Image Based Visual Servoing in Micro- and Macroscale Robotics," 2023 IEEE 19th International Conference on Automation Science and Engineering (CASE), Auckland, New Zealand, 2023, pp. 1-8, doi: 10.1109/CASE56687.2023.10260445.
