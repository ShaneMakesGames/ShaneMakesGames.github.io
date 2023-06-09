---
layout: post
title:  "Recursion Error"
summary: "Technical Game Designer"
date:   2022-10-07 15:39:40
preview: /assets/RecursionErrorPreview.png
---

<iframe width="1280" height="720" src="https://www.youtube.com/embed/OASWarE0Y6E" title="Recursion Error Trailer | Cyber Duck Collective" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

One of my main tasks on this project has been to create a satisfying combat system. My goal was to have three different weapons that each feel powerful but different from each other. But before implementing the other weapons I first had to make hitting enemies feel good. 

**[Game Feel]**

![Picture 1](/assets/RecursionErrorGifs/OldGameplay.gif)

This is what the gameplay looked like back in December 2022. It was functional but there was no visual feedback when you hit an enemy. 

![Picture 2](/assets/RecursionErrorGifs/Hitstop&Shake.gif)

Several changes were made at this point. Now some attacks move the player forwards when they are used. This is going to be more prominent in the Axe than other weapons since it is meant to do more area of effect damage. I added "hitstop" on certain attacks which means that both the player and enemy's animations are paused for a few frames to sell the weight of the hit. During this time the enemy is also shaken around a little. This will only be used on heavier attacks that are supposed to feel really powerful. I also added a visual for enemy's health and damage numbers that pop up when enemies are hit.   

![Picture 3](/assets/RecursionErrorGifs/AnimatedHealthbars.gif)

Now an enemy's healthbar animates instead of simply being set to a new value when they take damage. 


**[The Axe]**

The Axe is a strong and reliable weapon with decent distance and attacks that deal damage over a wide area. It's unique trait is that by holding and then releasing the light attack button you can perform a follow-up attack. 

I learned from playtesting that not a lot of people realized the Axe's follow-up attack existed until we told them about it. There were some people who enjoyed trying to get the perfectly timed version of the follow-up, but others did not use the follow-up attack even after they were told about it. 

To account for this, I did two things. First, I added a training room that is accessible from the main hub at anytime. In this room, you can try out each weapon in a safe environment and there is UI that highlights each weapon's unique features.

<p align="center">
  <img src="/assets/RecursionErrorGifs/TrainingRoom.gif">
</p>

I also changed the input for the follow-up attack. Now, holding the light attack will have you first perform a light attack and then the follow-up attack. However, if you release the button when you see the flash you will get the faster, perfect version of the attack. It is also possible to hold light attack shortly after dashing to skip the light attack, and just do the follow-up attack.

<p align="center">
  <img src="/assets/RecursionErrorGifs/FinalAxeGameplayV2.gif">
</p>

**[Daggers]**

The Daggers are the fastest weapon in the game, allowing you to weave in and out of enemies' reach while slicing them to pieces. The daggers are the only weapon that has a string of light attacks. By pressing the light attack again within a lenient amount of time, you can perform up to two follow-up attacks.  

<p align="center">
  <img src="/assets/RecursionErrorGifs/FinalDaggersGameplayV2.gif">
</p>

**[Gauntlets]**

The Gauntlets are a powerful weapon allowing you to shoot energy from your fists. It is a hybrid melee/ranged weapon for players who want to fight from afar. Holding light attack allows you to aim your attack in any direction and the heavy attack can be used to push enemies back. This weapon is the one that went through the most iteration.

When I first implemented it, the light attack shot a moderately slow projectile and the heavy attack shot a beam that could damage multiple enemies in a line but was very slow to perform. This worked fine, but it did not feel very satisfying to use. I tried making the light attack's projectile move faster and have the heavy attack shoot a slow moving projectile with a wide hitbox. This felt a little bit better, but because both of these attacks were pretty strong our playtesters would simply run away from enemies and whittle them down from afar. This made things far too easy and went against our goal of creating fast-paced combat. So to rememdy this, I changed the heavy attack to an uppercut that pushes enemies away. I then decreased the base damage of the ranged attack but made it so landing a heavy attack empowers your ranged attack for a small amount of time. This ended up encouraging players to stay just out of the enemies' range so they could land an uppercut and then dash away to deal damage with the ranged attack.

<p align="center">
  <img src="/assets/RecursionErrorGifs/FinalGauntletsGameplayV2.gif">
</p>
