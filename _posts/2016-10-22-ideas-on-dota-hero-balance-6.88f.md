---
layout: post
title: "Ideas on Dota Hero Balance in 2.88f"
date: 2016-10-22
---



Like all Dota players, I am always excited to see the release of an update to the game.  Recently, the [6.88f update](http://www.dota2.com/news/updates/24938/) was released, and I'm sure it will be a step forward towards making an already amazingly balanced game even better.  

As a person interested in game design, I'm always curious to think about how [Icefrog](https://en.wikipedia.org/wiki/IceFrog) approaches the question of hero balance.  There are always numerous articles written on which heroes need to be buffed or nerfed ([an example from Dotabuff](http://www.dotabuff.com/blog/2016-10-02-buff-me-balancing-for-underplayed-pub-heroes)).  

I wanted to share some of my own thoughts and suggestions.  I'll fully admit that I'm not a very experienced a Dota player, and I don't claim to have an expert opinion on every character's exact gameplay.  However, I think there should be **general principles** that game designers should pay attention to to decide which heroes to buff and nerf -- and importantly how.  


# General Principles For Hero Balance

1. Some level of equity in play rates is a goal ("hero diversity")
2. Relative popularity and power influences the type of buff or nerf
3. Adjust for experienced players (but take into consideration new players)



## 1. Some level of equity in play rates is a goal ("hero diversity")

**I think all heroes should get some roughly equal level of picks.**  
To take an extreme case, a situation where one hero is picked 90% of the games, while other heroes are seen less than 1% of the time is clearly a negative outcome.  The game could theoretically still be fairly balanced (win rates of 50%), but the game itself would suffer from a lack of variety.  **Hero diversity is important because it supports a wide range individual playstyles, and as a direct result, a wide range of team playstyles.**  This is truly one of the best aspects of Dota.

With 112 heroes, perfect equality in pick rates would be 8.9%.  However, **perfect equality is also not desirable**, and there are many reasons for that (notably would require a rigid breakdown of heroes and their roles, support, carry, etc.).  However, intuitively we should be able to say that a hero should not be picked 90 times more than another hero.  

My sense is that **the inequality in pick/ban rates for the heroes in 6.88 is still not equal enough**.  

Most picked heroes:
1
![Dotabuff Most Picked Meta](/blob/master/_posts/postimage/dotabuff_top10_5000mmr.jpg)
2
![Dotabuff Most Picked Meta](_posts/postimage/dotabuff_top10_5000mmr.jpg)

Least picked heroes:
3
![Dotabuff Most Picked Meta](https://github.com/pkaction/pkaction.github.io/blob/master/_posts/postimage/dotabuff_bottom10_5000mmr.jpg)
4
![](/blob/master/_posts/postimage/dotabuff_bottom10_5000mmr.jpg)


Heroes like Pudge are picked in more than 35% of high level games, while the bottom 10 heroes are getting picked less than 2% of the time.  This strikes me as wrong.  

**I think the designers should target closing the gap between the "richest" and "poorest" heroes.**  

There's no scientific rule for the right ratio, but my sense is that heroes should not be picked more than ~5 times other heroes.  This would mean the pick rate gap would be something closer to the least popular heroes being closer to 4% and the post popular heroes at 20%.  Based on the 8.9% pure equality rate, this would imply that you're likely to encounter some heroes twice as often, and other heroes half as often.


## 2. Relative popularity and power influences the type of buff or nerf

I think the two key factors involved in Hero Balance should be *popularity* and *win rate*.  This might be obvious, but I think there are some nuances worth noting.

* [View all of the stats on Dotabuff - Hero Meta](http://www.dotabuff.com/heroes/meta)

If you created a 2-factor graph, you could put heroes in different quadrants.

![Base Quadrant](https://github.com/pkaction/pkaction.github.io/blob/master/_posts/postimage/quadrant_base.jpg)

* Quadrant 1: Popular and High Win Rate
* Quadrant 2: Unpopular and High Win Rate
* Quadrant 3: Unpopular and Low Win Rate
* Quadrant 4: Popular and Low Win Rate

How to handle the heroes in Quadrant 1 and Quadrant 3 are fairly obvious:

* Quadrant 1: Popular and High Win Rate:  **Nerf**
* Quadrant 3: Unpopular and Low Win Rate:  **Buff**

These are the two situations that should be the easiest to handle.  Hheroes like Outworld Devourer and Omniknight should be nerfed.  Likewise, most of the heroes at the bottom end could use significant buffs, like Gyrocopter and Death Prophet.  I think it's fair to assume that there is a general tendency for heroes that get stronger to also get picked more often.


How to handle the heroes in Quadrant 2 and Quadrant 4 are less obvious:

* Quadrant 2: Unpopular and High Win Rate:  Increase popularity, but reduce strength
* Quadrant 4: Popular and Low Win Rate:  Increase strength, but reduce popularity


### How to adjust the two factors?

**Adjusting Win Rate** (raising or lowering a hero's strength) is relatively simple.  There are many ways to achieve this, but the easiest thing is simply to buff or nerf the hero's powers or stats.  Buffs and nerfs should continue until the hero's win-rate is within the boundaries (48%-52% as a suggestion).

**Adjusting Popularity** (unpopular to popular, or vice-versa) is more difficult.  However, there are definitely gameplay elements that could be adjusted to make heros more attractive to play.  Notably, heroes can be made more popular by making them more friendly to use, or reducing the level of micro required.  Here are some possible examples:

* Reducing complexity on the effects of abilities (different effects on allies, enemies, or has potential negative effects - Example: Oracle, Chen)
* Changing an ability to be auto-cast 
* Changing an ability to be area targeting or area of effect, rather than unit targeting 

Likewise, to reduce the popularity of a hero, do the opposite.


### Adjusting from the extremes 

**Adjusting Which Abilities** - It's also worth considering to start buffing a weak hero's least used power.  This is a way to cause major balance issues.  Similarly to having hero diversity, it's also more likely to lead to greater diversity in heroes builds over time.  As powers within a hero become more balanced, there is more space for great players to build according to the game and situation, rather than follow a set path.

**Adjusting Which Heroes** - It's also worth looking at the extremes for the heroes.  Heroes that have close to 8.9% pick rates and 50% win rates can arguably be ignored.  It's the heroes on the edges (top 10, and bottom 20) that badly need the adjustment.



## 3. Adjust for experienced players (but take into consideration new players)

Last note, the game should be balanced for the professionals.  These are players that should know how to play the game to the fullest.  As a proxy, I am looking at the statistics from [Dotabuff](http://www.dotabuff.com/heroes/meta), and specifically at the 5000+ MMR group.  These players should know the game, and their play should not be radically different from professionals.  

What about low-level players?   While there are definitely low-level pubstomp heroes that could receive buffs in this situation, this is theoretically something that players would learn to handle over time.  What is not acceptable is the situation of many heroes even in the 5000 MMR bracket that have 1% pick rates and <48% win rates.  This is not a situation where the player and the opponents do not know how to use the hero or how to counter it.  This is where the game could receive the best returns on adjusting the balance.

---

Thanks for reading.  Again, I am not an expert on Dota.  I hope this generates some ideas and some discussions.

