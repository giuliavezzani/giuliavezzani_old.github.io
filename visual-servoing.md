---
layout: secondary

title: Markerless visual servoing on unknown objects for humanoid robot platforms
author: C. Fantacci, G. Vezzani, U. Pattacini, V. Tikhanoff and  L. Natale
---

## Abstract
 To precisely reach for an object with a humanoid robot, it is of central importance to have good knowledge of both end-effector, object pose and shape. In this work we propose a framework for markerless visual servoing on unknown objects, which is divided in four main parts: I) a least-squares minimization problem is formulated to find the volume of the object graspable by the robot's hand using its stereo vision; II) a recursive Bayesian filtering technique, based on Sequential Monte Carlo (SMC) filtering, estimates the 6D pose (position and orientation) of the robot's end-effector without the use of markers; III) a nonlinear constrained optimization problem is formulated to compute the desired graspable pose about the object; IV) an image-based visual servo control commands the robot's end-effector toward the desired pose. We demonstrate effectiveness and robustness of our approach with extensive experiments on the iCub humanoid robot platform, achieving real-time computation, smooth trajectories and sub-pixel precisions. 


A preprint is available on [arxiv](https://arxiv.org/pdf/1710.04465.pdf). 


The following picture represents  the  proposed  markerless  visual  servoing framework on unknown objects. 1)The  modeling  approach  described  in  [1]  reconstructs a  superquadric  representing  the  object  by  using  a  3D
partial point cloud acquired from stereo vision. 2) The  estimated  model  is  exploited  by  the  pose  compu-
tation method of [1] for providing a grasping pose. 3)  An  open  loop  phase  brings  the  robot’s  end-effector  in
the proximity of the object and in the cameras field-of-views. 4) The 3D model-aided particle filter of [2] estimates the
end-effector pose using RGB images. 5) Visual servoing uses the particle filter output of 4) in order to reach for the pose computed in 2). 6) Reaching completes and the robot grasps the object.
<p align="center">
<img src="https://raw.githubusercontent.com/giuliavezzani/giuliavezzani.github.io/master/files/pipeline.png">
</p>

[1]  G. Vezzani, U. Pattacini, and L. Natale, “A grasping approach based on superquadric models,” in
_IEEE International Confeference on Robotics Automation_, pp. 1579–1586, IEEE, 2017

[2] C.  Fantacci,  U.  Pattacini,  V.  Tikhanoff,  and  L.  Natale,  “Visual  end-effector tracking using a 3D model-aided particle filter for humanoid
robot  platforms,” in _IEEE/RSJ  International Conference on Intelligent Robots and Systems_, Vancouver, BC,Canada, September 24–28, 2017. arXiv preprint 1703.0477.

[Home page](./)
