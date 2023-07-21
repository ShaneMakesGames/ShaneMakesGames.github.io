---
layout: post
title:  "Recursion Error"
summary: "Role : Technical Game Designer"
date:   2022-10-07 15:39:40
preview: /assets/RecursionErrorPreview.png
---
Game Design & Production Senior Project

Team Size : 17 People

September 2022 - June 2023

Recursion Error is a roguelike hack-and-slash set in an original science-fantasy world.
______________________________________________________________________________________________________________________________________________________________________________________________________________________________

<video width="640" height="360" autoplay muted loop>
  <source src="/assets/RecursionErrorVideos/RecursionError_Role.mp4" type="video/mp4">
</video>


My primary focus on this project was on the playable weapons. I designed three weapons that encourage different playstyles while maintaining similar power levels. As a technical game designer, my responsibilities included creating design documents, coding the weapon mechanics, collaborating with art and animation teams, implementing attack animations, and tweaking weapon parameters such as attack speeds and damage amounts based on playtest data. 

<video width="640" height="360" autoplay muted loop>
  <source src="/assets/RecursionErrorVideos/RecursionError_Axe.mp4" type="video/mp4">
</video>


The Axe is a strong and reliable weapon with decent distance and attacks that deal damage over a wide area. It's unique trait is that by holding and then releasing the light attack button you can perform a follow-up attack. 

I learned from playtesting that not a lot of people realized the Axe's follow-up attack existed until we told them about it. To account for this, I did two things. 

First, I added a training room that is accessible from the main hub at anytime. In this room, you can try out each weapon in a safe environment and there is UI that highlights each weapon's unique features. I also changed the input for the follow-up attack. Now, holding the light attack will have you first perform a light attack and then the follow-up attack. However, if you release the button when you see the flash you will get the faster, perfect version of the attack.


<video width="640" height="360" controls autoplay muted loop>
  <source src="/assets/RecursionErrorVideos/RecursionError_Daggers.mp4" type="video/mp4">
</video>


The Daggers are the fastest weapon in the game, allowing you to weave in and out of enemies' reach while slicing them to pieces. The daggers are the only weapon that has a string of light attacks. By pressing the light attack button again within a lenient amount of time, you can perform up to two follow-up attacks.  

<video width="640" height="360" controls autoplay muted loop>
  <source src="/assets/RecursionErrorVideos/RecursionError_Gauntlets.mp4" type="video/mp4">
</video>


The Gauntlets are a powerful weapon allowing you to shoot energy from your fists. It is a hybrid melee/ranged weapon for players who want to fight from afar. Holding light attack allows you to aim your attack in any direction and the heavy attack can be used to push enemies back. This weapon is the one that went through the most iteration. 

At first the ranged attacks were far too strong, leading to playtesters running away and defeating enemies without ever taking damage. This made things far too easy and went against our goal of creating fast-paced combat. So to rememdy this, I changed the heavy attack to an uppercut that pushes enemies away. I then decreased the base damage of the ranged attack but made it so landing a heavy attack empowers your ranged attack for a small amount of time. This ended up encouraging players to stay just out of the enemies' range so they could land an uppercut and then dash away to deal damage with the ranged attack.

If you'd like to read more in-depth, here is my <a href="https://docs.google.com/document/d/1bT9IFHqPR0wT22lfVg5XTb69fw_1GM0wqV9EgFpAeLM/edit?usp=sharing"> Weapon Design Document</a>.
