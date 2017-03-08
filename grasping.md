---
layout: secondary
title: A Grasping Approach Based on Superquadric Models
author: G. Vezzani, U.Pattacini, and L. Natale
---

## Abstract

This paper addresses the problem of grasping unknown objects with a humanoid robot. Conventional ap-
proaches fail when the shape, dimension or pose of the objects are missing. We propose a novel approach in which the
grasping problem is solved by modeling the object and the volume graspable by the hand with superquadric functions.
The object model is computed in real-time using stereo vision. Pose computation is formulated as a nonlinear constrained
optimization problem, which is solved in real-time using the Ipopt software package. Notably, our method finds solutions in
which the fingers are located on portions of the object that are occluded by vision. The performance of our approach has been
assessed on a real robotic system, the iCub humanoid robot. The experiments show that the proposed method computes proper
poses, suitable for grasping even small objects, while avoiding hitting the table with the fingers.

This paper will be available on the Proceedings of IEEE International Conference on Robotics and Automation.
A preprint is available [here]().

[Go back to the home page](./)
