---
layout: page
title: project 2
description: a project with a background image and giscus comments
img: assets/img/3.jpg
importance: 1
category: master's research
giscus_comments: true
---
<div class="embed-responsive embed-responsive-16by9 mb-4">
    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Ubg4PhAubUY?si=_gbg9ncRS-7hJMle" allowfullscreen></iframe>
</div>

This project showcases the development of an autonomous robotic system designed for cornstalk nitrate monitoring and sensor insertion, aimed at improving agricultural sustainability through precise data collection. The accompanying **ICRA paper video** provides a detailed visual overview of the system’s performance in real-world field environments, highlighting key capabilities such as mobile platform navigation and autonomous sensor insertion and exchange {% cite lee2024autonomous %}.

The system consists of a mobile robot platform (AMIGA), a manipulator arm (xARM), custom gripper for precise sensor insertion and custom sensor maintenance mechanisms for sensor cleaning, calibration, and replacement. In addition, the **Mask R-CNN-based visual servoing system** dynamically adjusts the manipulator’s position to align with cornstalks through visual detection, achieving robust performance despite variations in plant positioning and environment disturbance.


<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/cornbot_1.png" title="example image" class="" %}
  </div>
</div>
<div class="caption">
    Left: Overview of the robotic system components. Right: The robot navigating a cornfield during field testing.
</div>


The custom two-finger gripper features adaptive compliance to handle varying stalk diameters, achieving a 17% increase in insertion success rates. The **funneling mechanism**, highlighted in the thesis presentation {% cite Lee-2024-144865 %}, improves alignment precision by 76%, making the system robust for sensor replacement even with low-precision manipulators.

<div class="row">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/funnel_mechanism.jpg" title="Funneling mechanism for sensor alignment" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/visual_servoing_example.jpg" title="Visual servoing system in action" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    The funneling mechanism (left) enhances alignment precision, while the visual servoing system (right) uses Mask R-CNN to dynamically adjust manipulator position for accurate insertion. Middle: Close-up view of the compliant gripper improving insertion precision.
</div>

The **thesis presentation** elaborates on the motivation of the research followed by the design, integration, and testing of the robotic system. Field testing at Rivendale Farm and Iowa Ames Curtiss Farm demonstrated a 22% improvement in overall sensor insertion performance, underscoring the potential for large-scale deployments to enhance precision farming {% cite Lee-2024-144865 %}.

<div class="embed-responsive embed-responsive-16by9">
    <iframe 
        src="https://andrewcmu-my.sharepoint.com/personal/janicel2_andrew_cmu_edu/_layouts/15/Doc.aspx?sourcedoc={a0241919-2065-4a54-9073-b4df6ec5128b}&amp;action=embedview&amp;wdAr=1.7777777777777777" 
        class="embed-responsive-item"
        frameborder="0" 
        allowfullscreen>
    </iframe>
</div>

<div class="mt-5">
</div>
