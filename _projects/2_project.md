---
layout: page
title: DNS-Server
description: a project with a background image and giscus comments
img: assets/img/PI-DNS_Logo.jpg
importance: 4
category: fun
giscus_comments: true
---

This project focuses on repurposing an old Samsung Galaxy S8 as a DNS server and ad blocker using Pi-Hole. As a student with limited funds, I was looking for a budget-friendly alternative to a Raspberry Pi 4 or Raspberry Pi 5. I had an old phone, which, though a little worn, was still functional and more powerful than a Pi4, so I decided to make it work as a server.

I installed LineageOS and Termux on the device, and then set up Pi-Hole for DNS resolution and ad-blocking functionality. Originally I was installing Pi-hole with Termux packages however there were big issues with opening ports. While it was a bit of a challenge to get it up and running, I ultimately found an official Android version of Pi-Hole, which made installation and maintenance easier.

The project was a learning experience in both software and hardware. The phone now functions as the main DNS server for all my devices, including my partner’s devices, and it handles more traffic than I expected.

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

After a whole day of work setting it up, I had Pi-Hole running on the Galaxy S8. The phone acts as my primary DNS server, filtering out unwanted ads and malicious DNS queries for all the devices on my network. It serves as a robust solution, handling a significant amount of traffic without breaking a sweat, which I wasn’t sure a Pi4 could even handle.

The Pi-Hole setup also ensures security by preventing connections to known malicious domains, adding an extra layer of protection to my network.

In the future, I plan to revisit this setup and containerize Pi-Hole using Docker to further isolate the service and make it easier to maintain and update. I also want to explore alternatives to the Raspberry Pi, like the NanoPC-T4, for more learning about hardware and software integration.

Overall, repurposing the Galaxy S8 as a DNS server has been an incredibly cost-effective solution to meet my needs. This project not only helped me learn more about Linux environments, Android and networking but also proved that with some ingenuity, even older devices can find new life in technical projects.

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
