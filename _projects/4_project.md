---
layout: page
title: Custom Pokemon Game
description: Custom Pokémon game featuring new abilities, mega Pokémon sprites, and community-driven enhancements.
img: assets/img/emeraldlogo.jpg
importance: 3
category: fun
---

This project is a custom Pokémon game based on the RHH Expansion Team's fork of the Pokeemerald Decomp Project by the PRET team. I extended the base game by adding new features and mechanics, contributing custom code, and working with community-driven branches to improve the game's functionality. 
My goal was to learn and understand the C language more whilst 
also trying to get comfortable working with large code bases.

My work includes implementing new abilities inspired by the Elite Redux project and importing five mega Pokémon sprites, which we integrated into the game. Additionally, I also wrote custom scripts to support unique events and mechanics.

A significant part of the learning process involved navigating the complexities of C language development, working within a large codebase (50k+ files), and utilizing community resources like feature branches and pull requests to troubleshoot and enhance the contributions.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/DayNightCycle.jpg" title="DayNightCycle" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/emeraldlogo.jpg" title="emeraldlogo" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/MegaandMove_Display.jpg" title="MegaandMove_Display" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>

Working with a 50k+ file game required a steep learning curve, especially when it came to understanding how the various systems interacted. I had to understand concepts like memory management, pointer manipulation, and modular design. I feel I've adapted reasonabley well.

One of the most complex aspects was managing merge conflicts, which was.... stressfull to say the least, and integrating community-driven feature branches without breaking existing functionality. I spent significant time debugging issues related to event triggers, sprite handling, and ability mechanics (displayed bellow). Overall I think the debugging was key helping me improve my skills.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Codebase_Display.jpg" title="Codebase_Display" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/githubcodebase.jpg" title="githubcodebase" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

Working with such a large codebase gave me a deeper understanding of both development and the intricacies of open-source collaboration. The project forced me to adopt a disciplined approach to version control, code reviews, documentation and learning to use git in general.
Overall I believe I got what I wanted out of the project. A game I could play and a better understanding of programming.
