---
layout: project
type: teamproject
image: img/edens_reach_cover.png
title: "Eden's Reach"
date: 2025
published: true
labels:
  - Indie Game
  - 3D Pixel Art
  - 3D Action game
summary: "A third person action game with a 3D pixel art style, where you explore a wild world where you possess the local creatures to use their abilities."
projecturl: https://github.com/Hic-Sunt-Pixel/Hic-Sunt-Pixel/releases/download/%2B/EdensReach.zip
---

# Introduction

Eden's Reach is a video game project currently being developed by [NovaDot Studios](https://linktr.ee/novadotstudio), an indie game team made up of approximately ten people. Eden's Reach emerged from a former college classmate's final year project, which involved creating three-dimensional worlds that looked like pixel art. That is, while the game world was three-dimensional, it would appear two-dimensional to the player.

<div class="text-center p-4">
  <img width="700px" class="img-fluid" src="https://i.imgur.com/GWThrIv.gif">
</div>

With this visual style in mind, a group of friends got together shortly after our final year of college and founded NovaDot Studio with the goal of creating an exploration game that would take advantage of this 3D pixel art.

<br>

## First Development Fase

At first, the same colleague who developed this project explained how it generally worked to us. At first, we thought they were boxels, like in Minecraft, but we soon realized that everything we put into the engine would appear as pixel art on the screen. On the one hand, it saved us a lot of work developing pixel art sprites, but on the other, it forced us to always model a large part of the assets in 3D.

With this in mind, in the first few days, we began planning and conceptualizing the different elements of the game so they would work within this engine. We spent several weeks simply gathering references on what style would work well within the engine and what elements we could include to begin prototyping. We also began assigning roles among ourselves to make the organization easier. I was assigned the role of designer, by personal request, and the role of artist, due to the skills my classmates knew from my previous university projects, role that was later formally elevated to Lead Artist.

As an artist, one of my first tasks was to conceptualize the basic design of the protagonist. During the first versions of the project, we had planned for the protagonist to be customizable, both physically and in his clothing, which is why the first concept was to be his basic attire. I worked with other colleagues to find a style that matched the game's, which ultimately led me to create more than ten different styles.

<div class="text-center p-4">
  <img width="700px" class="img-fluid" src="https://i.imgur.com/busPyOm.png">
</div>

I was also in charge of conceptualizing one of the game's first bosses. This was done by several people, including the one who eventually became the Lead Designer and two artists, including myself. The Lead Artist, who was also responsible for creature design, would tell us how the creature should look and move, and a colleague and I would create concepts that fit his description.

<div class="text-center p-4">
  <img width="700px" class="img-fluid" src="https://i.imgur.com/c7qymzd.png">
</div>

<br>

## Second Development Fase

Once we had most of the project planned, we decided to set a deadline and start producing some assets. In my case, since I had already worked on the protagonist and the boss, my job consisted of modeling them so they could be incorporated into the game. This process included modeling them in 3D, performing a retopology to reduce the polygon count, creating UVs for later texturing, creating rigging and skinning, and finally animating them.

Needless to say, during this process I focused solely on creating these characters. However, before modeling, the Lead Designer and I tweaked the boss to make it more closely resemble its original design, so I had to iterate several times until we arrived at a design we both liked.

<div class="text-center p-4">
  <img width="600px" class="img-fluid" src="https://i.imgur.com/cABrQ8b.gif">
</div>

However, once we put it into the engine and everything looked good, we began to notice that the polygonal load was too large, even after retrieving it. During this phase of the project, we began to see some problems with creating a 3D world, so in the following weeks we considered reducing and reworking some assets.

However, at that time we didn't make any changes to production, as the deadline we originally set had already been extended to allow us to attend an event being organized at our university, CITM, so we focused on having everything ready for that day. If we had a demo by that date, we could show it to everyone who came to the event, and people could try the game, which would give us visibility and feedback for future improvements.

In the end, we sprinted through asset and code development to have a playable demo in time. I spent the last few days creating a small test level where the player could explore a small island and face various enemies, including the boss, while my colleagues prepared the engine code for the demo and fixed some bugs. That demo level is the one currently playable.

<div class="text-center p-4">
  <img width="700px" class="img-fluid" src="https://i.imgur.com/p4lXPmz.png">
</div>

<br>

## Third Development Fase

After the event, we decided to take advantage of what we'd learned and made some changes to the game's production. We started by working on small things and polishing them before implementing an entire unfinished system. On the code side, we decided to redo a large portion of the code to improve production. There weren't any major changes on the design side, but on the art side, we decided to start working on creating a more compelling main character.

During this phase of development, we decided to reduce the workload after considering everything we had originally proposed and the work it was causing us. Therefore, one of the decisions we made was to remove the character's physical customization and leave only the clothing. We also decided to make the character genderless, which would make it easier to design the clothing without having to vary versions depending on gender.

<div class="text-center p-4">
  <img width="300px" class="img-fluid" src="https://i.imgur.com/cVDdUiC.png">
  <img width="300px" class="img-fluid" src="https://i.imgur.com/MP7gWkX.png">
</div>

For the protagonist, I decided to use several references to Link from The Legend of Zelda and Sora from Kingdom Hearts. The idea was to create a character who was an explorer and had to learn from his surroundings, but at the same time agile and able to defend himself in combat. With this design in mind, we decided to redo the character modeling and make it much more polygonal.

I used old character models from the Nintendo 64 and the original PlayStation as references. I ended up creating a model that was almost as detailed as the one we had in previous development phases, but with less than a third of its weight and polygonal load.

<div class="text-center p-4">
  <img width="700px" class="img-fluid" src="https://i.imgur.com/KcEOhYg.gif">
</div>

I created a test texturing to see how it would look, and although it's not the final character design, it's starting to look better for now.

We haven't done any more demos with the new version of the character yet, but you can follow the project's development on [NovaDot's social media ](https://linktr.ee/novadotstudio), or you can download the demo version we took to the CITM event using this button: <a href="
https://github.com/Hic-Sunt-Pixel/Hic-Sunt-Pixel/releases/download/%2B/EdensReach.zip" class="btn btn-outline-dark">Download Ende's Reach Demo</a>
