---
layout: splash
title: "Projects"
permalink: /projects/
author_profile: false
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: topbar_image.jpg
  caption: "Image credit: [**Greg Dunn**](https://www.gregadunn.com)"
    
feature_row_farmhand:
  - image_path: thumb_nail_farmhand.gif
    alt: "Strawberry Pollination Robot"
    title: "Towards Closing the Loop in Robotic Pollination for Indoor Farming via Autonomous Microscopic Inspection"
    excerpt: 'This work proposes a novel robotic system for indoor farming. The proposed hardware combines a 7-degree-of-freedom (DOF) manipulator arm with a custom end-effector, comprised of an endoscope camera, a 2-DOF microscope subsystem, and a custom vibrating pollination tool; this is paired with algorithms to detect and estimate the pose of strawberry flowers, navigate to each flower, pollinate using the tool, and inspect with the microscope.'
    url: "https://saferoboticslab.me.gatech.edu/research/towards-robotic-pollination/"
    btn_label: "project page"
    btn_class: "btn--primary"

feature_row_parc:
  - image_path: thumb_nail_parc.gif
    alt: "PARC Drifting Image"
    title: "Goal-Reaching Trajectory Design Near Danger with Piecewise Affine Reach-avoid Computation"
    excerpt: 'The algorithm seeks to compute trajectory plans for which a robot is guaranteed to reach a goal and to avoid obstacles in the specific near danger case, also known as a narrow gap, where the agent starts near the goal, but must navigate through tight obstacles that block its path.'
    url: "https://saferoboticslab.me.gatech.edu/research/parc/"
    btn_label: "project page"
    btn_class: "btn--primary"

feature_row_thumper:
  - image_path: thumb_nail_thumper_robot.gif
    alt: "Nonprehensile Impulse Manipulator"
    title: "Design and Control of A Nonprehensile Impulse Manipulator"
    excerpt: 'In modern manufacturing industries, autonomously feeding unsorted small components such as bolts and nuts into ongoing robot assembly processes has been a challenging topic for years because most commonly used devices, albeit possess a great processing speed, are not versatile enough to economically adapt to any new parts. In this project, we built a novel part feeder that uses impulse shocks to flip parts into poses more suitable for grasping.' 
    # url: "https://www.linkedin.com/posts/kongc2_robotics-research-activity-7038741450318073856-GMZA?"
    # btn_label: "demo video"
    # btn_class: "btn--primary"
    url: "https://ieeexplore.ieee.org/abstract/document/10156322"
    btn_label: "paper link"
    btn_class: "btn--primary"

feature_row_tormach:
  - image_path: thumb_nail_tormach.gif
    alt: "Robot arm with the part to be cutted"
    title: "Robot Subtractive Manufacturing with A High-Speed Spindle"
    excerpt: 'This is a python library designed for subtractive manufacturing applications using the Tormach ZA6 robotic arm, integrated with a high-speed spindle and an ATI Force/Torque sensor. The library offers functions for calibrating the workspace, assessing shape feasibility by checking for singularities and joint limits, and determining optimal part placement. It includes code for generating Cartesian path profiles and solving for joint angle trajectories using quadratic programming, enabling precise, closed-loop force control and efficient path planning for manufacturing tasks.'
    url: "https://github.com/kczttm/tormach_za6_subtractive_mftg"
    btn_label: "code"
    btn_class: "btn--primary"
  
feature_row_dobot:
  - image_path: thumb_nail_dobot.png
    alt: "Dobot Image"
    title: "Dobot ROS Driver with pySerial"
    excerpt: 'This project involved a low level ROS1 driver for Dobot v1.0. The functionality includes the reading and controlling of joint angles, forward kinematics, inverse kinematics, integration with usb webcam.'
    url: "https://github.com/kczttm/ROS_dobot_driver"
    btn_label: "code"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row_farmhand" type="left" %}

{% include feature_row id="feature_row_parc" type="left" %}

{% include feature_row id="feature_row_thumper" type="left" %}

{% include feature_row id="feature_row_tormach" type="left" %}

{% include feature_row id="feature_fow_dobot" type="left" %}

