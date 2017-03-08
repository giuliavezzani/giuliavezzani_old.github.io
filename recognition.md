---
layout: secondary
title: A Novel Bayesian Filtering Approach to Tactile Object Recognition
author: G. Vezzani, N.Jamali, U.Pattacini, G. Battistelli, L. Chisci,  and L. Natale
---

## Abstract

This paper addresses tactile object recognition, i.e. the identification of an object among a set of known objects,
given tactile measurements. The solution of this problem can improve perception capabilities of autonomous robots and
complement vision. Such a system is fundamental for the operation of autonomous robots that are often required to
recognize objects while interacting with the environment. The proposed approach is innovative for three reasons. First,
tactile recognition is cast into a tactile localization problem wherein multiple models are fit to the available measure-
ments and objects are recognized by selecting the model that minimizes the localization error. Second, the measurements
consist only of 3D contact point coordinates, which provide poor information for the recognition task. Lastly, we make use
of a novel and effective filtering algorithm, named Memory Unscented Particle Filter (MUPF), which solves the 6 degree-
of-freedom localization (and recognition) problem recursively by using only contact point measurements. The performance
of the proposed approach has been assessed both in simulation and on a real robotic system equipped with tactile sensors (i.e.,
the iCub humanoid robot). The experiments show that our approach provides good recognition performance and is able
to discriminate objects that are similar even in presence of noisy measurements.

This work has been published in the  Proceeding of the IEEE International Conference on Humanoid Robotics, Cancun,Mexico, 2016.You can download the final version of the manuscript [here](https://github.com/giuliavezzani/giuliavezzani.github.io/raw/master/files/recognition.pdf).

 ![](https://raw.githubusercontent.com/giuliavezzani/giuliavezzani.github.io/master/files/icub-touch.jpg)
 
[Go back to the home page](./)
