# Data Analysis

### Table of Contents
- [Data Exploration](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/analysis.md#data-exploration)
- [Attack](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/analysis.md#attack)
	- [Goals Scored](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/analysis.md#goals-scored)
	- [Comebacks](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/analysis.md#comebacks)
- [Defence](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/analysis.md#defence)
	- [Goals Conceded](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/analysis.md#goals-conceded)
	- [Clean Sheets](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/analysis.md#clean-sheets)
	- [Throw-aways](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/analysis.md#throw-aways)
- [Overall](https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/analysis.md#overall)

### Data Exploration

The data contains a record of 1,808 matches played between 29 clubs, from the start of 2015-2016 season up till the [COVID-19 break](https://www.premierleague.com/news/1645173) in 2020.

Due to the concept of promotion and relegation, not all clubs had played an equal amount of matches (fig. 1). To eliminate bias, most analyses were conducted on clubs that had played more or equal to the total average amount of matches played by a club (125).

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/games.png' width='1500'> |
| :--: |
| _Figure 1 - Number of Matches Played_ |

### Attack

This section provides analyses of attack statistics including goals scored and comebacks.

#### Goals Scored

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/goals_top10.png' width='1000'>|
| :--: |
| _Figure 2 - Total Goals Scored (Top 10)_ |


| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/goals_bottom10.png' width='1000'>|
| :--: |
| _Figure 3 - Total Goals Scored (Bottom 10)_ |

Manchester City and Liverpool are leading the goals tally (fig. 2), whereas Middlesbrough and Sheffied United are at the bottom (fig.3).

Interestingly, Leicester is a little ahead of Manchester United.

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/goals_firsthalf_top10.png' width='1000'>|
| :--: |
| _Figure 4 - Total Goals Scored in First Half (Top 10)_ |

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/goals_firsthalf_bottom10.png' width='1000'>|
| :--: |
| _Figure 5 - Total Goals Scored in First Half (Bottom 10)_ |

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/goals_secondhalf_top10.png' width='1000'>|
| :--: |
| _Figure 6 - Total Goals Scored in Second Half (Top 10)_ |

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/goals_secondhalf_bottom10.png' width='1000'>|
| :--: |
| _Figure 7 - Total Goals Scored in Second Half (Bottom 10)_ |

Manchester City and Liverpool lead the statistics in both the halves, followed by a fight between Chelsea, Tottenham, and Arsenal.

Hull and Cardiff have scored the least goals in the first half, whereas Middlesbrough has scored the least in the second half.

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/goals_per_game.png' width='1000'>|
| :--: |
| _Figure 8 - Total Goals Scored per Game_ |

The goals per game standings are similar to the total goals standings. Manchester City and Liverpool have an impressive record of scoring more than 2 goals per game.

#### Comebacks

The comeback statistics are computed as a percentage:

`successful comebacks / total comeback opportunities * 100%`

For the purpose of this analysis, a *successful comeback* is defined as: when a club is losing at half time, and ends up winning the match.

A *comeback opportunities* is defined as a situation where a club is losing at half time.

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/comebacks_home.png' width='1000'>|
| :--: |
| _Figure 9 - Home Comebacks_ |

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/comebacks_away.png' width='1000'>|
| :--: |
| _Figure 10 - Away Comebacks_ |

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/comebacks_total.png' width='1000'>|
| :--: |
| _Figure 11 - Total Comebacks_ |

Liverpool are way ahead of others in terms of converting comeback opportunities to successful comebacks, both home and away.

Interestingly, Chelsea is in second place when it comes to Away comebacks, but has not been able to overturn a half time deficit at home (8 opportunities).

### Defence

This section provides analyses of attack statistics including goals conceded, clean sheets, and throw-aways.

#### Goals Conceded

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/goals_conceded_per_game.png' width='1000'>|
| :--: |
| _Figure 12 - Total Goals Conceded per Game_ |

Manchester City is the most defensively successful club in terms of goals conceded per game, followed by Liverpool, Manchester United, and Tottenham (fig. 12).

Interstingly, it is their defensive performane in the second-half that pushes them ahead of the other clubs (fig. 14).

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/goals_conceded_per_game_firsthalf.png' width='1000'>|
| :--: |
| _Figure 13 - Goals Conceded per Game (First Half)_ |

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/goals_conceded_per_game_secondhalf.png' width='1000'>|
| :--: |
| _Figure 14 - Total Goals Conceded per Game (Second Half)_ |

#### Clean Sheets

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/clean_sheets_total.png' width='1000'>|
| :--: |
| _Figure 15 - Total Clean Sheets_ |

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/clean_sheets_percent.png' width='1000'>|
| :--: |
| _Figure 16 - Total Clean Sheets (%)_ |

Manchester City has the most clean sheets, followed by Liverpool and Manchester United (fig. 15).

Interestingly, it is their defensive performance at away games which puts them ahead of the others (fig. 17).

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/clean_sheets_home.png' width='1000'>|
| :--: |
| _Figure 17 - Clean Sheets (Home)_ |

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/clean_sheets_away.png' width='1000'>|
| :--: |
| _Figure 18 - Clean Sheets (Away)_ |

#### Throw-aways

The throw-away statistics are computed as a percentage:

`successful throw-aways / total throw-away opportunities * 100%`

For the purpose of this analysis, a *successful throw-away* is defined as: when a club is winning at half time, and ends up losing the match.

A *comeback opportunities* is defined as a situation where a club is winning at half time.

It is the opposite of a comeback.

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/throwaways_home.png' width='1000'>|
| :--: |
| _Figure 19 - Home Throwaways_ |

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/throwaways_away.png' width='1000'>|
| :--: |
| _Figure 20 - Away Throwaways_ |

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/throwaways_total.png' width='1000'>|
| :--: |
| _Figure 21 - Total Throwaways_ |

Crystal Palace and Southampton have thrown away the highest percentage of their home games, whereas Leicester and Southampton have thrown away the highest percentage of their away games.

Out of the top clubs, Tottenham has thrown away the highest percentage of home and away games.

Chelsea (40 opportunities), Leicester (33 opportunities), Liverpool (52 opportunities), Manchester United (43 opportunities), and Newcastle (16 opportunities) have not thrown away a game at home.

Manchester United is the only club which has not thrown away an away game (34 opportunities). This makes them the only club that has not thrown away a game at all (77 opportunities).

### Overall

The _win, draw, and loss_ percentages are key metrics to judge the performance of a club.

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/win_percent.png' width='1000'>|
| :--: |
| _Figure 22 - Win Percentage_ |

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/draw_percent.png' width='1000'>|
| :--: |
| _Figure 23 - Draw Percentage_ |

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/loss_percent.png' width='1000'>|
| :--: |
| _Figure 24 - Loss Percentage_ |

Manchester City and Liverpool have the highest win ratio (fig. 22) and also the lowest loss ratio (fig. 24).

Out of the top clubs, Manchester United has the highest draw ratio and Manchester City has the lowest draw ratio (fig. 23).

| <img src='https://github.com/meehadjawwad/Premier-League-Analysis/blob/master/images/table.png' width='500'>|
| :--: |
| _Figure 25 - Accumulated Points Table_ |

#### Top of the Table

Manchester City (with a game in hand) and Liverpool are clearly the two best performing clubs. Their difference of 9 points, comes from Liverpool having drawn more games.

#### Second Cluster

The next cluster of clubs includes Tottenham, Chelsea, Manchester United, and Arsenal (with a game in hand), with only a difference of 26 points between them. They have all won around 90-100 games and have a goal-difference greater than +100.

#### Third Cluster

Leicester is the only club in the third cluster. It has broken away from the lower clubs (difference of 29 points), but still not part of the second cluster (difference of 42 points.)

#### Fourth Cluster

Everton is the only club in the fourth cluster. It is 19 points away from the third cluster, and 20 points ahead of the fifth cluster. It is hanging onto a goal-difference of +7.

#### Fifth Cluster

The fifth cluster includes West Ham, Southampton, Crystal Palace, Bournemouth, and Watford. They are separated by a difference of 25 points and have a negative goal-difference.

#### The rest

The rest of the clubs have played less than the maximum number of games (181), and their performances can be studied in Fig. 15.