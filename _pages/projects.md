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
<!--- "commented out"
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
--->
feature_row:
  - image_path: thumb_nail_thumper_robot.jpg
    alt: "Nonprehensile Impulse Manipulator"
    title: "Design and Control of A Nonprehensile Impulse Manipulator"
    excerpt: 'In modern manufacturing industries, autonomously feeding unsorted small components such as bolts and nuts into ongoing robot assembly processes has been a challenging topic for years because most commonly used devices, albeit possess a great processing speed, are not versatile enough to economically adapt to any new parts. In this project, we built a novel part feeder that uses impulse shocks to flip parts into poses more suitable for grasping.\
`Control Under Uncertainty` `Stochastic Modeling` `Learning Control` ' 
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: thumb_nail_tormach.jpg
    alt: "Robot arm with the part to be cutted"
    title: "Robot Subtractive Manufacturing with A High-Speed Spindle"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: thumb_nail_dobot.png
    alt: "Dobot Image"
    title: "Dobot ROS Driver with pySerial"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row type="left" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="left" %}
