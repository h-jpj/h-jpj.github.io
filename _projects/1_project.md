---
layout: page
title: Home-Lab
description: Media-Server, Cloud-Storage, VPN, and more.
img: assets/img/12.jpg
importance: 4
category: fun
---

This project is about creating a Home-Lab. 
This will host all of my media, act as a cloud storage using (MariaDB a fork of MySQL), video game server and more.


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
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Home-Lab.jpg" title="Home-Lab" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The server is a refurbished HP-EliteDesk 800 G3 SFF, which I've repurposed as a home server.
</div>

The refurished HP-EliteDesk 800 G3 SFF is a great choice for a home server due to its processor being more than adaquate for its purpose, 4 ram slots (right now we have 24gb), and having 3 sata slots making its ample for a first starter server. 
It's also relatively quiet, making it an ideal choice since it sits in my room right now.
Running debian 12 ssh server and using Wireguard to secure the server and allow remote access to the server from multiple devices.
It's a great way to learn about server management, networking, linux and cyber security.

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

Currently I'm hosting a factorio server for myself and friends, this game will change depending on what we want to play.
I'm also using rsync for backups of the server data, this allows me to easily transfer the data to another location in case of a failure.
I have a bash script that will run the rsync command "rsync -av --delete /drivea/ /driveb/" once per week to ensure both drives are synced.

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
