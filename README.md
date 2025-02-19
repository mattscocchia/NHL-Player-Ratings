# NHL-Player-Ratings
## Introducing the [ScotiaStat](https://linktr.ee/scotiastat) Player Rating system.
These ratings are intended to be a catch-all metric to value a player's performance both defensively, and offensively. They are far from perfect, but they are an attempt at taking (free) publicly sourced data and utilizing it to build a player performance evaluation metric. They are based on the "all-in-one player value stat" (Net Rating) that Dom Luszczyszyn at The Athletic has made. I have tried to design this to be easy to reproduce and/or alter.

The player and team statistics are from [MoneyPuck](https://moneypuck.com/data.htm) and the Woodmoney data is from [PuckIq](https://puckiq.com/woodmoney)


---


The rating magnitudes are designed to be the total amount of goals better than average a forward or defenceman is. This value is an accumulation over the amount of games the player has played during the season, but can also be measured as a per game value. For example, in Connor McDavid's 2022-2023 season, he had an Overall Rating of 45.51 and played 82 games. This can be understood as McDavid being 45.51 goals better than average over the course of the 82 games he played. His per game Overall Rating would be 45.51/82 = 0.555. This can be interpreted as McDavid being 0.555 goals per game better than the average forward. If we break that down into offense and defense, he is 0.529 goals better on offense and 0.026 goals better on defence. Or the team is expected to score 0.529 more goals and allow 0.026 less goals with McDavid on the ice. 


---


I will be adding more in depth comments when I have the time to. I will also add new code when I have new changes or additions. Unless my commitments change, I will be tirelessly working on this behind the scenes. If you have any comments/suggestions/feedback or want to be a part of this somehow, please let me know. I am open to hearing how you think this can be improved. You can message me on any method you prefer [X](https://x.com/ScotiaStat), [Instagram](https://www.instagram.com/scotiastathockey), [Email](matthewscocchia@gmail.com). 


---


If I have time in the future, I will try to add code for more open source hockey related advanced statistics/ratings/models, but for now this is all I have to share. Also, please feel free to copy this and make it your own. It is meant to be used as a starting point.

Enjoy
