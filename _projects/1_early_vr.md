---
layout: page
title: VR Tracking System
description: First experiments with Virtual Reality and custom hardware
img: assets/img/projects/sensors.jpeg
importance: 2
category: early projects
---

In 2014, I acquired my first VR helmet and began experimenting with it. It quickly became apparent to me and my friends that while the technology was incredibly cool, there was a vast untapped potential, particularly in the input system.

The original Oculus Rift DK1 we obtained was 3DOF, meaning it only tracked the user's head rotation. Moreover, there were no input devices available apart from a mouse and keyboard, which imposed significant limitations. Most games were mere roller coasters without any player interaction.

We decided to create our own controller. I purchased two YEI 3-space IMU sensors and developed a simple self-made arm-tracking controller. One sensor was fixed on an elbow, another one placed in a palm.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/oculus_rift.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/yei3-sensor.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Oculus Rift DK1 and YEI 3-space IMU sensor.
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/early-vr-video.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>

Eventually, I sold this setup to a friend who established a small kiosk in a mall, allowing visitors to experience the system and engage in zombie shooting games.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/zombies.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>

Nowadays modern VR hardware uses 6DOF tracking and proper controllers out of the box. While the entire setup and games may seem outdated today, the process of creating a complete VR project with experimental hardware was an valuable experience for me.