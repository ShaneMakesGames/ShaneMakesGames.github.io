---
layout: post
title:  "Digital Janitors"
role: "Technical Game Designer"
context: "Game Released on Steam"
team-size: "Team Size : 6 People"
timeline: "November 2019 - October 2021"
summary: "Digital Janitors is an action-packed desktop defense game where hackers have taken your employer’s network hostage."
date:   2023-06-04 15:39:40
preview: /assets/DigitalJanitorsPreview.png
---
<p align="center">____________________________________________________________________________________</p>
<p align="center">
<iframe width="720" height="405" src="https://www.youtube.com/embed/ZgYnhckP1VA" title="Digital Janitors Launch Trailer" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Responsibilities : <br>
  - Designed and programmed 30 enemy types<br>
  - Designed and programmed 15 power-up abilities<br>
  - Designed and programmed 3 boss fights<br>
  - Wrote documentation on designs<br><br>

The gameplay core of Digital Janitors consists of sorting secure folders or malware into either the secure drive or recycling bin respectively. The player interacts with folders using their mouse cursor, making the game play closer to an aim trainer than a game with a traditional combat system. Folders in Digital Janitors are the game's equivalent of enemy types.

Since the premise of the game is to simulate a computer desktop in the 90s, it lives or dies by its immersion. It does not to be perfectly realistic to the setting, but it needs to recreate the image or memory of that setting that a player has in their mind. If something happens that breaks the player out of this reality then we have failed.<br>
In order to maintain this image, there are a few constants that all folders follow :<br>
  - Hover and Selection states (When hovering over a folder or selecting it, it's sprite changes)<br>
  - If a folder is "unlocked", it can be picked up and sorted in the secure drive or recycling bin<br>
  - All folders are either a secure folder or malware<br>
  - All folders are worth exactly one unit of space (Can be seen on the bar at the bottom of the screen. When this fills up, it is a game over)<br><br>

With these contrainsts I grouped folder types into four groups : Moving, Locked, Elusive, and Aggresive.


<video width="640" height="360" autoplay muted loop>
  <source src="/assets/DigitalJanitorsVideos/RunawayFolder.mp4" type="video/mp4">
</video>
  
</p>
