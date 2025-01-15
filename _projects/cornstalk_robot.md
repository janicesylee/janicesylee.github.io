---

layout: page  
title: Cornstalk Monitoring Robot  
description: 
img: /assets/img/cornbot_thumbnail.jpg  
importance: 1  
category: research  
related_publications: true  

---

<div class="embed-responsive embed-responsive-16by9 mb-4">
    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Ubg4PhAubUY?si=_gbg9ncRS-7hJMle" allowfullscreen></iframe>
</div>
<div class="caption text-center mt-2">
    This video showcases the robotic system’s field demonstration, highlighting key capabilities such as autonomous navigation, visual servoing for alignment, and sensor insertion and replacement {% cite lee2024autonomous %}.
</div>

<!-- 2. Research Introduction + Motivation -->
Sustainable agriculture relies heavily on accurate and efficient monitoring of crop health. Excessive nitrogen fertilizer use can harm the crop and the environment, making precise nitrate monitoring critical for optimizing fertilizer application and improving crop yield. This project addresses this challenge by developing a robust, autonomous robotic system capable of performing nitrate sensor insertion and replacement in cornfields for long-term field deployment. By eliminating the need for manual data collection, this system significantly reduces labor costs and improves the scalability of precision agriculture technologies.

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/cornbot_1.png" title="example image" class="" %}
  </div>
</div>
<div class="caption">
    (Left) Overview of the robotic system components. (Right) The robot navigating a cornfield during field testing.
</div>

<!-- 3. Overall Robotic System Introduction -->
The robotic system consists of a mobile platform (AMIGA) equipped with a 6-DOF manipulator arm (xARM), a compliant gripper, and custom sensor maintenance mechanisms for sensor replacement and calibration. The robot autonomously navigates rows of cornstalks, identifies target stalks, and executes precisely sensor insertion for accurate real-time data collection. Additionally, the system performs autonomous sensor replacement through precise alignment and includes an in-house sensor calibration mechanism. The integration of these components enables seamless operation in agricultural field environments.

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/website_gripper.png" title="gripper image" class="" %}
  </div>
</div>
<div class="caption">
    (Left) Overview of the gripper design and functions. (Right) Coupled sliding mechanism.
</div>

<!-- 4. Gripper Design -->
A key contribution of this project is the **custom two-finger compliant gripper**, designed to adapt to varying cornstalk diameters. This adaptive compliance and two-finger design allows for robust grasping and precise sensor insertion, improving the insertion success rate by 17%. In addition, to avoid collision with other stalks, the gripper is required to be compact. Utilizing the coupled sliding mechanism, the gripper uses a single linear actuator to grasp the stalk, insert the sensor and swap sensors while remaining compact in size. 


<div class="row justify-content-sm-center">
  <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/precise_alignment.png" title="Funneling mechanism for sensor alignment"%}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/funneling_cad.gif" title="Sensor Replacement" %}
    </div>
</div>
<div class="caption">
    (Left) Sensor Replacement Mechanism. (Right) Funneling mechanism.
</div>



<!-- 5. Sensor Replacement + Funneling Mechanism -->
To enable long-term field deployment with minimal human intervention, contact-based sensors must be replaced frequently due to wear and tear. The small size of the sensor and dynamic field conditions make the replacement process require precise alignment, which is particularly challenging when using low-precision manipulators. The funneling mechanism utilizing t-shaped tapered extrusion was developed to address these challenges by compensating for external disturbances and manipulator inaccuracies. This mechanism improves alignment precision by 76%, guiding the sensor to the insertion point with minimal reliance on perception and hardware control. As a result, the system ensures consistent and reliable sensor replacement, even in unstructured outdoor environments.


<div class="row">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/pbvs.png" title="Visual servoing system in action" %}
    </div>
</div>
<div class="caption">
    (Left) Visual Detection. (Right) Position-baed Visual Servoing Controller
</div>

<!-- 6. Cornstalk Visual Detection + Visual Servoing -->
For precise sensor insertion despite  varying field conditions and a dynamic robot base, the system incorporates a **Mask R-CNN-based visual detection and visual servoing system**. This system detects and tracks cornstalks in real time, dynamically adjusting the manipulator’s position to ensure accurate insertion. The position-based visual servoing controller compensates for variations in cornstalk height, orientation, and wind-induced motion.

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/motion_sequence2.png" title="Motion sequence of the robotic system." %}
    </div>
</div>
<div class="caption">
    Motion sequence of the robotic system.
</div>

<!-- 7. Field Testing -->
The system was extensively tested in both lab and field environments. Field deployments at **Rivendale Farm** and **Iowa Ames Curtiss Farm** demonstrated the robot’s ability to navigate uneven terrain and adapt to real-world agricultural conditions. The field tests showed a **22% improvement** in overall sensor insertion performance compared to previous prototypes, validating the system's robustness and reliability for large-scale agricultural applications.

<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/evaluation.png" title="Field evaluation of the robotic system." %}
    </div>
</div>
<div class="caption">
    Field evaluation of the robotic system.
</div>

<!-- 8. Thesis Presentation -->
The **thesis presentation** provides a detailed overview of the iterative design and development process that led to the final robotic system. It covers system integration, experimental evaluations, and key insights gained from field testing. The presentation highlights the project’s contributions to precision agriculture and its potential impact on sustainable farming practices {% cite Lee-2024-144865 %}.

<div class="embed-responsive embed-responsive-16by9">
    <iframe 
        src="https://1drv.ms/p/c/3013cfb7a18bbd2f/IQROiwi-ukN3SLD-ZOk0ITAQAYBwBhlYpXz7PruigPEW9xw" width="402" height="327" frameborder="0" scrolling="no"
        class="embed-responsive-item"
        frameborder="0" 
        allowfullscreen>
    </iframe>
</div>


<div class="mt-5">
</div>


