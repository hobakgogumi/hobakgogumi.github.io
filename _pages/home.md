---
title: "Splash Page"
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_filter: "0.5"
  overlay_image: /assets/images/cover_head.jpeg
  actions:
    - label: "Download"
      url: "#test-link"
excerpt: "Bacon ipsum dolor sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`' 
feature_row:
  - image_path: /assets/images/pic_tool.jpg
    title: "Process & Tool Development"
    excerpt: "Automatic tool development for analytical motor analysis"
    url: "/tool/"
    btn_class: "btn--primary"
    btn_label: "Read more"
  - image_path: /assets/images/pic_motor.jpg
    title: "Learning E-Machines"
    excerpt: "Everything related to E-machine... Theoretical, mathematical background and some practical experience"
    url: "/motor/"
    btn_class: "btn--primary"
    btn_label: "Read more"
  - image_path: /assets/images/pic_note.jpg
    title: "Thoughts & Notes"
    excerpt: "My personal notes not to forget things and to organize my unnecessary thoughts"
    url: "/dailylogs/"
    btn_class: "btn--primary"
    btn_label: "Read more"      
---

{% include feature_row id="intro" type="center" %}
{% include feature_row %}
