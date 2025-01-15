---
layout: page
title: Smith & Nephew Robotics R&D 
description: Sustaining and Improving Surgical Robotic Systems
img: assets/img/cori_thumbnail.jpg
importance: 3
category: work
---

I worked as a **Robotics Product Support Intern** with the **Robotics R&D (Product Support) Team** at **Smith & Nephew** in Pittsburgh from **June 2022 to August 2022**. My work focused on improving the **CORI surgical system**, which assists in knee arthroplasty.

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/cori_intro.png" title="CORI system" class="" %}
  </div>
</div>
<div class="caption">
    (Left) CORI Surgical System. (Right) CORI handheld milling tool.
</div>

The **CORI system** is an image-free surgical platform that provides real-time planning and gap assessment during knee surgeries. It features a **robotic handheld milling tool** for bone preparation, equipped with motors to control the burr's rotation and exposure. My projects targeted critical connectivity and maintenance challenges in this robotic handheld tool. The following sections outline the core components of the project.

### 1. **Bad Exposure Position Sensor (BEPS) Testing**

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/beps_testing.png" title="CORI system" class="" %}
  </div>
</div>
<div class="caption">
    Bad Exposure Position Sensor (BEPS) Testing
</div>

   - Investigated connectivity issues related to the exposure motor by switching from pin connectors to solder cup connections for direct wire attachment.
   - Conducted **pressure leakage tests** and **hipot (high-potential) tests** to ensure electrical safety by measuring leakage current under high voltage.

### 2. **Hipot Test Fixture for Exposure Motor**
   - Designed and fabricated a dedicated test fixture to evaluate the exposure motor independently from the full handpiece assembly.
   - Improved testing accuracy for isolating motor-specific issues.

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/test_fixture.png" title="Test Fixture" %}
    </div>
</div>

<div class="caption">
    (Left) Hipot test fixture to test the exposure motor. (Right) Continuity test fixture design for detecting wiring issues.
</div>

### 3. **Handpiece Electrical Continuity Test Fixture**
   - Developed a fixture to simplify detecting disconnections in the handpiece's 16-wire cable.
   - Designed LED indicators to quickly identify wire continuity issues when the handpiece is connected.

### 4. **Obsolescence Analysis for CORI Components**


<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/silicon_expert.png" title="CORI system" class="" %}
  </div>
</div>
<div class="caption">
    Obsolescence Analysis for CORI Components
</div>

   - Created a monitoring system using **Silicon Expert** to track the status of electrical components in the CORI console.
   - Automated notifications for obsolete or at-risk parts, streamlining the maintenance process for hardware updates.

These contributions improved the reliability and efficiency of the handpiece, enabling faster diagnostics and ensuring the device met stringent safety requirements. This work strengthened my expertise in hardware troubleshooting, electrical safety testing, and system diagnostics. It also reinforced the importance of proactive maintenance and robust design in medical robotics, contributing to more reliable surgical solutions.
