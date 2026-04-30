---
title: "About Me"
layout: default
permalink: /pages/about-me/

skills:
  - name: "Unity"
    icon: "fab fa-fw fa-unity"
    badges: ["C#", "Game Dev"]
    text: "Built multiple prototypes and a completed tower defense game."
    years: 1
  - name: "Unreal Engine"
    icon: "fab fa-fw fa-unreal"
    badges: ["C#", "Game Dev"]
    text: "Built multiple prototypes, game demos and a completed rhythm game."
    years: 2
  - name: "Game Design"
    icon: "fas fa-fw fa-gamepad"
    badges: ["Game Mechanics", "Levels", "UI"]
    text: "Designed mechanics, levels, and player feedback loops."
    level_label: "Beginner"
  - name: "Music Production/Game Soundtracks"
    icon: "fas fa-fw fa-music"
    badges: ["Composition", "Production", "soundtrack"]
    text: "Experienced with using Reaper to create music and game soundtracks."
    level_label: "Intermediate"
---

{% include figure image_path="/assets/images/3D 2.png" alt="Game Jam screenshot" %}

{% include download
  title="Download my CV"
  url="/assets/downloads/Project-proposal.pdf"
  button_label="Download CV"
  download="Project-proposal.pdf"
%}

{% include skills skills=page.skills %}

