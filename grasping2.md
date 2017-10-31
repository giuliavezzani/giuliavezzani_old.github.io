---
layout: secondary

title: MImproving Superquadric Modeling and Grasping with Prior on Object Shapes
author: G. Vezzani, U. Pattacini, G. Pasquale and  L. Natale
---

## Abstract
 This paper proposes an object modeling and
grasping pipeline for humanoid robots. This work improves
our previous approach based on superquadric functions. In
particular, we speed up and refine the modeling process by using
prior information on the object shape provided by an object
classifier. We use our previous method for the computation of
grasping pose to obtain pose candidates for both the robot
hands and, then, we automatically choose the best candidate
for grasping the object according to a given quality index.
The performance of our pipeline has been assessed on a real
robotic system, the iCub humanoid robot. The robot can grasp
18 objects of the YCB and iCubWorld datasets considerably
different in terms of shape and dimensions with a high success
rate.


The following picture represents  complete and improved modeling and grasping pipeline. 
An object categorization system provides prior information on the shape of the object to be grasped (Step 1).
Our modeling approach reconstructs a superquadric representing the object (Step 3) by combining the information
provided by vision (Step 2) and the prior on object shape (Step 1). The prior information on object shape helps
to obtain a finer and more sharp-cornered model that is crucial for computing better grasping poses. Our approach
computes the grasping pose by maximizing the overlapping between the hand ellipsoid H and the object superquadric
O. A more accurate model can thus provide useful information about where to locate the desired pose for better grasping
performance.
The estimated model is used to obtain pose candidates for the right and left hand (Step 4).
The best hand for grasping the object is automatically selected according to proper criteria that are summarized in a
pose quality index (Step 5). In particular, the index takes into account the overlapping between the hand ellipsoid H
and the object superquadric O and favors grasping poses with orientations easily reachable by the robot.
Once the selected hand reaches the desired pose, grasp stabilization is achieved via tactile feedback so that the
robot can robustly lift the object (Step 6).
<p>
<img src="https://raw.githubusercontent.com/giuliavezzani/giuliavezzani.github.io/master/files/icra-pipeline-nofilter-min.png">
</p>



[Home page](./)
