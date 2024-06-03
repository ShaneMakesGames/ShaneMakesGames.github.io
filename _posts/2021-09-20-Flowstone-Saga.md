---
layout: post
title:  "Flowstone Saga"
role: "Junior Programmer"
team-size: "Team Size : 20 People"
timeline: "September 2021 - Present"
summary: "Flowstone Saga is a 16-bit RPG adventure with a unique puzzle-battle system."
date:   2021-09-20 15:39:40
preview: /assets/FlowstoneSagaPreview.png
---
<p align="center"><a href="https://store.steampowered.com/app/1372000/Flowstone_Saga/"><img src="/assets/steam_logo_64x.png"></a><img src="/assets/switch_logo_64x.png"></p>
<p align="center">____________________________________________________________________________________</p>
<p align="center">
<iframe width="720" height="405" src="https://www.youtube.com/embed/uqNS-6pwP3A" title="Flowstone Saga Next Fest Trailer" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<b>Responsibilities :</b><br>
  - Worked closely with designers to program monster abilities and character item passives<br>
  - Implemented UI screens and functionality based on layouts from designers<br>
  - Updated systems such as asset loading, localization, and input device detection for UI icons<br>
  - Communicated with QA team to fix bugs<br>
  - Wrote documentation on how to work with new systems<br><br>
____________________________________________________________________________________
<br><br>

<b>Monster Powers</b>
<img src="/assets/FlowstoneSagaGifs/LightningStrike.gif">
Monster powers are special attacks that enemies use during a battle, usually with a moderate cooldown. Tile removers are one type of monster power, that disrupts the player by removing tiles from the board and dealing damage based on the number of tiles removed. In this example a lightning bolt strikes down and removes tiles vertically in a zig-zag pattern.<br><br>

Setting up monster powers is one of my main responsibilities on the project and the process for creating one can be broken up into three main steps.<br><br>
____________________________________________________________________________________
<br><br>

<b>1. Planning</b>
<img src="/assets/Lock&Key(Mock-Up).png">
It all starts with our designer making a ticket in our task management system. This includes a sketch as well as a description of the ability. I'll ask any preliminary questions I may have and start thinking about how to go about implementing the ability. The image above is the mock-up for the Lock and Key power which blocks off a section of the board with lock tiles and then tosses a key tile on one side. Once the key tile is cleared, all of the lock tiles will go away.<br><br>

____________________________________________________________________________________
<br><br>
<b>2. Prototyping</b>
<img src="/assets/FlowstoneSagaGifs/LockAndKeyHorizontal.gif">
The goal in this stage is to quickly get the monster power's working so our artists can see it in motion and start making assets for it. Often times while prototyping I will come up with more questions, so I talk with our designer again and we decide how the ability should function. For example, when the Lock and Key power blocks off the board horizontally it is common to have left over tiles after clearing the key tile. I spoke with our designer and we decided that these tiles should fall down and fill in gaps after the ability has ended because that is not where we wanted the difficulty to come from with the power.<br><br>

____________________________________________________________________________________
<br><br>
<b>3. Polish</b>
<img src="/assets/FlowstoneSagaGifs/LockAndKeyPower(Final).gif">
At this point the functionality of the monster power is there so I am mostly cleaning up my code and replacing placeholder assets with final art. This is also when I add VFX, SFX, and other polish elements like screenshake depending on the ability. Above you can see the final look of the Lock and Key monster power.  
____________________________________________________________________________________
<br><br>

<b>UI</b><br>
<img src="/assets/FlowstoneSagaGifs/EquipmentUI.gif">
One of the UI menus that I worked on was the Equipment menu. It allows you to pick which items are equipped for the characters in your party before you go into a battle. It also shows a comparison of the stats of your currently equipped weapon against the weapon your are looking at.
<br><br>


If you'd like to <b>play the demo</b>, here is the <a href="https://store.steampowered.com/app/1372000/Flowstone_Saga/"> Steam Page</a>.
</p>
