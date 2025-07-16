---
layout: project
type: project
image: img/bardakedabra_cover.png
title: "Bardakedabra"
date: 2025
published: true
labels:
  - Indie Game
  - Unity
  - Game Design
summary: "A reinvented indie game of the classic Google's Dinosaur Game. Adds a new visual style, new mechanics, replayability, and an ending to the game."
projecturl: projects/bardakedabra_build/index.html
---

# Introduction

Bardakedabra is an plattformer indie game made with Unity where the player has to avoid a series of obstacles which appear faster as the games goes on. It is strongly inspired by the famous endless runner Google's Dinosaur Game but each run the player has the chance to improve the character so it gets further every run.

<div class="text-center p-4">
  <img width="700px" class="img-fluid" src="https://i.imgur.com/kpdK0bH.gif">
</div>

<br>

## First Version

The first concept of the game was to make a rythim and plattformer game mix, similar to another games like Harmoknight. The idea was that the player has to jump following the music beats to avoid the different obstacles. Due to time and difficulty issues i discarted this idea and changed the game's premise, which now was to avoid obstacles that progressively come faster along with an evolution in the game's music.

This way, not only i saved a lot of time in the game's development, but also to facilitate the development of the game's music, which originally was in charge of a university colleague. So, while I was creating the assets and programming the game, my partner was composing the songs for it, so we were both moving forward on the project at the same time.

For the visuals, I considered older Game Boy Color and Nes games, such as Kirby's Adventure (1993) and Pokemon Gold or Pokemon Silver (1999). Their reduced color palette was a good choice since it was easier to design and color the game's characters, saving time and allowing me to fine-tune details if necessary. It also resulted in a style that I personally liked.

<div class="text-center p-4">
  <img width="330px" height="300px" class="img-fluid" src="https://i.imgur.com/mCGc2Yu.png">
  <img width="330px" height="300px" class="img-fluid" src="https://i.imgur.com/0YL4sv6.png">
</div>

In these types of games, the character color palette is usually divided into three, while the backgrounds are usually colored with two colors. In the case of characters, the colors usually consist of a main color, which is usually the most characteristic of the character, a secondary color that can be used for shadows or details, and black, which was used primarily to highlight the character's silhouette against the background, although it was also used to draw some details.

I used this same technique for this game: the backgrounds are composed of light colors, and the characters are more vibrant, highlighted by black. Both the coloring and animations were done in Photoshop, where I colored and animated the characters to see how they looked. Once they were ready, I imported them into Unity so I could program them.

Once the sprites and music were ready, the first version of the game was programmed. In this version, the player ran endlessly while avoiding the characters who acted as obstacles. The objective was to last as long as possible without colliding with anything; if they did, they would have to start the game over.

<br>

## Second Version

In this state the game was a carbon copy of Dinosaur Game, which is why I decided to update the game to differentiate my game from it and be able to contribute something new. When I used to play Dinosaur Game, I got a little frustrated having to always start from scratch, which is why for the new version of Bardakedabra I decided to include replayability, this way each run would have importance.

To achieve this, I included a menu upon losing each run, where players could purchase new abilities in exchange for coins that appeared periodically during runs. This not only added replayability to the game, but also gave players new tools to help them progress further and further in each run.

<div class="text-center p-4">
  <img width="400px" class="img-fluid" src="https://i.imgur.com/FkrtGdZ.png">
</div>

I also decided to include an ending to the game. This not only made it more distinct from Dinosaur Game, but also gave players a goal to achieve in each run. This way, players wouldn't just compete to see who could get the furthest, but also to see who could reach the end. Currently, the ending is at 9999 points, which is equivalent to about six minutes of uninterrupted running. At the end, a short cinematic and a thank-you for playing the game play.

I also decided to redo the game's audio that my colleague had created, and in this case I used Famitracker, a music-generating program for the NES/Famicom systems. Since the old version didn't take advantage of any of the original rhythm game concept, I decided to compose a theme that would progress as the character progressed through the run. This song that plays during each run, which I called Creschendo March, is made up of four loops that repeat continuously. Each loop adds new notes, making the song increasingly more elaborate.

## Final Version

Finally, I created a main menu so you can enter the game without starting a run directly and take a break between runs if you wish. This menu displays the game title and a small text indicating which key to use to start the game, which also serves as a mini-tutorial for the game's controls.

<div class="text-center p-4">
  <img width="400px" class="img-fluid" src="https://i.imgur.com/AUBDKtr.png">
</div>

Since I wasn't entirely convinced by the logo, I decided to redo it so it would stand out a little more from the background. That's why the new version changed its color to yellow, which served as a complementary color to purple. I also removed the little hat from the logo as I felt it wasn't quite polished, and for time reasons I decided not to reimplement it.

<div class="text-center p-4">
  <img width="400px" class="img-fluid" src="https://i.imgur.com/wgNsuE3.png">
</div>

Finally, I decided to add a few credits with my name on the title screen and fixed some general game issues so that it can also work in windowed mode. However, due to the game's configuration, it offers slightly more room to react when playing in full screen, since the character and obstacles are positioned further apart than in windowed mode.

You can play this game in Itch.io and in the next button in te browser:
<div class="text-center p-4">
  <a href="{{ page.projecturl }}" class="btn btn-outline-dark">Play Game</a>
</div>


