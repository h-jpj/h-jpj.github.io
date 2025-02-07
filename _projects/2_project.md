---
layout: page
title: DNS-Server
description: a project with a background image and giscus comments
img: assets/img/11.jpg
importance: 2
category: work
giscus_comments: true
---

This project is about repurposing my old Samgsung Galaxy S8.
Since I'm a student I have limited funds and at the time the Raspberry PI4 and PI5 where a little out of my price range.
However I still had my old my phone, albiet a little beaten up but still fully functional and stronger than a PI4.
I loaded LinageOS onto it and installed Termux and set up PI-Hole on it. Samgsung didn't make it easy.
It was alot of effort but after a whole day of working on it and getting it to work I later find out that there is an android version of PI-Hole so I ended up using that instead due to being easier to maintain but at least I know two ways to deal with it now!

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/PI-DNS_Logo.jpg" title="Pi-Hole_Dashboard" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Here is an example of the Pi-Hole dashboard acting as an adblocker for know malicious ads and a DNS server.
</div>

All of my machines use this as their main DNS server, including my partners machine and devices. I dont think even the Pi4 could handle all of that!


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Phone-to-DNS.jpg" title="Samsung-Galaxy-S8" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Termux_Logo.jpg" title="Termux" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Showing the Phone plugged into the Home-Lab so it never turns off and the software we used, Termux.
</div>

In the future I will be trying a the Termux method again however I will be using Docker to contain the Pi-Hole software and work from there.
I may also try this with an alternative to a Raspberry-Pi such as NanoPC-T4 in order to learn more about computers, electronics, software and so on.

<!--{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}  -->
