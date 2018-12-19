---
layout: secondary
title: A Grasping Approach Based on Superquadric Models
author: G. Vezzani, U.Pattacini, and L. Natale
---

## Abstract

This paper addresses the problem of grasping unknown objects with a humanoid robot. Conventional approaches fail when the shape, dimension or pose of the objects are missing. We propose a novel approach in which the grasping problem is solved by modeling the object and the volume graspable by the hand with superquadric functions. The object model is computed in real-time using stereo vision. Pose computation is formulated as a nonlinear constrained optimization problem, which is solved in real-time using the Ipopt software package. Notably, our method finds solutions in which the fingers are located on portions of the object that are occluded by vision. The performance of our approach has been assessed on a real robotic system, the iCub humanoid robot. The experiments show that the proposed method computes proper poses, suitable for grasping even small objects, while avoiding hitting the table with the fingers.

The paper can be downloaded [here](https://github.com/giuliavezzani/giuliavezzani.github.io/raw/master/files/superquadric-grasping.pdf). [This video](https://www.youtube.com/watch?v=eGZO8peAVao) shows the testing of our approach on a set of everyday objects.

The code I developed is available on _github_:

- superquadric modeling software <a href="https://doi.org/10.5281/zenodo.262995"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.262995.svg" style="vertical-align:middle;" alt="DOI"></a>,
- grasping pose computation module <a href="https://doi.org/10.5281/zenodo.263015"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.263015.svg" style="vertical-align:middle;" alt="DOI"></a>.

![](https://raw.githubusercontent.com/giuliavezzani/giuliavezzani.github.io/master/files/grasp-min.png)

[Home page](./)
