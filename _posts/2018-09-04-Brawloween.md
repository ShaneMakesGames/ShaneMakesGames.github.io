---
layout: post
title:  "Brawloween"
role: "Technical Game Designer"
team-size: "Team Size : 3 People"
timeline: "July 2023 - Present"
summary: "A 2D sprite-based fighting game set in a cartoonish, halloween inspired world featuring new takes on classic monsters."
date:   2022-09-04 15:39:40
preview: /assets/RecursionErrorPreview.png
---
<p align="center">____________________________________________________________________________________</p>
<p align="center">  

<b>Responsibilities :</b><br>
  - Created custom editor tools for creating new normal attacks and special moves
 
  - Designed movesets for 3 weapons that encourage different playstyles<br>
  - Wrote documentation on weapon designs<br>
  - Programmed base weapon functionality and unique weapon mechanics<br>
  - Tweaked weapon parameters such as attack speeds and damage amounts based on playtest data<br>
  - Collaborated with art and animation teams on the look of the weapons and attacks<br>
  - Implemented attack animations and hitboxes<br><br>

I strived to create a fast-paced combat system that is easy to pick up but still rewards player skill. To keep things simple, there are three main actions you can take during combat besides basic movement: Light attack, Heavy attack, and Dash. Each weapon has a different light and heavy attack, though your dash remains the same. Dashing grants a quick burst of speed and provides brief invulnerability, allowing you to evade enemy attacks with it. This basic control scheme makes it easy to play for the first time and start defeating enemies, however it still allows for depth in other ways. For example, multiple weapons have unique or modified attacks accessed by holding and releasing the light attack button with proper timing instead of just pressing it.
____________________________________________________________________________________
<br><br>

<b> Visual Feedback</b>
<img src="/assets/RecursionErrorGifs/VisualFeedback.gif">
Throughout the course of development, the combat system went through a number of changes, most notably in regard to visual feedback. At first, I did not want to display enemy healthbars or damage numbers from attacks because I was worried about screen clutter. But after trying it out I realized not only was it important information to have available, but it also made the game feel better to play. Employing this, along with screen shake, hit stop, and attack pushback went a very long way in making attacks feel more powerful. Originally enemies’ attacks would not be interrupted when they took damage. I wanted the game to be somewhat challenging and thought that just having a dash with i-frames would be enough defensively. This ended up punishing players for attacking enemies head-on, which went directly against the encouraged playstyle of the axe. After adding attack interruption the game did become a little easier, but more importantly it felt more fair for the player.
____________________________________________________________________________________
<br><br>

<b> The Axe</b><br>
<video width="640" height="360" autoplay muted loop>
  <source src="/assets/RecursionErrorVideos/RecursionError_Axe.mp4" type="video/mp4">
</video>
<br>
The Axe is a strong and reliable weapon with attacks that deal solid damage over a wide area. It encourages a brawler kind of playstyle, facing groups of enemies head on and cutting them down multiple at a time with sweeping attacks. Its unique trait is that by holding and then releasing the light attack button you can perform a follow-up attack. <br><br>

I learned from playtesting that not a lot of people realized the Axe's follow-up attack existed until we told them about it. To account for this, I did two things. <br><br>

First, I added a training room that is accessible from the main hub at any time. In this room, you can try out each weapon in a safe environment and there is UI that highlights each weapon's unique features. I also changed the input for the follow-up attack. Now, holding the light attack will have you first perform a light attack and then the follow-up attack. However, if you release the button when you see the flash you will get the faster, “perfect” version of the attack.
____________________________________________________________________________________
<br><br>

If you'd like to <b>read more</b> in-depth, here is my <a href="https://docs.google.com/document/d/1bT9IFHqPR0wT22lfVg5XTb69fw_1GM0wqV9EgFpAeLM/edit?usp=sharing"> Weapon Design Document</a>.<br>
Want to <b>see my code samples</b> from the project, they are here : <a href="https://github.com/ShaneMakesGames/Code-Samples/tree/main/Recursion%20Error"> Recursion Error Code Samples</a>.<br>
Or if you'd like to <b>play the game</b> yourself, here is the <a href="https://shanegamedev.itch.io/recursion-error"> Itch.io Page</a>.
</p>
