---
layout: post
title: Come Bowl Season, Beware of the Big 10 and SEC
tag: college football
author: Cameron Taylor
date: 2019-12-16
description: I assess whether team conference can improve predicting college football bowl games. 
permalink: /blog/conference-bowls
---


Predicting the outcomes of college football bowl games is hard. In a [previous piece](https://cameronntaylor.github.io/blog/cfb-bowl-predict) we compared the prediction methods of the average contestant on [ESPN&#39;s Bowl Mania](http://fantasy.espn.com/college-bowl-mania/2019/en/) to picking strategies that simply utilize publicly available information from sources such as Vegas. We found that using these methods results in predicting the winner correctly somewhere between 50 and 60% of the time. While these are decent percentages of picking, there is clearly a lot of room left for improving picks upon using these methods. Is it possible to improve picking methods by using information about the conferences of the teams playing?

Conceptually, the reason why conferences could be important in bowls is that all bowls are against teams from different conferences (except potentially the playoff bowls), and some conferences may be generally better than others. All else equal then, a team&#39;s conference affiliation should tell us about their how good they are overall. Practically, conferences are a useful feature for prediction because they are easily observable, even by the most casual fan.

Table 1 below shows the conference participation of bowls in 2018-2019, including the number of games they played in, the percentage of those games that Vegas got correct and the percentage of those games that at least one of the three methods we considered (Vegas, ESPN, S&amp;P+) got correct, which we call the MAX method.

   Table 1

| **Conferences** | **# Games** | **Vegas %** | **MAX %** |
| --- | --- | --- | --- |
| Big 10 | 9 | 22% | 44% |
| SEC | 12 | 33% | 33% |
| ACC | 11 | 45% | 64% |
| AAC | 7 | 57% | 86% |
| Big 12 | 7 | 57% | 57% |
| CUSA | 6 | 67% | 100% |
| MAC | 6 | 67% | 100% |
| Pac 12 | 7 | 71% | 86% |
| Sun Belt | 5 | 80% | 100% |
| Independent | 3 | 100% | 100% |
| Mountain West | 5 | 100% | 100% |

   Source: VegasInsider.com, ESPN Capital One Bowl Mania



The Big 10 and the SEC are the hardest to predict and appear to be so by a substantial margin. For those contestants making picks, last year&#39;s data suggests that the Big 10 and SEC could be particularly challenging to pick again this year. The ACC also appears to be quite uncertain and there are general trends towards the power 5 conference bowl games being harder to pick and conferences with less teams playing in bowls being easier to pick.

The inability of Vegas to predict these games suggests it may be worth shedding conventional wisdom when picking games involving these larger conferences, especially the Big 10 and SEC. Importantly, these games take up a very large share of the bowls (26 bowl games last year involved either the ACC, Big 10 or Big 12) so it appears that this &quot;wariness&quot; should apply to the majority of bowl games. In other words, most bowl games are hard to predict, but the Big 10 and SEC seem to be particularly tricky. For other games, it appears as though utilizing these conventional methods performs quite well giving success rates above 2/3 in general.

What kinds of mistakes are being made within these bowl game picks? In particular, are they just random errors, or are contestants seemingly over or under-weighting the abilities of certain conferences? If there are systematic &quot;mistakes&quot;, prediction methods could institute simple fixes to conventional methods to improve. One way to get evidence on this is to look at all the wrong picks for each conference and see in which &quot;direction&quot; was the pick wrong – i.e. did the pick go against the Big 10 when it should have been for, etc.

   Table 2

| **Conferences** | **Wrong For** | **Wrong Against** | **Total Wrong** |
| --- | --- | --- | --- |
| ACC | 2 | 4 | 6 |
| Big 10 | 3 | 4 | 7 |
| SEC | 6 | 2 | 8 |

   Source: VegasInsider.com, ESPN Capital One Bowl Mania



Table 2 shows the results for this exercise by conference for picking using only the Vegas method. Interestingly the mistakes are relatively balanced for the ACC and Big 10, while the SEC mistakes are overwhelmingly incorrect towards favoring the SEC. This suggests some potential &quot;SEC bias&quot; in picks from conventional sources. The SEC does have a reputation as the best conference, and it appears that that reputation might be overshadowing other important data points from the season in how picks are being made. For prediction, however, this suggests a simple methodology of &quot;under-valuing&quot; SEC picks by conventional methods. Think carefully about games where the SEC is favored, as some of this favoring may be driven by the legacy effect that is not very informative of bowl performance.

Why might games involving the Big 10 and SEC be particularly hard to predict? One hypothesis is scheduling. To make inferences about bowl games requires understanding how good a team is generally on an absolute scale, and the only real way to assess how good a team is by looking at the results of their schedule. The Big 10 and SEC are known for having particularly [easy non-conference schedules](https://saturdaytradition.com/big-ten-football/too-many-cupcakes-espn-includes-5-b1g-teams-with-softest-non-conference-schedules/). (The SEC even has a week called &quot;cupcake week&quot;.) This makes it harder to infer how good these teams because mismatched non-conference games generally end in large blowouts that have very little information. When teams play better non-conference teams, winning or losing tells us much more about how good they are.

Another reason could be that because the power 5 conferences have more prospective NFL players, and many of these players [sit out](https://sports.yahoo.com/college-football-players-sitting-bowl-games-2018-210123415.html) to retain their &quot;draft stock&quot; and avoid getting hurt, it is more challenging to know how good the team will be in the bowl game given they are missing some star players. (Injuries can also cause the same problems but should be expected to be more evenly spread across conferences.)

Table 3 below shows the number of notable teams with players sitting out and number of total players sitting out bowl games for non-medical reasons by conference. Clearly the power 5 conference teams have many more teams and players sitting out. Interestingly, the Big 10 has the most teams affected.

  Table 3

| **Conferences** | **Number of Teams with Players Sitting Out** | **Number of Players Sitting Out** |
| --- | --- | --- |
| Big 10 | 4 | 6 |
| SEC | 2 | 3 |
| Big 12 | 2 | 3 |
| Pac 12 | 2 | 2 |
| AAC | 2 | 2 |
| ACC | 1 | 2 |
| CUSA | 0 | 0 |
| Sun Belt | 0 | 0 |
| Independent | 0 | 0 |
| Mountain West | 0 | 0 |
| MAC | 0 | 0 |

   Source: [Yahoo! Sports](https://sports.yahoo.com/college-football-players-sitting-bowl-games-2018-210123415.html).

While players sitting out could explain the general trend that 4 of the bottom power 5 conferences have below average prediction rates, and why the Big 10 is particularly challenging to predict, the numbers do not suggest an explanation for why the Big 10 and the SEC are so much more challenging than the Big 12 and the Pac 12 to predict. However, sitting out bowl games could still be an important explaining factor in general for why power 5 conference games seem more difficult to predict than other games.

Thus, when you are making your picks this year, beware of the power 5, and the Big 10 and SEC in particular. You may want to be a little more hesitant about pro-SEC picks, and generally place less confidence in your Big 10 picks. It&#39;s probably best to focus more of your higher point picks on smaller conference games.
