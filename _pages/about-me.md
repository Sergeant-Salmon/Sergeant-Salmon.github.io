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
    icon: "fab fa-fw fa-unrealengine"
    badges: ["C#", "Game Dev"]
    text: "Built multiple prototypes and a completed tower defense game."
    years: 1
  - name: "Game Design"
    icon: "fas fa-fw fa-gamepad"
    badges: ["Game Mechanics", "Levels", "UI"]
    text: "Designed mechanics, levels, and player feedback loops."
    level_label: "Beginner"
---

{% include figure image_path="/assets/images/3D 2.png" alt="Game Jam screenshot" %}

{% include download
  title="Download my CV"
  url="/assets/downloads/Project-proposal.pdf"
  button_label="Download CV"
  download="Project-proposal.pdf"
%}

{% include skills skills=page.skills %}

{% include google-form
  title="Contact Me"
  src="https://docs.google.com/forms/d/e/1FAIpQLSc5ZDOFTuEht1AUqxiuNxkIDqzZFYIlEGJH70j9hRmIchEYgw/viewform?usp=sharing&ouid=111142779049640651967"
  height="800"
%}
