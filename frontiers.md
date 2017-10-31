---
layout: secondary

title: A Real-time pipeline for object modeling and grasping pose selection via superquadric functions 
author: G. Vezzani and L. Natale
---

## Abstract
 This work provides a novel real-time pipeline for modeling and grasping of unknown objects with a humanoid robot. Such a problem is of great interest for the robotic community, since conventional approaches fail when the shape, dimension or pose of the objects are missing.
Our approach reconstructs in real-time a model for the object under consideration and represents the robot hand with proper and mathematically usable models, i.e. superquadric functions. The volume graspable by the hand is represented by an ellipsoid and is defined a-priori, because the shape of the hand is known in advance. The superquadric representing the object is obtained in real-time from partial vision information instead, e.g. one stereo view of the object under consideration, and provides an approximated 3D full model. The optimization problem we formulate for the grasping pose computation is solved online by using the Ipopt software package and, thus, does not require off-line computation or learning.
Even though our approach is for a generic humanoid robot, we developed a complete software architecture for executing this approach on the iCub humanoid robot. Together with that, we also provide a tutorial on how to use this framework.
We believe that our work, together with the available code, is of a strong utility for the iCub community for three main reasons: object modeling and grasping are relevant problems for the robotic community, our code can be easily applied on every iCub and the modular structure of our framework easily allows extensions and communications with external code.


More information are available at [this link](https://www.frontiersin.org/articles/10.3389/frobt.2017.00059/abstract). 

The code I developed is available on _github_: 

[![DOI](https://zenodo.org/badge/54572419.svg)](https://zenodo.org/badge/latestdoi/54572419)

[![DOI](https://zenodo.org/badge/54477564.svg)](https://zenodo.org/badge/latestdoi/54477564)


The following picture represents a sketch of the modeling and grasping pipeline. 1) The object is stored by the object property
collector with the label object. 2) LbpExtract provides the 2D blob of the object. 3) The 3D point cloud is
extracted from the disparity map, by querying the Structure From Motion module. 4) The superquadric
modeling the object is reconstructed. 5) The grasping pose and approaching trajectory for the right hand
are computed. 6) The robot grasps the object.

<p align="center">
<img src="https://raw.githubusercontent.com/giuliavezzani/giuliavezzani.github.io/master/files/results.png">
</p>



[Home page](./)
