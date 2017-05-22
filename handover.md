---
layout: secondary
title: A Novel Pipeline for Bi-manual Handover Task
author: G. Vezzani, M. Regoli, U. Pattacini and L. Natale
---

## Abstract
This paper addresses the problem of bi-manual object handover with a humanoid robot, i.e. the task
of passing objects from one hand to the other. Bi-manual coordination is fundamental for improving
manipulation capabilities of humanoid robots. We propose a novel and effective pipeline that tackles
the problem by using visual and tactile information. Given the object in one of the robot hand (first
hand), the object in-hand pose is estimated by a localization algorithm, which makes use of vision
and tactile information. Then, the estimated pose is used in order to automatically choose a suitable
pose for the second hand among a set of candidates a-priori annotated on the object model. The
selected pose is finally used to accomplish the handover task. The performance of our approach has
been assessed on a real robotic system, the iCub humanoid robot, on a set of objects from the YCB
dataset. Experiments show that the proposed method allows performing proper and reliable handovers
with different every-day objects.
A preprint of the paper will be available soon. [This video](https://www.youtube.com/watch?v=be27-FGU-Sk) shows some examples of successful handovers with the iCub humanoid robot.

The code I developed is available on _github_: <a href="https://zenodo.org/badge/latestdoi/44164737"><img src="https://zenodo.org/badge/44164737.svg" alt="DOI"></a>.


![](https://raw.githubusercontent.com/giuliavezzani/giuliavezzani.github.io/master/files/grasp-min.png)

[Home page](./)
