---
layout: project
title: Baker's Dozen
permalink: /BakersDozen/
---
<iframe width="560" height="315" src="https://www.youtube.com/embed/XbJ-XvnPGfI?rel=0" frameborder="0" allowfullscreen></iframe>
## Baker's Dozen
[Play for free!](https://play.google.com/store/apps/details?id=com.AndrewHackmann.BakersDozen&hl=en)

Easy to understand but difficult to complete!
#### Gameplay
* Tilt your device to slide the doughnuts and dough balls
* Swipe to flip the stage (after level 3)
* Tap the Flipper when a dough ball is next to the it

#### Features 
- 13 levels that increase in difficulty
- Keeps your best time of each level so you can compete with your friends!
- Unique controls
- Fun and satisfying graphics and game play

#### Early Development
The concept for Baker's Dozen began in 2011. It was the summer after my sophomore year of high school, and I just started learning C# and XNA. Baker’s Dozen was my first real attempt at a game in a team environment. Naturally, it suffered from what every first game suffers from: a disproportional scope. Josh and I did not fully understand the time it took to design cohesive mechanics and formal technical planning.

The first ideas were simple - tilt a gameboard to make blocks move, and have special blocks that reach a goal while navigating through some kind of maze. That was too simple so we added a list of features: special blocks that could move through special walls, complex theme that would require far too many assets, a player level editor that allowed for scriptable events, playability on every device, etc.

As one could imagine, these ideas would be very taxing on a new programmer even if they were planned out with diagrams, utilized design patterns, and followed code conventions. Sadly, I did not use such things. I took the just-make-it-work approach and suffered every time we decided to add a new element or slightly change an old one. I now know how to make modular and extensible code that can diversely change to better suit the inner workings of a game.


#### Latest Development
Years later, after analyzing where Josh and I failed, I decided to complete Baker’s Dozen alone as a learning exercise. My goals were actually doable this time. First I select a small handful of mechanics to implement that were intuitive but unique. Then I decided on a theme that highlighted each mechanic. Next I created a modular system that was conducive to adding new mechanics. Finally I made an internal level editor that was simple to represent new mechanics with and effective when used.

I succeeded almost completely on all fronts. I created mechanics that were easy to understand, but complicated to master like the icing vortex portals. They allowed for complicated levels requiring the player to plan their route in advance instead of randomly roaming around. Another well implemented mechanic was gravity because it forces all of the cubes to travel at the same rate allowing for precise and complex level design.

The only point I wish I executed better was theming each mechanic, specifically, theming the Flipper. This is forgivable because my aspirations don’t lie with art and animation. A successful theme was moving dough balls into the fryer to complete the level.
![alt text](/images/gravity.gif "Level 11")

This new iteration of Baker’s Dozen was created with [Unity](https://unity3d.com/), which proved to be a better choice than XNA for several reasons. For example, Unity has an amazing visual editor that allows for easy tuning on the fly and has powerful scripting that other similar editors do not possess. Beside the better engine choice, my knowledge of programming also progressed due to completing several advanced data structure and programming language courses that I applied to this hobby. So, my code became modular, extensive, and well documented.

The level editor for Baker’s Dozen is not pretty to look at because it was never meant to be shared (Consider yourself lucky!) It was created with .NET and C#. I chose these tools simply for the sake of familiarity. My editor uses a common save file system that the game also reads so levels can be created, saved, and played in a matter of seconds!
<iframe width="560" height="315" src="https://www.youtube.com/embed/U9L-gac9dZo?rel=0" frameborder="0" allowfullscreen></iframe>

#### Future Development
Since Baker’s Dozen is design well, it would be trivial to add new levels and relatively easy to add new mechanics. There will be an expansion containing both. My family and friends are currently enjoying Baker’s Dozen, so I look forward to creating new mechanics and levels for them to enjoy again!

