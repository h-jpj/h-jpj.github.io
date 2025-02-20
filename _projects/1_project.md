---
layout: page
title: Home-Lab
description: Media-Server, Cloud-Storage, VPN, and more.
img: assets/img/Home-Lab.jpg
importance: 4
category: Personal
---

This Home-Lab serves as an all-in-one server hosting solution for various applications, including a media server, cloud storage, and a VPN. The system is built on a HP EliteDesk 800 G3 SFF, offering an affordable, efficient setup for personal use. Great for a first server.

Key components include:

    Jellyfin for media streaming, handling all media files that I’ve archived (e.g., DVDs, BluRays).
    Nextcloud for cloud storage, file sharing, calendar management, and notes.
    A Factorio game server that can be swapped for other games depending on the need.

I’m also utilizing MariaDB (a fork of MySQL) to handle data management for Nextcloud and other associated services.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Jellyfin_Logo.jpg" title="Jellyfin Logo" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Home-Lab.jpg" title="Home-Lab" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Nextcloud_Logo.jpg" title="Nextcloud Logo" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The centre image displays the server, the left image is Jellyfin, and the right image is Nextcloud. These are two of the main pieces of software
    that I use on my home server. Jellyfin is used for streaming media I've burnt, while Nextcloud is used for file sharing, calenders, and notes.
</div>

Hardware & Software Setup

The server is powered by a refurbished HP EliteDesk 800 G3 SFF:

    Processor: i5 VPRO 7th gen.
    Memory: 24GB of ddr4 RAM installed (with 4 slots available for future upgrades).
    Storage: 3 SATA slots. Boot drive, 2 hdds and a spare nvme slot.
    Noise: Quiet operation makes it a perfect fit in my bedroom.
    Power Consumption: Low power consumption and has wake-on lan when conserve power more.

Running Debian 12 as the OS, the server is accessible remotely via WireGuard VPN, ensuring secure access to files and applications across multiple devices.

This setup is an excellent opportunity for me to learn about server management, databasing, networking, Linux administration, and cybersecurity.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Factorio_Logo.jpg" title="Current Hosted Game Server" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Rsync_Logo.jpg" title="Rsync_Logo" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This shows the current game server hosted and our backup software.
</div>

Backup Strategy:

I use rsync to back up my server’s data regularly. A custom bash script runs every week, ensuring that my data is consistently backed up to another storage drive. The backup command used is:

rsync -av --delete /drivea/ /driveb/

This command syncs the contents of one drive to another, ensuring redundancy in case of a hardware failure.

This Home-Lab setup not only serves as a functional server for various applications but also offers a hands-on learning experience in server administration, security, and automation. It’s an ongoing project that I can continue to expand, incorporating more tools and software as I learn new concepts in system management.

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
