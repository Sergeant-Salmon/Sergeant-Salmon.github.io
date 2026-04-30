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

<div style="display:flex; flex-wrap:wrap; gap:2rem; align-items:flex-start;">

  <!-- LEFT: text content -->
  <div style="flex:1 1 250px; min-width:250px;">
    <h2>Summary</h2>
    <p>
      Passionate and motivated Game Design student going into my second year at Ulster University. 
      Recently completed a team project and am advancing my skills in C#, Unity development and seeking experience.
      Skilled in scripting, game audio, soundtracks, and level design. Excited about learning more C# scripting.
    </p>
  </div>

  <!-- RIGHT: video/content area -->
  <div style="flex:1 1 250px; min-width:250px;">
    <!-- Replace this placeholder with a YouTube iframe or a video tag -->
    {% include video id="(jYgJjNNnNqU)" provider="youtube" %}
  </div>

</div>

{% include skills skills=page.skills %}

