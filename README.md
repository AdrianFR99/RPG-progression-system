# RPG Progression Systems

by Adrián Font

"I am [Adrian Font](https://www.linkedin.com/in/adri%C3%A1n-font-romero-669a1a158/), a student of [the Bachelor&#39;s Degree in Video Games](https://www.citm.upc.edu/ing/estudis/graus-videojocs/) by UPC at CITM. This content is generated for the second year&#39;s subject Project 2, under the supervision of lecturer [Ricard Pillosu](https://es.linkedin.com/in/ricardpillosu)";



## Index

- [Introduction](https://github.com/AdrianFR99/RPG-progression-system/#Introduction)

- Progression systems

- What is a progression system?

- Why does it work?

- Types of progression systems

- What makes a good progression system?

- The math behind it

   * ratios

   * curves of progression

- Breakpoints

- Power spikes

- Conclusion



## Introduction

In this research article, I will be talking about progression systems, specifically, what is a progression system and the most common types that we can find and also Why these systems became so popular. I will be also exploring the math behind these structures like progression curves (the behavior of them) and some formulas to create basic progression curves will be also included. And as the maths are not all the developers need to create great progression systems I will include some important game designs concepts which are useful to bear in mind when creating one.



## Progression systems

### What is a progression system?

A progression system is simply a combination of mechanics which forces the player to make actions with determined goals, and these must complete them in order to move forward. The player will be able to carry out activities during the whole game and along the way, he might be able to unlock new content and new knowledge to learn (new abilities, more quest, etc).

 In order to have a successful progression system, there are some key element to take into account, which are:

-Game Mechanics:

great mechanics which makes the player feel satisfaction when interacting with the different elements of your game such as weapons, abilities, and when doing so, developer have to control and understanding over the learning curve and avoiding to overwhelm the player, in order to do this you could use what is called mechanics progression, which summarising  is a way to control the way the player learns the different elements of the game over time, there are two types of mechanics progression:

1. Some mechanics are unavailable at first and will be introduced progressively when playing the game

<p align="center">

<img  src="https://github.com/AdrianFR99/RPG-progression-system/blob/master/Graphical%20resources/Game%20Mechanics.png?raw=true" width="600">

</p>


_&quot;Talent trees of World of Warcraft &quot;_



2. All the mechanics are introduced at first but developers use the gameplay in order to induce them. An example of games which have this system will be the games developed by FromSoftware (Dark souls saga and  bloodborne)

<p align="center">

<img  src="https://github.com/AdrianFR99/RPG-progression-system/blob/master/Graphical%20resources/Dark%20Souls.png?raw=true" width="600">

 _&quot;Saga Dark Souls&quot;_

</p>

-Experience thresholds duration:

 As a developer, you want to have as most control of possible on how much time the player might be taken when leveling up, completing a quest, stage,...

And use in order to improve the experience and balancing matters, you don&#39;t want the player to be an unnecessary time in a mission or trying to level up, this can drive the player to frustration.

-Essential Rewards:

If you have any type of progression system you need to reward the players that go through them, and this reward are essential in order to make the player feel that he/she is progressing, I&#39;m talking about game modes, upgrades, unlockable content, in general, new content.



-Secondary rewards:

the secondary reward are those ones that satisfy our visual and aural stimulus, in other words, good visual and auditive effects which focus the player&#39;s attention and  of course, improve the experience, e.g. when playing FPS (First Person Shooters) if you kill an enemy with a headshot a sound will play, this sound is a reward which gives positive feedback to the player and gives a satisfactory stimulus too.

<p align="center">

<img  src="https://github.com/AdrianFR99/RPG-progression-system/blob/master/Graphical%20resources/battlefield.png?raw=true" width="600">

</p>

_&quot;Battlefield v headshot example&quot;_



-Difficulty:

Understanding the elements that affect your games difficulty are key in order to provide a good experience, damage dealt by enemies, weapons stats, etc, control, test and balance the different values in your game and you will be able to improve the experience.



This is the main elements to take into account when creating a progression system, there are more specific elements, strategies to use to improve a progression system, which you will see some of them further on in the article.



## Why do they work?

Nowadays most of the new games have a progression system, and not only from  RPG game which are the ones from the progression system are born (Original D&amp;D), most genres have implemented these systems, and currently, it seems difficult for a game to work without them. But why do these systems are so popular?

The reason is that is useful for the players and the developers, let me explain, it&#39;s good for the player because it gives them the feeling of getting stronger, giving them a sense of progression and that the time they spend in the games is worth the time.

As for the developer&#39;s progressions systems helps them to control the flow of the game, to balance it and modify it as they want (e.g. levels and experience point good tools for that ). In that way, developers are more accurate in creating a better experience, and better control in the player&#39;s actions.

<p align="center">

<img  src="https://github.com/AdrianFR99/RPG-progression-system/blob/master/Graphical%20resources/flow.png?raw=true" width="500">

</p>

## What makes a great progression system?

We have seen which are the key elements that compose a good progression system, but that&#39;s not all, there are a lot of game design techniques to understand in order to improve the experience.

Before getting in what makes a good progression system, us as developers, we should observe cases in which a progressions system has not worked and drove player to have a bad experience, so let&#39;s take a look to the most common mistakes when trying to create a progression system.

RPG games usually have a lot of content, which makes the chance of having a repetitive experience (not always has to be like that,but as more content a game has, the more content the developers have to create, and therefore, more chance end up in a repetitive loop), meaning that the game arrives at a point where the only thing the player does is to level up doing always the same, e.g. make the player replay a dungeon or the same dungeon with slight changes(&quot; a new one&quot;)  in order to win EXP and level up, at the end developer are trying to enlarge the game experience without adding new content.

Another common mistake which I found, is that when you manage to add new content to the game, this is not really part of the experience, is something to tag on into the game in order make the player come back or stay longer

<p align="center">

<img  src="https://github.com/AdrianFR99/RPG-progression-system/blob/master/Graphical%20resources/experience.png?raw=true" width="300">

</p>

Sometimes these mistakes are not only done to enlarge the game lifespan, usually, are committed when trying to disguise the lack of gameplay. If your gameplay is not interesting enough or seem to lack something, by adding new mechanics is not going to solve it, you are only disguising it, instead of doing this, try to understand by the gameplay is not working, check the pre-production phase of the development, the game pillars, etc.



All this bad design decision became psychological traps. The Skinner box, a study of operant conditioning it is a really good example of these psychological techniques to make the player stay on your game but at the end of the day player don&#39;t have fun.

With a general idea of the type of bad game design decisions for a progression system, let&#39;s get to the good ones, what makes a good progression system?

For those who play RPG game, how many time do you spend thinking on your build? Shall I get my character to a DPS or a healer? Increase my melee damage or my magic damage? good progression system allows players to take meaningful decisions to plan out strategies, these systems have something that we can call **long term strategical systems,** which as I said let&#39;s the player to plan strategies for hours, even days. And so if we want this systems to work developers have to reward those players that choose to go through the strategic problem, but also let the player backtrack if they are not happy with the outcome (players are able to change/reset your character talents if they wish so).

<p align="center">

<img  src="https://github.com/AdrianFR99/RPG-progression-system/blob/master/Graphical%20resources/Reset%20abilities.png?raw=true" width="400">

</p>

Another Incredible good decision in order to implement a progression system is to let the player to have a self-regulated learning curve, and how do we do that?

Remember when we talk about mechanics progression, we can use this in order to introduce element one by one and so allowing players to familiarize with the different elements, which could be abilities, therefore player being able to control and master their abilities at the pace they wish, controlling their own learning curve.

As a developer, you need to more or less predict the player&#39;s behavior while using the mechanics of your game, and for that developers could take advantage of progression systems, creating a reward system for engaging types of play style, pushing players to learn and use different mechanics in your game.

And to finish with this section I would like to mention the narrative in progressions systems. Having a progression system which affects the narrative of your game,for example, that the action of the player affects your relationship with factions of the game&#39;s world or that the player decisions on the skill tree changes the character visual style in some way(the progression system, mechanics and narrative being cohesive), this improves the experience of the players significantly, due to it helps players to get more immersed in the game.



## Types of progression systems



### Level based progression:

By doing some determined actions player gain XP/EXP (experience) point which allows them to level up, by doing so the player abilities get stronger and also increases the quantity of XP the player needs to get to the next level (threshold) and the level the player currently has, represent his/her skills/experience.

<p align="center">
  
  <img  src="https://github.com/AdrianFR99/RPG-progression-system/blob/master/Graphical%20resources/RuneScape.png?raw=true" width="400">

</p>

_&quot;RuneScape&quot;_


### Training/Play-Style progression:

This system increases the attributes power the more that is used and is not driven by XP, the more distance you run the more stamina, the more kill with one-handed weapons the more strength and abilities with those... A good example of this kind of system implemented in a game could be The Elder Scrolls v: Skyrim.

<p align="center">

<img  src="https://github.com/AdrianFR99/RPG-progression-system/blob/master/Graphical%20resources/Skyrim.png?raw=true" width="600">

</p>

### Skill points progression:

In this system, player improve their skills by allocating points and usually, they are able to spend it as they please which gives to the player more control over the characters growth, e.g  3 points to improve dexterity, 10 to improve archery, etc.

<p align="center">

<img  src="https://github.com/AdrianFR99/RPG-progression-system/blob/master/Graphical%20resources/Blodborne.png?raw=true" width="600">

</p>

_&quot;Borderlands hunter skill tree&quot;_



Currently, most of the game doesn&#39;t only have one of these systems but multiple at the same time with slight changes in each one in order to work, as some of the last examples shown.You could have a leveling up system that instead of increasing your abilities/ attributes when the player levels up, grants you a certain number of skill points which will allow you to purchase new abilities or improve the ones the player already has.



## The math behind it

So if we want to create a decent progression system at least we need to have a basic knowledge on the maths that are behind it. Understanding and knowing them will allow us as developers to have control on how the player will go through the game, when he/she is going to level up, at which phase of the game will have all the abilities unlocked?,...and also being able to perform any change for balancing needs, simple to improve the experience, because at the end is what most matters, the player to have a good experience.

So now we will take a look to the the different progressions curves,

 seeing how the different types of functions affect in the progression of the player.



### Ratios

If  we are going to study the different functions, it could be useful to have a tool which helps us to perceive the changes in the player progression faster and easily ,for that we are going to use some ratios.



Basic ratio:

This ratio is obtained by dividing the XP required to reach one level by the XP required to reach the previous level.

<p align="center">

<img  src="https://github.com/AdrianFR99/RPG-progression-system/blob/master/Graphical%20resources/basic%20ratio.png?raw=true" width="150">

</p>

Where LVL functions return the XP in a determined level (LVL( **n** ) returns the XP in the **n** level ).

When obtaining the basic ratio we will see that the lower the number obtained the less time(the difference of time between levels,less XP less time) for the player to go for n to n+1 level ( the ratio gets smaller as the game progresses due to the cumulative effects of the multiplayers of the different number of levels, this does not mean that the progression is faster).



 Total ratio:

To determine this ratio we just need the total XP required for the n level and the total XP required for the n+1 level, then divide them with each other:

<p align="center">

<img  src="https://github.com/AdrianFR99/RPG-progression-system/blob/master/Graphical%20resources/total%20ratio.png?raw=true" width="100">

</p>

This ratio shows us how the XP needed for a level increases. If the value is large means that the quantity of experience the player needs to level up increases significantly during the game progression.

### Curves of progression:

So now let going to take a look to some of the most use progressions curves, see how they behave and how this a affects the progression system.

1.Exponential progression

Let&#39;s use an example, we are going to take a look to the next function

<p align="center">

<img  src="https://github.com/AdrianFR99/RPG-progression-system/blob/master/Graphical%20resources/Exponential%20equation.png?raw=true" width="150">

</p>

If we use this function to extract to some values with its correspondent graphic we have the following data(in this case i will show you the first 15 lvl I think there&#39;s no need to extend to much this interval).



| LVL | XP | TOTAL RATIO | BASIC RATIO |
| --- | --- | --- | --- |
| 1 | 25 | 2 | 1 |
| 2 | 50 | 2 | 2 |
| 3 | 100 | 2 | 2 |
| 4 | 200 | 2 | 2 |
| 5 | 400 | 2 | 2 |
| 6 | 800 | 2 | 2 |
| 7 | 1600 | 2 | 2 |
| 8 | 3200 | 2 | 2 |
| 9 | 6400 | 2 | 2 |
| 10 | 12800 | 2 | 2 |
| 11 | 25600 | 2 | 2 |
| 12 | 51200 | 2 | 2 |
| 13 | 102400 | 2 | 2 |
| 14 | 204800 | 2 | 2 |
| 15 | 409600 | 2 | 2 |



<img  src="https://github.com/AdrianFR99/RPG-progression-system/blob/master/Graphical%20resources/Exponential%20progression.png?raw=true" width="600">



The first thing we can take a look at is the relationship of XP between levels, if we calculate the exponential factor we will see that it is a constant number.Let&#39;s get the first 5 levels and see the XP of each one, 25,50,100,200,400, the exponential factor is  2 (50/25,100/50,200/100...),which is equals to both of the ratios(generally), which means that the XP of each levels increases in a constant  factor of two(in this case), in other word that the experience of n+1 will increase by 2(2n).



In exponential progression system developers have to be aware of how you provide players with XP, more exactly which is the difference on quantity that the sources of XP changes when leveling up,because if this ones are too low maybe when the players arrives to high levels it would be impossible to level up.

Also as the levels experience rises exponentially  this means that the rewards given to players must be at the same phase, (have to be exponential) which means that the player can use this in its favor in order to be unsync with the curve and rush through the game which implies that the player could win huge quantities of experience in less time than expected in the current level,making him/her  level up faster.



2.Polynomial Progression

Here we are going to use a function from a dreamcast game called _Armada:Metro3D_
which is:

<p align="center">

<img  src="https://github.com/AdrianFR99/RPG-progression-system/blob/master/Graphical%20resources/polynomial%20equation.png?raw=true" width="150">

</p>

| LVL | XP | TOTAL RATIO | BASIC RATIO |
| --- | --- | --- | --- |
| 1 | 8 | 8,00 | 7,00 |
| 2 | 64 | 3,38 | 2,71 |
| 3 | 216 | 2,37 | 1,95 |
| 4 | 512 | 1,95 | 1,65 |
| 5 | 1000 | 1,73 | 1,49 |
| 6 | 1728 | 1,59 | 1,40 |
| 7 | 2744 | 1,49 | 1,33 |
| 8 | 4096 | 1,42 | 1,28 |
| 9 | 5832 | 1,37 | 1,25 |
| 10 | 8000 | 1,33 | 1,22 |
| 11 | 10648 | 1,30 | 1,20 |
| 12 | 13824 | 1,27 | 1,18 |
| 13 | 17576 | 1,25 | 1,17 |
| 14 | 21952 | 1,23 | 1,15 |
| 15 | 27000 | 1,21 | 1,14 |


<img  src="https://github.com/AdrianFR99/RPG-progression-system/blob/master/Graphical%20resources/polynomial%20curve.png?raw=true" width="600">



As we can see in the polynomial progression the ratios are no longer constant values, and both of the progressions ration decline as the player levels up (indeed is a property of these kind of systems),but the total ratio declines slowly than the basic one.This means that the difference of XP increases get lower as the systems progresses .

In polynomial progression systems, the XP needed for a level is proportional to level^factor (polynomial factor). For example:

**EXP(2)=64        2^x=64  → x=6**


The problem with this type of system is that when the player arrives to the upper reaches of the curve this one tends to lead to a flat  progression  then here is when  we found that there is almost  no difference between the actions the player have to perform  and time taken by this one to level up.



3.Other progression curves

Fibonacci Progression:

In this kind of system the relationship of XP between levels is the XP sum of lvl(n) and lvl(n-1), e.g.  50 100 150 250 400  and the total and basic ratios equals to the golden ratio ( phi=1.618034 ).

NAP(Near Arithmetic Progression):

As the name describes, follows the arithmetic progression but with slightly changes

in the increases of XP e.g.400,500,700,700,800,900,900…

This progression system has low progression ratios which produces a smooth progression curve (more than polynomial and exponential functions) which allows player to have a more gentle pace when going through the game .

There are plenty of more types of curves which we could use as progression systems,such as linear and algorithm functions, but at the end is just to create a curve which fits the type of game that you as a developer want to create. Using the total and basic ratio in your progressions systems will help you a lot to foresee game design problems in the future and therefore prevent them.



## Breakpoints &amp; Power Spikes

Breakpoints are places in your game when a major difference occurs based on a minor mathematical differences (is not necessary a bug it could be a feature), this ones are not easy to detect (usually are discovered when testing the game), let me show you a clear example:

Imagine that we have a linear progression system:

<p align="center">
   
<img  src="https://github.com/AdrianFR99/RPG-progression-system/blob/master/Graphical%20resources/linear%20curve.png?raw=true" width="600">

</p>

Here the player has default melee damage of 100 and has to fight a monster of 160 HP (Health Points). The player melee attack increase 20 points per level (as it is a linear function the values are constant), meaning that the first two levels the player will have to hit two times the enemy to kill it, this seems all right doesn&#39;t, but the problem here is not a matter of numbers but of experience , it might look good but feels bad.

It feel bad because the player doesn&#39;t have any reward during the first levels and then when the players arrives to level four he suddenly one shots the enemy, which means that the difficulty of the game has dropped through the floor.

Another example would be being able to cast two times in a row your most powerful spell because you have enough mana to do so.

Breakpoint come from multiple systems overlapping (monsters, levels ,weapons...) and you can&#39;t really see these ones by looking each system one by one, in order to found them you have to test them as a whole.

Then we have power spikes,not to confuse with the breakdowns, the difference between them is that the power spikes are intentionally introduced by the developers and this one gives a boost of power larger than the normal ones.This power boost are part of the game (in D&amp;D some spells don&#39;t get strong enough)

When trying to control these two game design element it easier to work with power spikes, due to the breakpoint are unintentionally placed, created from how the math of your game interacts with the systems this one has.
