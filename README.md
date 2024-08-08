## *Dynamics*
![til](https://github.com/ale-chen/molecular_dynamics/blob/e50a2b964b48939484512e8f3d8b8737b15ef418/k_inter_10_k_center_1.gif)<img src="https://github.com/ale-chen/molecular_dynamics/blob/4dfdf53ec0720f874ddc0a4ec0e9d863b8d6a3cb/problem2_markovian_analysis.png" width=25.6% height=25.6%>

Some chaotic dynamics from scratch in MATLAB, and a measurement of resulting state estimation error.

## *Arbitrage*

I spent several hours or so writing a short program to search differing upcoming American Football betting odds to find guaranteed Arbitrage profit opportunities between different bookmakers. As of the time of writing this (7:00 AM, Nov. 12 2022), betting on the Sunday Bills v. Vikings game can yield a guaranteed .63% profit if you bet using both the BetMGM and BetFAIR platforms.

*AS OF 8 AM ON NOV 13 2022, THERE'S A 9.72% GUARANTEED RETURN ON THE SAME GAME USING MYBOOKIEAG AND FANDUEL

## *Arbitrage + Deep Learning*

[Click here for the summative paper](https://github.com/ale-chen/Arbitrage/blob/aea82747f7908e69c1b2e49e96aa2e2e63d734e3/Report.pdf)

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

## *Robot*

I designed (Fusion) and milled/laser-cut parts for a state-championship robot during the 2019-2020 FTC season.
![IMG_0523](https://github.com/ale-chen/ale-chen/assets/118056107/93c8d92f-3363-4b06-9e26-3975c880f613)

## *Art*

| Pastel | Pastel | Pencil and Charcoal |
| ------------- | ------------- | ------------- |
| ![image](https://github.com/ale-chen/ale-chen/assets/118056107/a2d045ee-c253-4c94-b9db-5e3f168da2e5) | ![image](https://github.com/ale-chen/ale-chen/assets/118056107/bee976fa-79e7-44c2-9358-53c5a6e1b7e1) | ![image](https://github.com/ale-chen/ale-chen/assets/118056107/6fbfc955-7873-4df1-9495-dd755c65d00e) |

<!---
ale-chen/ale-chen is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
