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
<iframe width="720" height="405" src="https://www.youtube.com/embed/OASWarE0Y6E" title="Recursion Error Trailer | Cyber Duck Collective" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

My primary focus on this project was on the playable weapons. I designed three weapons that encourage different playstyles while maintaining similar power levels. As a technical game designer, my responsibilities included creating design documents, coding the weapon mechanics, collaborating with art and animation teams, implementing attack animations, and tweaking weapon parameters such as attack speeds and damage amounts based on playtest data.   

From the beginning my goal was to have three playable weapons in order to keep a manageable scope while still allowing for different playstyles. I wanted to create a fast-paced combat system that is easy to pick up but rewards players who take more time learning its nuances. To keep things simple, there are three main actions you can take during combat besides basic movement: Light attack, Heavy attack, and Dash. Each weapon has a different light and heavy attack, though your dash remains the same. It travels a moderate distance with a quick burst of speed and offers invulnerability for a brief moment at the start of the animation. This basic control scheme makes it easy to play for the first time and start defeating enemies, however it still allows for more depth in other ways. For example, multiple weapons have unique or modified attacks accessed by holding and releasing the light attack button with proper timing instead of just pressing it.
<br>

<img src="/assets/RecursionErrorGifs/VisualFeedback.gif">

Throughout the course of development, the combat system went through a number of changes, most notably in regard to visual feedback. At first, I did not want to display enemy healthbars or damage numbers from attacks because I was worried about screen clutter. But after trying it out I realized not only was it important information to have available, but it also made the game feel better to play. Employing this, along with screen shake, hit stop, and attack pushback went a very long way in making attacks feel more powerful. Originally enemies’ attacks would not be interrupted when they took damage. I wanted the game to be somewhat challenging and thought that just having a dash with i-frames would be enough defensively. This ended up punishing players for attacking enemies head-on, which went directly against the encouraged playstyle of the axe. To fix this I changed it so most attacks of the weapons’ attacks will interrupt an enemy’s attack with the exception of the ranged attacks and additionally the brute enemy’s attacks cannot be interrupted. 
<br>

<video width="640" height="360" autoplay muted loop>
  <source src="/assets/RecursionErrorVideos/RecursionError_Axe.mp4" type="video/mp4">
</video>

The Axe is a strong and reliable weapon with decent distance and attacks that deal damage over a wide area. It encourages a brawler kind of playstyle, facing groups of enemies head on and cutting them down multiple at a time with sweeping attacks. Since it is the starting weapon, I wanted it to make players feel powerful. To achieve this, I gave it’s attacks wide hitboxes and relatively high damage. Its unique trait is that by holding and then releasing the light attack button you can perform a follow-up attack. 

I learned from playtesting that not a lot of people realized the Axe's follow-up attack existed until we told them about it. To account for this, I did two things. 

First, I added a training room that is accessible from the main hub at any time. In this room, you can try out each weapon in a safe environment and there is UI that highlights each weapon's unique features. I also changed the input for the follow-up attack. Now, holding the light attack will have you first perform a light attack and then the follow-up attack. However, if you release the button when you see the flash you will get the faster, “perfect” version of the attack.
<br>

<video width="640" height="360" autoplay muted loop>
  <source src="/assets/RecursionErrorVideos/RecursionError_Daggers.mp4" type="video/mp4">
</video>

The Daggers are the fastest weapon in the game, allowing you to weave in and out of enemies' reach while slicing them to pieces. The dagger’s attacks do not have large hitboxes so to be proficient with them, you must make use of dashing for both movement and defense like a true assassin. They are the only weapon that has a string of light attacks. By pressing the light attack button again within a lenient amount of time, you can perform up to two follow-up attacks. The design of the daggers stayed consistent throughout development, but it did take a good deal of tweaking to balance the damage and speed of its attacks. 

At first the total duration of the dagger’s attacks was too long, making it difficult to react to an enemy’s attack and dodge it if you had just attacked. I ended up making the first two light attacks in the dagger’s string very quick, while the third and final attack has more recovery but deals more damage. This way when using the daggers, you can attack twice and likely still be able to dodge any incoming attacks or get greedy and go for all three hits, leaving yourself more vulnerable to other enemies’ attacks.
<br>

<video width="640" height="360" autoplay muted loop>
  <source src="/assets/RecursionErrorVideos/RecursionError_Gauntlets.mp4" type="video/mp4">
</video>

The Gauntlets are a powerful weapon allowing you to shoot energy from your fists. It is a hybrid melee/ranged weapon for players who want to fight from afar. Holding the light attack button allows you to aim your attack in any direction and the heavy attack can be used to push enemies back. This weapon is the one that went through the most iteration. 

At first the ranged attacks were far too strong, leading to playtesters running away and defeating enemies without ever taking damage. This made things far too easy and went against our goal of creating fast-paced combat. So to remedy this, I changed the heavy attack to an uppercut that pushes enemies away. I then decreased the base damage of the ranged attack but made it so landing a heavy attack empowers your ranged attack for a small amount of time. This ended up encouraging players to stay just out of their enemies' range so they could land an uppercut and then dash away to deal damage with the ranged attack.


If you'd like to read more in-depth, here is my <a href="https://docs.google.com/document/d/1bT9IFHqPR0wT22lfVg5XTb69fw_1GM0wqV9EgFpAeLM/edit?usp=sharing"> Weapon Design Document</a>.

Want to see my code samples from the project, they are here : <a href="https://github.com/ShaneMakesGames/Code-Samples/tree/main/Recursion%20Error"> Recursion Error Code Samples</a>.

Or if you'd like to play the game yourself, here is the <a href="https://shanegamedev.itch.io/recursion-error"> Itch.io Page</a>.
