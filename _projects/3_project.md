---
layout: page
title: Advancing Stroke Rehabilitation, a Neuroplasticity-Driven Approach
description: My end of (3rd) year disseration project for my Mechatronics and Robotics MEng degree.
img: assets/img/Components_Assembled.jpg
importance: 3
category: work
---

This project involves the design and development of a stroke rehabilitation device aimed at aiding hand recovery during the early stages of stroke rehabilitation. The device leverages 3D printing and Arduino-controlled servo motors to offer a cost-effective, customizable, and accessible solution for mild to medium stroke survivors.

The goal is to develop a practical solution that utalizes neuroplasticity in stroke patients by mimicking hand movements needed for recovery to induce dendritic growth. This device can be used by patients at home to complement traditional rehabilitation methods.

<!-- Include Venobox CSS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/venobox@2.0.3/venobox.min.css">

<!-- Include Venobox JS -->
<script src="https://cdn.jsdelivr.net/npm/venobox@2.0.3/venobox.min.js"></script>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <a class="venobox" data-gall="device-gallery" href="assets/img/Components.jpg" title="Diagram of Components">
            <img src="assets/img/Components.jpg" class="img-fluid rounded z-depth-1" alt="Diagram of Components">
        </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <a class="venobox" data-gall="device-gallery" href="assets/img/Components_Asembly.jpg" title="Partially Built">
            <img src="assets/img/Components_Asembly.jpg" class="img-fluid rounded z-depth-1" alt="Partially Built">
        </a>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <a class="venobox" data-gall="device-gallery" href="assets/img/Components_Completely_Assembled.jpg" title="Complete Device">
            <img src="assets/img/Components_Completely_Assembled.jpg" class="img-fluid rounded z-depth-1" alt="Complete Device">
        </a>
    </div>
</div>
<div class="caption">
    Build Process of the Device
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <a class="venobox" data-gall="device-states" href="assets/img/State1_State2.jpg" title="Two States that the Device has">
            <img src="assets/img/State1_State2.jpg" class="img-fluid rounded z-depth-1" alt="Two States">
        </a>
    </div>
</div>
<div class="caption">
    This is the device in each state.
</div>

Bellow is the device without out the mount and circuitry attached for a better visual. The device has 2 states and two algoritms. Algo 1 will stretch each finger individually and then clench. Algo 2 will stretch all the fingers at once and then clench. These algorithms do each 5 times to save for time during demonstration as these algorithms will normally occur for about 10-15mins depending on the paitent. So a total of a 20 to 30min sessions. Additionally I've displayed the flow diagram. 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <a class="venobox" data-gall="device-flow" href="assets/img/Components_Assembled.jpg" title="Components Without Circuitry Mounted">
            <img src="assets/img/Components_Assembled.jpg" class="img-fluid rounded z-depth-1" alt="Components Without Circuitry">
        </a>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <a class="venobox" data-gall="device-flow" href="assets/img/FlowDiagram.jpg" title="Flow Diagram of Code">
            <img src="assets/img/FlowDiagram.jpg" class="img-fluid rounded z-depth-1" alt="Flow Diagram">
        </a>
    </div>
</div>
<div class="caption">
    Device without circuitry mounted. The flow diagram shows how the device operates.
</div>

Key features include:

    Personalized 3D-printed components for adjustable fit
    Predefined rehabilitation algorithms to target different muscle groups
    Affordable and adaptable design, integrating off-the-shelf electronics
    Iterative prototyping and testing, ensuring user comfort and effectiveness

This device aims to empower caregivers and patients with home-based rehabilitation options, complementing traditional therapy methods. The stroke rehabilitation device provides a low-cost, customizable solution for stroke patients to continue rehabilitation at home. Although challenges like achieving a full hand strech remain, the device complements traditional therapy methods and enhances the patient’s recovery process in theory. This project shows the potential of neuroplasticity-driven rehabilitation technologies to support stroke survivors in their journey to regain hand function at home, additionally hoping to relief pressure off of the UK's NHS.

<script>
    $(document).ready(function(){
        $(".venobox").venobox();
    });
</script>
