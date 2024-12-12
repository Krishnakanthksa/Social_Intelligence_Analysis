# Social_media_Intelligence
This project explores social media networks using data from the Mastodon platform. It involves creating and analyzing directed graphs to understand user relationships, connections, and influence within the network. The analysis also includes predicting optimal strategies to minimize bias in networked systems.

## Project Overview

Social networks reveal patterns of interaction and influence among users. Using Mastodon API data, this project analyzes the social graph of users posting with the hashtag #WSUCOMP7025. It employs techniques to:
* Visualize user connections.
* Measure influence using PageRank.
* Identify critical network structures, such as clusters and connected components.
* Apply game theory to determine strategic decisions for network fairness.

## Graph Construction and Analysis
Using the collected data, a directed graph is created where nodes represent users and edges denote “follow” relationships. The analysis identifies strongly connected components, measures graph metrics like diameter and density, and reveals patterns such as clustered groups of users and isolated nodes. The graph is visualized to better understand its structure.

## Influence and Ranking
To measure user influence, the PageRank algorithm ranks nodes based on their connectivity and importance in the network. The results highlight the most influential users, and these rankings are compared with in-degree metrics to validate the findings. The analysis reveals the network’s scale-free nature, where a few nodes act as prominent hubs.

## Game Theory and Decision-Making
The project applies game theory to simulate decision-making processes, such as selecting campuses in a way that minimizes predictability and bias. Using a payoff matrix and linear programming, the optimal strategy is determined, ensuring a fair and balanced approach to influence network-driven decisions.

## Results and Insights
The analysis uncovers the dynamics of the Mastodon social network, including clusters, influential users, and isolated participants. It highlights the importance of hubs in driving network interactions and demonstrates how strategic decision-making can mitigate biases.
