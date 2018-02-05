hiphopfeaturings
================
# Description
Hip hop featurings is a project to display a network of collaborations between artists.
Largely based on Gephi's sigma.js exporter.

# Raw Data stats
It is based on spotify's api data.
I gathered:
- 68580 artists
- 74543 featurings

# Methodology description
Then I used Gephi to analyze the graph and to perform simple network algorithm analysis.

Node sizes and Layout is based on Page Rank and colors on Gephi's modularity cluster (~60 clusters).

Based on that I extracted the most meaningful links and artists.


# Web interface

You can choose a cluster to see all the edges of the cluster or select an artist to see all his edges.


# Screenshots
![E40](screenshot-e40.png?raw=true "E40")

![Gucci Mane](screenshot-gucci-mane.png?raw=true "Gucci Mane")

![Modularity](screenshot-modularity.png?raw=true "Modularity")  
