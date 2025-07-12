---
layout: project
type: project
image: img/cold_steps_cover.png
title: "Cold Steps"
date: 2024
published: true
labels:
  - Level Design
  - Baba is You
  - Puzzle Design
summary: "A level of the puzzle video game Baba is You, created with the game level editor beta uploaded on Itch.io."
---

# Introduction

Cold Steps is a level of the puzzle video game Baba is You, created with the game level editor uploaded on Itch.io. The following sections explain the process of creating the level from the first initial concept to its latest version.

<div class="text-center p-4">
  <img width="700px" class="img-fluid" src="https://i.imgur.com/6R5GCHi.gif">
</div>

## First Aproach with the Game

After playing several levels of Baba is You, there were two mechanics that stood out to me. The first was the fact that in some levels, the player could take control of the walls of the level, which provided a feeling of power by suddenly gaining agency over a large area of the level. The other mechanic was based on the <b>MAKE</b> property, which allowed the player to generate an element every time they took a step.
This mechanic reminded me of the puzzles of the video game The Legend Of Zelda: Tears of the Kingdom, in which the puzzles provide you with different pieces and materials separately and it is the player who must put them together to create himself the tools that will allow him to solve the puzzle.

So I decided that in my level the player had to create different elements with the <b>MAKE</b> property and then use them to solve the puzzle.

## Initial Concept

The first idea of the level that I thought of, taking advantage of the MAKE property, was that the player had to create a large version of Baba and then take control of it and with it solve the puzzle.

<div class="text-center p-4">
  <img width="700px" class="img-fluid" src="https://i.imgur.com/BAhyGd1.png">
</div>

There were three materials that worked well when creating large masses of elements, not only because when different pieces were put together they formed a single piece, but it also made logical sense taking into account the material used.
The materials were: <b>CLOUD</b>, <b>ICE</b>, and <b>BLOB</b>.

<div class="text-center p-4">
  <img width="250px" class="img-fluid" src="https://i.imgur.com/7NdLAaT.png">
  <img width="250px" class="img-fluid" src="https://i.imgur.com/3suWnr5.png">
  <img width="250px" class="img-fluid" src="https://i.imgur.com/2DKh1Un.png">
</div>

The material that worked best was <b>BLOB</b>, as it created an interesting result and it made more sense that Baba could leave a trail of slime than clouds. However, the final material was <b>ICE</b> as I thought it would be more fun if the player could create ice by walking on water and it was a good hook that differentiated my level from the rest.

The idea was to use the large body created to move blocks of <b>TEXT</b> at the same time, or adopt different shapes to fit into gaps and move text in ways that could not be done with Baba.
But this idea was discarded due to its complexity and I established that the way to beat the level would not be to control the mass of ice created, but to use it to overcome the puzzle.

## First Version

In the first attempt to make the level I had two rules clear that would remain intact throughout development. The first was that the way to win was to touch the flag (<b>FLAG IS WIN</b>), since it was a clear and easy to see objective. The second was the mechanic of Baba creating ice when stepping on water (<b>BABA ON WATER MAKE ICE</b>), since this was the hook of the level.

However, I couldn't use these mechanics in a way that they were not too easy to solve or didn't break the level and then I realized that I was building the level before establishing the puzzle to resolve.

<div class="text-center p-4">
  <img width="700px" class="img-fluid" src="https://i.imgur.com/aoJpXt3.png">
</div>

## Second Version

On the second attempt at making the level I focused not only on using the mechanics of using the <b>FLAG</b> to win and <b>BABA ON WATER MAKE ICE</b>, but also on playing with these rules so that the player altered them to solve the puzzle, since the fact that changing the rules was what made Baba is You special, and I wasn't taking advantage of it.
I started messing around with the <b>TEXT</b>s of the game to create the puzzle, however I ran into three problems during the development.

The first was that it was creating the level in chunks, so the player had to solve several mini-puzzles to reach the flag. This mechanic was not bad itself as long as the mini-puzzles served to solve a larger puzzle, but I realized that I was doing them separately and disconnected from each other, so I did not like this approach.

The second problem was that again, altering some rules made creating the puzzle very complicated, since it completely broke the level.

And the last problem came as a result of the second, since I realized that some mechanics should not be altered (such as the case of the level hook, <b>BABA ON WATER MAKE ICE</b>). So for the next attempt I focused on finding first all the mechanics that the level would use and then separating them into alterable and unalterable to make the puzzle.

<div class="text-center p-4">
  <img width="700px" class="img-fluid" src="https://i.imgur.com/PtEGFQ8.png">
</div>

## Third Version

The first version required the player to remove the <b>SINK</b> property of <b>WATER</b> and <b>ICE</b> in order to freeze the water and use the ice to push the <b>FLAG</b> off the <b>SKULL</b> group and win.
However, I found at least five problems in the level, two due to design errors and three through the playtesting done in class.

The first two design errors had to do with the word <b>WATER</b>, because, one, I realized that having <b>WATER AND ICE IS SINK</b> as the first rule directly avoided the use of the main hook of the level <b>BABA ON WATER MAKE ICE</b>, and two, the level could be solved by pushing water instead of ice and the player would never see the hook mechanic. 
On the other hand, thanks to playtesting I discovered three other problems. 

The first problem was that with the <b>FLAG SINKS IN THE WATER</b> rule, the flag eliminated the player when he touched it. This was because I wanted the players to create an ice platform to save the flag from the lake, due to the <b>FLAG ON ICE IS SAFE</b> rule, as I wanted the player to use the ice created to solve the puzzle no matter what, however, the <b>FLAG</b> that had the <b>SINK</b> property eliminated the player on contact unless the flag was moved off the surface of the water.
The second problem was due to players modifying the <b>FLAG IS PUSH</b> rule to create more flags since there were no repercussions for altering this rule.
And the last problem, which I discovered thanks to the feedback of a classmate, was that the rules to be modified were very easy to access, and it was very easy to change them.

<div class="text-center p-4">
  <img width="700px" class="img-fluid" src="https://i.imgur.com/uvLHgtR.png">
</div>

## Fourth Version

For the second version I focused on correcting the problems from the previous version. 
First I shrunk the size of the level vertically and enlarged the lake so that the player would cross over it and try the <b>BABA ON WATER MAKE ICE</b> mechanic no matter what.

Second, I got rid of the <b>WATER AND ICE IS SINK</b> rule and the <b>WATER AND ICE IS SAFE</b> rule, which prevented ice and water from eliminating each other, but without <b>WATER AND ICE IS SINK</b> it was no longer necessary.

Third, I changed the <b>FLAG ON WATER IS SINK</b> rule to <b>WATER EAT FLAG</b>, which kept the flag safe as long as it was on ice, but no longer eliminated the player on touch.
Also, I changed the <b>FLAG IS PUSH</b> rule, since I didn't like giving away part of the solution, and replaced it with the <b>FLAG ON ICE IS SAFE</b> rule, which solved the problem of people altering the <b>FLAG IS PUSH</b> rule without repercussions.

Finally I put the rules inside the lake, not only to encourage the player to step into the water, but also to complicate access, since now the ice prevented the player from retracing their steps with the <b>ICE IS STOP</b> rule.
Besides I added a new material called <b>CRYSTAL</b> as an excuse to add AND and allow the player to create the <b>ICE AND FLAG IS PUSH</b> rule, which would allow them to win. I chose <b>CRYSTAL</b> specifically because it looked like ice fragments, especially when its color is changed to light blue.

Now the catch of the level is that the player had to use the words <b>ICE</b>, <b>AND</b>, <b>IS</b> and <b>PUSH</b> to create the <b>ICE AND FLAG IS PUSH</b> rule or similars but it can not mess the <b>FLAG ON ICE IS SAFE</b> rule.

<div class="text-center p-4">
  <img width="700px" class="img-fluid" src="https://i.imgur.com/5PZPnuo.png">
</div>

## Final modifications

I wanted the player to think first about using ice instead of crystals, so I tried adding the <b>CRYSTAL IS DEFEAT</b> rule to draw the player's attention away from the crystals, which only worked if the <b>CRYSTAL IS STOP AND PUSH</b> rule was modified.

<div class="text-center p-4">
  <img width="500px" class="img-fluid" src="https://i.imgur.com/LAqNccH.png">
</div>

However, this did not greatly affect the gameplay and was more of an annoyance than a feature. Therefore, I left the rules as they were, modified some colors to make the level more aesthetic, and added clouds as decoration since they looked like snow.

<div class="text-center p-4">
  <img width="500px" class="img-fluid" src="https://i.imgur.com/D6EaL21.png">
</div>

However, at this point I realized that <b>AND</b> was not really necessary if I placed the texts like a crossword puzzle.

So I changed the <b>CRYSTAL IS STOP AND PUSH</b> rule to <b>CRYSTAL IS PUSH</b>, and I put the <b>ICE IS STOP</b> together with the <b>FLAG ON ICE IS SAFE</b> rule in the form of a crossword puzzle to give the player a clue on how to solve the puzzle.

<div class="text-center p-4">
  <img width="500px" class="img-fluid" src="https://i.imgur.com/nzXfaqI.png">
</div>

With this change, the <b>ICE IS STOP</b> rule became more relevant, not only because it taught the player that he could take advantage of texts from a column rule to create a row rule, but now it was much further away from the player, which made it the mechanic of the player not being able to retrace his steps inevitably lasted longer.

However, now the crystals took more leadership than the ice to move the flag, but I decided not to interfere anymore since at this point the level design was more aimed at using the crystals.

## Final Version

Finally, I decided to recover the <b>AND</b> and add the <b>FLOAT</b> property so that the player would have more options to choose from, and thus, make the level a little more difficult. 
With this, not only did increase the possibility of using <b>ICE</b> to obtain the flag, but by not having <b>CRYSTAL IS PUSH</b>, which I did not like since it gave part of the solution to the puzzle, and changing it to <b>CRYSTAL IS FLOAT AND PUSH</b>, the player would have to make the decision whether to use the <b>FLOAT</b> or not, which makes it a little more difficult to find the solution to the puzzle.

 I decided to use <b>FLOAT</b> instead of another <b>STOP</b> since <b>STOP</b> with a <b>PUSH</b> did not work and with a <b>FLOAT</b> it gives the sensation that the crystals are floating in the lake.

<div class="text-center p-4">
  <img width="700px" class="img-fluid" src="https://i.imgur.com/uEJvTRu.png">
</div>

Before finishing, there are several solutions to this puzzle, which are mainly divided into three.

The first is to solve the puzzle as planned, which is to use the <b>PUSH</b> property and different materials, such as <b>ICE</b>, <b>CRYSTAL</b> or <b>TEXT</b> itself to get the <b>FLAG</b> out of the <b>SKULL</b> group.

The second solution is to take one <b>CRYSTAL</b> out of the water and turn it into a <b>FLAG</b>. It must be taken out of the water to prevent the destruction of the <b>FLAG</b> with the <b>WATER EAT FLAG</b> rule.

The last solution is to modify the <b>FLAG ON ICE IS SAFE</b> rule, shortening it to <b>FLAG IS SAFE</b>, causing the water to not destroy the <b>FLAG</b> in any case, and converting other elements such as <b>ICE</b> or <b>CRYSTAL</b> into flags.

Last but not least, the level can be played with the code <b>8PRF-ZC2B</b> with the [beta version of the Baba is You editor.](https://hempuli.itch.io/baba-is-you-level-editor-beta)
