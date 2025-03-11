---
layout: post
role: "Technical Game Designer"
team-size: "Team Size : 6 People"
timeline: "November 2019 - October 2021"
summary: "An action-packed desktop defense game where hackers have taken your employer’s network hostage."

date:   2019-10-15 15:39:40
preview: /assets/DigitalJanitorsPreview.png
---
<p align="center">
<a href="https://store.steampowered.com/app/1389850/Digital_Janitors/"><img src="/assets/steam_logo_64x.png"></a>
____________________________________________________________________________________
<iframe width="720" height="405" src="https://www.youtube.com/embed/ZgYnhckP1VA" title="Digital Janitors Launch Trailer" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
Responsibilities : <br>
  - Designed and programmed 28 folder types<br>
  - Designed and programmed 15 power-up abilities<br>
  - Designed and programmed 3 boss fights<br>
  - Wrote documentation on designs<br><br>
<p align="center">____________________________________________________________________________________</p>
<br>
The gameplay core of Digital Janitors consists of sorting secure folders or malware into either the secure drive or recycling bin respectively. The player interacts with folders using their mouse cursor, making the game play closer to an aim trainer than a game with a traditional combat system. Folders are the enemies of the game, requiring the player to deal with them to progress. If too many folders are on screen at once, the available disk space on the computer (shown by the bar at the bottom of the screen) fills up, leading to a game over.<br><br>

I grouped folder types into four categories :<br>
<p align="center">____________________________________________________________________________________</p>
<br>
<p align="center">  
<b>Evasive Folders</b>
<video width="640" height="360" autoplay muted loop>
  <source src="/assets/DigitalJanitorsVideos/RunawayFolder.mp4" type="video/mp4">
</video><br>
</p>
Evasive folders are the most straight-forward of the four. They are folders that move around, making it harder to pick them up. These folder types are not immediately dangerous, but can quickly get out of hand if the screen gets filled with them. There are also folders that only move when you do and folders that teleport to random positions around the screen.
<br>
<p align="center">____________________________________________________________________________________</p>
<br>
<p align="center">  
<b>Locked Folders</b>
<video width="640" height="360" autoplay muted loop>
  <source src="/assets/DigitalJanitorsVideos/LockedFolders.mp4" type="video/mp4">
</video><br>
</p>
Locked folders on the other hand are specifically designed to take more time to deal with than most folders. They are folders that start off locked and require the player to do something before they can be picked up and dragged. The designs are kept fairly simple so they will be intuitive to deal with, but since most of them require multiple clicks to deal with it gives time for other folders to spawn. The encrypted folder requires you to decrypt it by opening the UI and selecting all of the yellow circles. The spam folder opens several pop-ups that cover the screen and must be closed one by one. 
<br>
<p align="center">____________________________________________________________________________________</p>
<br>
<p align="center">  
<b>Trick Folders</b><br>
<video width="640" height="360" autoplay muted loop>
  <source src="/assets/DigitalJanitorsVideos/ElusiveFolders.mp4" type="video/mp4">
</video><br>
</p>
Trick folders, like the name implies, are more gimmicky than the rest. They use misdirection, traps, or tricks to slow down or distract the player. But unlike locked folders, the solution is not always so obvious. The magician folder creates two fake folders which disappear in a puff of smoke when dragged to the recycling bin or secure drive. It is impossible to tell if a folder is fake or not until it has been sorted, forcing the player to use trial and error to find the real one. The frozen folder has ice covering one of its corners and if the player hovers over this spot the folder will freeze up. Once this happens the folder cannot be picked up for a short amount of time. Lastly the split folder is split in half when it spawns and must be put back together before it can be sorted.
<br>
<p align="center">____________________________________________________________________________________</p>
<br>
<p align="center">  
<b>Disruptive Folders</b>
<video width="640" height="360" autoplay muted loop>
  <source src="/assets/DigitalJanitorsVideos/DisruptorFolders.mp4" type="video/mp4">
</video><br>
</p>
Disruptor folders are by far the most dangerous folder type and will lead to a game over if not dealt with quickly. When one is on screen they should be the highest priority, which is why they have bright and flashy artwork to stand out among the rest. The payload folder moves to the bottom of the screen and starts to corrupt the PC. While it is active, a red bar starts moving the opposite direction of the normal storage space bar and if the two overlap it leads to a game over. Once the payload folder is taken away from the bottom of the screen, the red bar will begin slowly receding. The bomb folder has a fire burning down a fuse. Once the fuse  reaches the folder it explodes, spawning three random folders. The spider folder follows other folders and weaves a web which stops them from moving, including being picked up by the player. The player must rapdily click on the web to break it. 
<br><br>

If you'd like to <b>read more</b> in-depth, here is my <a href="https://docs.google.com/document/d/1E4p4KDIr2QUzw1-vumjemMU4ms_Baho3OnM1Yt-2bw4/edit?usp=sharing"> Folder Design Document</a>.<br>
Want to <b>see my code samples</b> from the project, they are here : <a href="https://github.com/ShaneMakesGames/Code-Samples/tree/main/Digital-Janitors"> Digital Janitors Code Samples</a>.<br>
Or if you'd like to <b>play the game</b> yourself, here is the <a href="https://store.steampowered.com/app/1389850/Digital_Janitors/"> Steam Page</a>.
