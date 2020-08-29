---
layout: splash
ref: main
permalink: /
hidden: true
header:
  overlay_color: "#FFFFFF"
  overlay_filter: "0.4"
  #overlay_image: /assets/images/cover_head.JPG
excerpt: "It’s what you do right now that makes a difference"
intro: 
  - excerpt: 'This place is made for kicking my ass from the couch  
  and to do something productive & creative.' 
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
    url: "/dailylog/"
    btn_class: "btn--primary"
    btn_label: "Read more"      
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
