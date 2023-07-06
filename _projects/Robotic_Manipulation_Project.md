---
layout: page
title: Allegro Hand Teleop in PyDrake
description: 6.4212 Robotic Manipulation course project
img: assets/img/RoboticManipulation_TeleopFig.png
importance: 1
category: work
---

Abstract -- This paper presents the design and implementation of a teleoperation scheme for a multi-finger robotic hand in the Drake simulation environment using human demonstrations captured by a single RGB camera. Specifically, teleoperation of the Allegro Hand was implemented using a custom script to obtain joint kinematics of the human hand via a software called MediaPipe. Moreover, through the addition of kinematic hand synergies in this pipeline, we were able to simplify the degrees of freedom used to control the robotic hand. Currently, full teleoperation is incomplete as we were unsuccessful in grasping and manipulating different objects. In the future, we plan to not only address this limitation but to also apply this teleoperation pipeline to conduct behavior cloning of various manipulation tasks based on human demonstration. Such research is important for the design and control of anthropomorphic prosthetic hands.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/RoboticManipulation_TeleopFig.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example of human (left) teleoperation of the Allegro
Hand (Right). (a) A peace sign. (b) A fist. (c) Grasp closure
of a cube.
</div>

Below is a video recording of our final presentation.

<iframe width="560" height="315" src="https://www.youtube.com/embed/IImbUH8T4I4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

For further details please see our final report below:

<iframe src="../../assets/pdf/Robotic_Manipulation_Project.pdf" width="100%" height="600px"></iframe>
