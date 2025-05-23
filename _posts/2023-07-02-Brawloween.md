---
layout: post
title:  "Brawloween"
role: "Technical Game Designer"
team-size: "Team Size : 3 People"
timeline: "July 2023 - Present"
summary: "A 2D sprite-based fighting game set in a halloween inspired world featuring new takes on classic monsters."
date:   2018-09-04 15:39:40
preview: /assets/BrawloweenPreview.png
---
<p align="center">____________________________________________________________________________________
<video width="640" height="360" autoplay muted loop>
  <source src="/assets/BrawloweenVideos/BrawloweenGameplay.mp4" type="video/mp4">
</video>
</p>
<b>Responsibilities :</b><br>
  - Developed custom editor tools for creating new normal attacks and special moves<br>
  - Documented Instructions for using development tools<br>
  - Programmed core gameplay systems and input buffering system<br>
  - Designed movesets for characters including movement abilties, special moves, and normal attacks

<p align="center">____________________________________________________________________________________</p>
<p align="center">  
<b> Custom Editor Tools</b><br>
<img src="/assets/BrawloweenGifs/NormalAttackCustomEditor.gif"><br>
</p>
One of my responsibilities on the project is to create tools to facilitate our content development. Shown above, is our custom editor tool for creating and editing Normal Attacks and Special Moves. The primary goal of this tool is to be modular, breaking the data into smaller groups. If I just want to edit a Normal Attack's Hitstun then I can just open the "Opponent Frame Data" group and leave all the other groups closed. Additionally, there is a toggle that opens all groups if you want to quickly take a look at the overall move. The editor also hides certain parameters based on context. For example, if a Special Move is not a Launcher, then the Launcher Force and Fall Speed parameters will be hidden because they will not be needed.<br><br>

If you'd like to read more in-depth, here is my <a href="https://docs.google.com/document/d/13dCv29WsFoRbIdVQaPxMXBdBqzNINogZ-KMvsr4hsMQ/edit?usp=sharing"> Move Editor Documentation</a>.<br><br>

<a href="https://docs.google.com/presentation/d/1USMjjvOdRkfbaPvTS6eGCgtBI-I_NxuO56K2gFUEH2Q/edit?usp=sharing"> <img src="/assets/BrawloweenPitchDeck.png"></a><br>
I am also working on designing character movesets for the game. To learn about Clive, the Lycanthrope Boxer check out my <a href="https://docs.google.com/presentation/d/1USMjjvOdRkfbaPvTS6eGCgtBI-I_NxuO56K2gFUEH2Q/edit?usp=sharing"> Pitch Deck</a>. This presentation details both of the character's two styles including their movement abilities and special moves.<br><br>

The unique aspect of Brawloween is that <b>each playable character will have two different Styles</b>, both with <b>different normal attacks, special moves, and movement abilities</b>. A character’s two styles should lead to <b>synergy while still feeling distinct from one another</b>. For Clive, our first playable character, I wanted to differentiate the two styles with their movement options and gameplan.<br><br>

His Boxer style has <b>phenomenal grounded movement</b> whereas his Werewolf style relies on <b>strong aerial movement</b>. The Boxer style has <b>great combo tools</b> but a fairly <b>straight forward gameplan</b> involving <b>strike/throw pressure</b>. The Werewolf style on the other hand has <b>shorter combos</b> but <b>incredible tools for mix-ups</b> such as side-switches, an overhead, an airdash, and a fastfall. 
