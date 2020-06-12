This notebook use Riot's API data to better understand the interactions between league of legends champions. We will use `networkX` to build our networks and `bokeh` to plot them and visualize data.

What we are going to do is see the most common connections between champions from the same team. In other words, understand what are the most common champions combination in a team.

The dataset we used was gathered from Kaggle:

https://www.kaggle.com/paololol/league-of-legends-ranked-matches

This is a Work in Progress and there are some clear next steps:

    1) plug this notebook directly on Riot's API;

    2) balance the connection between champions, removing weak links to have a better visualization;

    3) add the ranks from each match, so we can better understand how each rank behaves;
