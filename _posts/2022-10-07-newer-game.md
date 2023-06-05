---
layout: post
title:  "Recursion Error"
summary: "Technical Game Designer"
date:   2022-10-07 15:39:40
preview: /assets/RecursionErrorPreview.png
---

One of my main tasks on this project has been to create a satisfying combat system. My goal was to have three different weapons that each feel powerful but different from each other. But before implementing the other weapons I first had to make hitting enemies feel good. 

[Game Feel]

![Picture 1](/assets/RecursionErrorGifs/OldGameplay.gif)

This is what the gameplay looked like back in December 2022. It was functional but there was no visual feedback when you hit an enemy. 

![Picture 2](/assets/RecursionErrorGifs/Hitstop&Shake.gif)

Several changes were made at this point. Now some attacks move the player forwards when they are used. This is going to be more prominent in the Axe than other weapons since it is meant to do more area of effect damage. I added "hitstop" on certain attacks which means that both the player and enemy's animations are paused for a few frames to sell the weight of the hit. During this time the enemy is also shaken around a little. This will only be used on heavier attacks that are supposed to feel really powerful. I also added a visual for enemy's health and damage numbers that pop up when enemies are hit.   

![Picture 3](/assets/RecursionErrorGifs/AnimatedHealthbars.gif)

Now an enemy's healthbar animates instead of simply being set to a new value when they take damage. 


[The Axe]

The Axe is a strong and reliable weapon with decent distance and attacks that deal damage over a wide area. It's unique trait is that by holding and then releasing the light attack button you can perform a follow-up attack. 

I learned from playtesting that not a lot of people realized the Axe's follow-up attack existed until we told them about it. There were some people who enjoyed trying to get the perfectly timed version of the follow-up, but others did not use the follow-up attack even after they were told about it. 

To account for this, I did two things. First, I added a training room that is accessible from the main hub at anytime.

// Training Room Gif

I also changed the input for the follow-up attack. Now, holding the light attack will have you first perform a light attack and then the follow-up attack. However, if you release the button when you see the flash you will get the faster, perfect version of the attack. It is also possible to hold light attack shortly after dashing to skip the light attack, and just do the follow-up attack.

<p align="center">
  <img src="/assets/RecursionErrorGifs/FinalAxeGameplayV2.gif">
</p>

[Daggers]


<p align="center">
  <img src="/assets/RecursionErrorGifs/FinalDaggersGameplayV2.gif">
</p>

[Gauntlets]

The Gauntlets are a powerful weapon allowing you to shoot energy from your fists. It serves as the game's ranged weapon option for players who want to fight from afar. Holding light attack allows you to aim your attack in any direction and the heavy attack can be used to push enemies back. This weapon is the one that went through the most iteration.

When I first implemented it, the light attack shot a moderately slow projectile and the heavy attack shot a beam that could damage multiple enemies in a line but was very slow to perform. This worked fine, but it did not feel very satisfying to use. I tried making the light attack's projectile move faster and have the heavy attack shoot a slow moving projectile with a wide hitbox. It still didn't feel quite right. Then I decided to rework aspects from the first iteration. Now the light attack was a hitbox, not a projectile, but it had decent range and the range could be extended by holding the button and aiming your attack. The heavy attack became a short ranged uppercut that pushes enemies back allowing you to get to safety. This version was way more fun however, it ended up being far too strong. Players could lay waste to swarms of enemies without ever getting close enough to take damage themselves.   

<p align="center">
  <img src="/assets/RecursionErrorGifs/FinalGauntletsGameplayV2.gif">
</p>
