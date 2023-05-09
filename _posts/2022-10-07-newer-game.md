---
layout: post
title:  "Recursion Error"
summary: "Technical Game Designer"
date:   2022-10-07 15:39:40
preview: /assets/RecursionErrorPreview.png
---

One of my main tasks on this project has been to create a satisfying combat system. My goal was to have three different weapons that each feel powerful but different from each other. But before implementing the other weapons I first had to make the Axe feel good to use. 

[Game Feel]

![Picture 1](/assets/RecursionErrorGifs/AnimatedHealthbars.gif)
![Picture 2](/assets/RecursionErrorGifs/Hitstop&Shake.gif)



[The Axe] 
The Axe is a strong and reliable weapon with decent distance and attacks that deal damage over a wide area. It's unique trait is that by holding and then releasing the light attack button you can perform a follow-up attack. 

I learned from playtesting that not a lot of people realized the Axe's follow-up attack existed until we told them about it. There were some people who enjoyed trying to get the perfectly timed version of the follow-up, but others did not use the follow-up attack even after they were told about it. 

To account for this, I did two things. First, I added a training room that is accessible from the main hub at anytime.

(Show Gif)

I also changed the input for the follow-up attack. Now, holding the light attack will have you first perform a light attack and then the follow-up attack. However, if you release the button when you see the flash you will get the faster, perfect version of the attack. It is also possible to hold light attack shortly after dashing to skip the light attack, and just do the follow-up attack.

(Show Gif)

[Daggers]



[Gauntlets]
The Gauntlets are a powerful weapon allowing you to shoot energy from your fists. It serves as the game's ranged weapon option for players who want to fight from afar. Holding light attack allows you to aim your attack in any direction and the heavy attack can be used to push enemies back. This weapon is the one that went through the most iteration.

When I first implemented it, the light attack shot a moderately slow projectile and the heavy attack shot a beam that could damage multiple enemies in a line but was very slow to perform. This worked fine, but it did not feel very satisfying to use. I tried making the light attack's projectile move faster and have the heavy attack shoot a slow moving projectile with a wide hitbox. It still didn't feel quite right. Then I decided to rework aspects from the first iteration. Now the light attack was a hitbox, not a projectile, but it had decent range and the range could be extended by holding the button and aiming your attack. The heavy attack became a short ranged uppercut that pushes enemies back allowing you to get to safety. This version was way more fun however, it ended up being far too strong. Players could lay waste to swarms of enemies without ever getting close enough to take damage themselves.   
