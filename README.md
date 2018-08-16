# ElDewrito-RankingSystem
Ranking system logic for El Dewrito and Halostats.click
  
The goal of this project is to create a ranking system for use in the El Dewrito project. Each player will be assigned a rank 1-50 in each playlist. 
Unlike Microsoft's Trueskill project, this system is memoryless in order to discourage players from making new accounts (smurfs), and ignores your own teammates' ranks in order to prevent rank "boosting".

The goal is to have two implementations, strictly EXP based and ELO based. Their usage will be dependent on player population.
