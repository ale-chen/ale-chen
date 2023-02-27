## *Arbitrage*

I spent several hours or so writing a short program to search differing upcoming American Football betting odds to find guaranteed Arbitrage profit opportunities between different bookmakers. As of the time of writing this (7:00 AM, Nov. 12), betting on the Sunday Bills v. Vikings game can yield a guaranteed .63% profit if you bet using both the BetMGM and BetFAIR platforms.

*AS OF 8 AM ON NOV 13, THERE'S A 9.72% GUARANTEED RETURN ON THE SAME GAME USING MYBOOKIEAG AND FANDUEL

## *Arbitrage + Deep Learning*

Using historical (2008-2022) betting odds from football-data.co.uk, CategoricalModel and RegressionModel predict whether a given game is likely to present good opportunities through arbitrage through deep learning models. RegressionModel was built in response to CategoricalModel's lukewarm performance, and lack of good loss metrics.
- X (Both models): Each row of X contains date, teams playing, and betting odds/game statistics for each teams' previous five games (10 previous games total)
- y (Categorical): Categorized Arbitrage yields for each game as follows:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<ins>idx | profit range</ins>   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\-2:   [-∞,&nbsp;&nbsp; -2%]   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\-1:   [-2%,&nbsp; -0%]   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1: [+0%, +2%]   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2: [+2%,&nbsp;&nbsp; +∞]   
- y (Regression): Direct decimal profit margins

[Click Here for Colab Project](https://drive.google.com/drive/folders/1ZnR5a_7enPvifi1PJFIsz0oyN4gU1BYs?usp=sharing)

## *ML Projects*

The MLProjects repo contains several toy-datasets and a demonstration of profficiency with Python, sklearn, and a breadth of ML models.

<!---
ale-chen/ale-chen is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
