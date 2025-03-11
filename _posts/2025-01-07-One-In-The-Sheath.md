---
layout: post
title:  "One In The Sheath"
role: "Technical Game Designer"
team-size: "Team Size : 3 People"
timeline: "January 2025 - February 2025"
summary: "A score-attack action game. Both you and your enemies will die from a single attack. Using your dash-attack spends a resource that can be regained by killing enemies or parrying projectiles."
date:   2017-09-04 15:39:40
preview: /assets/1SheathPreview.png
---
<p align="center">____________________________________________________________________________________</p>
<p align="center">  
<video width="640" height="360" autoplay muted loop>
  <source src="/assets/BrawloweenVideos/BrawloweenGameplay.mp4" type="video/mp4">
</video>
<br>
<b>Responsibilities :</b><br>
- Setup a token system for enemy attacks to ensure only a set number of enemies can attack at once<br>
- Tweaked visual elements such as animation timing & hitstop to achieve satisfying combat without compromising responsiveness<br>
- Wrote a gameplay document outlining the core pillars, player actions, and objectives<br>
- Implemented UI motion for bars, hover states, and skill notifications

____________________________________________________________________________________
<br>

<b>Keep Moving Forward</b><br>
The first pillar of the game’s design is as follows: “the player should always be encouraged to keep moving forward”. I incentivized this is by skewing the risk/reward in the favor of being aggressive.<br>
</p>
- Enemy projectiles can be parried by a well timed attack so rather than dodging their attacks, it makes more sense to dash through them instead.<br>
- Dashing spends a dash charge and only by getting a kill or parry can you regain your dash charge. I figured that if we put the dash on a cooldown after being used, some players might run away and wait out the cooldown timer rather than playing risky.<br>
- Additionally, successful offensive actions can be canceled into other offensive actions (Ex. After attacking an enemy you can cancel the recovery animation by immediately dashing).<br>
- It is also very beneficial to maintain a combo because having a higher multiplier means each kill or parry will earn you more score.<br>
- The combo timer does get shorter the higher your combo gets but the further into the game you get, more enemies will spawn and they move faster. In this way even though it becomes more difficult to survive later on, it actually gets easier to build up a large multiplier.<br>
If you aren’t entering a flow state when playing One In The Sheath, then I have failed.
<br><br>

Very early into development I realized that this game would live or die by it’s game feel. I knew that I wanted to utilize hitstop to make every attack feel powerful but I quickly realized that this could interfere with our “keep moving forward” design pillars. If hitstop slows the game down too much it will do the opposite of my intent and actually take you out of that flow state. This issue would become especially obvious when reaching later waves with more enemies spawning. We could simply shorten the length of hitstop around the board, but this would make single hits feel less impactful. To account for both cases, I added hitstop scaling so when hitstop occurs immediately after one another, the next instance will be shorter. There is a minimum amount of hitstop that it cannot go below because if it is too short then it defeats the purpose. But hitstop scaling allows single hits to feel impactful while still retaining the feeling of slicing through each individual enemy.<br><br>
<video width="640" height="360" autoplay muted loop>
  <source src="/assets/1SheathVideos/1SheathHitstopScaling.mp4" type="video/mp4">
</video>
<br>

Play the game here on my <a href="https://shanegamedev.itch.io/one-in-the-sheath">Itch.io Page</a>.<br><br>
If you'd like to read more in-depth, here is my <a href="https://docs.google.com/document/d/1z-u6jxpOQ0967URzYsQztUvDtA67lIu9O2IFe62chjU/edit?usp=sharing"> Gameplay Document</a>.<br><br>
Check out the entire codebase on <a href="https://github.com/ShaneMakesGames/Code-Samples/tree/main/One%20In%20The%20Sheath">Github</a>.<br><br>
