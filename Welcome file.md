# How Well Do NBA Players Evaluate Themselves? - By Dylan Kahler
The NBA finally returned on July 30th. 22 teams are isolated in a bubble in Orlando to mitigate the risk of Covid-19. As a passionate fan, I wanted to use this opportunity to answer the following question: how good are NBA players at evaluating themselves? To answer this, I’m comparing two datasets. 
 
 - The first set: 538's RAPTOR (**R**obust **A**lgorithm (using) **P**layer **T**racking (and) **O**n/Off **R**atings) analysis algorithm. This new tool developed by 538 takes advantage of modern NBA data, specifically [player tracking](https://stats.nba.com/players/speed-distance/?Season=2018-19&SeasonType=Regular%20Season) and play-by-play data that isn’t available in traditional box scores. All this data can be found here: [https://github.com/fivethirtyeight/data/tree/master/nba-raptor](https://github.com/fivethirtyeight/data/tree/master/nba-raptor)
 
 - The Second Set: A survey publish by TheAthletic.com in which NBA players were asked questions about the players the compete against. The three questions I focus on below are "Who is the MVP of the league?", "Who is the best defender in the league?", and "Who is going to win the NBA Finals?"

So how well do the NBA players know themselves? Let's start by seeing if they know who the best player in the league is.

Other Notes: I only analyzed players who had played more than a thousand minutes, because the data completely departs from reality under this value. And you get players like Tyler Davis, who only played one minute. Because he did something good in that one minute, the data claims he packs the densest defensive punch per minute of any player in the league. However, because he went 0/1 shooting the ball, RAPTOR assumes he'll never make a basket, and thus has his RAPTOR offense as last.

|                |Tyler Davis RAPTOR                  |Tyler Davis  Actual   (about 50 seconds played in 2019)                      |
|----------------|-------------------------------|-----------------------------|
|RAPTOR DEFENSE SCORE|4th           |1 Rebound         |
|RAPTOR OFFENSE SCORE      |184th         |1 Missed AFG

![enter image description here](https://docs.google.com/spreadsheets/d/e/2PACX-1vQN629YtX07W4F0cMeIjif4kY4qje4kYsspi2qwAAnY4rW3O_8lgaszKGXMyYRlmAoscHxbpNTwNOpQ/pubchart?oid=1697797136&format=image)
# Question 1: Who is the MVP of the League?
The MVP is voted on by the media apparatus surrounding the sport, and represents the best player in the league for a respective season.

## The Players say... James Harden

James Harden with 44.3% of the vote. Giannis Antetokounmpo came in a close second with 38.9% of the vote. Both players are the leaders of their teams, but have wildly different play-styles. Harden is a modern ball-handler and three point shooter (the type of play popularized by Steph Curry). Giannis is a 7-foot Greak Freak who looks to have been modeled by the gods with the perfect body for basketball. Giannis lacks traditional handling and shooting skills, but overcomes this with his quickness, length, and strength. 

|                |Who is the MVP (122 votes)   
|----------------|----------------------------------------|
|James Harden|44.3%    
|Giannis Antetokounmpo|38.9%       
|Paul George|12.7%    
|Joel Embiid|1.7%       

## 538's RAPTOR says... James Harden, by a WIDE margin.
![enter image description here](https://docs.google.com/spreadsheets/d/e/2PACX-1vQN629YtX07W4F0cMeIjif4kY4qje4kYsspi2qwAAnY4rW3O_8lgaszKGXMyYRlmAoscHxbpNTwNOpQ/pubchart?oid=723344351&format=image)
This is a hopeful first finding from the RAPTOR data. It shows that 538 can make claims that mirror what the experts with real world experience would say. What's surprising is that James Harden has the best overall RAPTOR score by a very wide margin. RAPTOR would conclude that harden should be the unanimous, undisputed MVP..... but....



## In Reality.... Giannis Antetokounmpo won the MVP.

|                |MVP Results   
|----------------|----------------------------------------|
|Giannis Antetokounmpo|73%    
|James Harden|23%       

The actual MVP was Giannis, even though the players and the data overwhelmingly said that Harden deserved this. I think there are several reasons for this discrepency, including the fact that this award is voted on by beat writers for the league, who naturally enjoy a good story (because they write them). Giannis is the newer kid on the block with a different style of play that has been analyzed less. For this reason, I believe story-biased reporters voted Giannis the MVP against the data.

# Question 2: Who is the Best Defender in the league?
One of the most famous mantras in the league is that "Defense wins championships." But how well can the players determine who the best defender in the league is?

## The Players say... Kawhi Leonard
With 30.3% of the vote, the players believe that Kawhi Leonard shuts down scorers like no other. In the basketball world, this isn't a very controversial opinion. There is however controversy with who DIDN'T get votes. Specifically, Klay Thompson only received 1.7% of the vote despite, as we will see, having very impressive stats.

However, as we'll see, the defensive voting done by the players in the metric that has the greatest departure from the RAPTOR data.
|                |Who is the best defender (122 votes)   
|----------------|----------------------------------------|
|Kawhi Leonard|30.3%    
|Pau George|16.2%       
|Rudy Gobert|14.9%    
|Patrick Beverly|10.9%       

## 538's RAPTOR says... Jusuf Nurkic?

This result is most is most surprising. It claims that Jusuf Nurkic, who didn't any amount of meaningful votes in the players poll, is actually the best defender in the league? How does that work? Nate Silver is a dog who is always making bold claims, but this specific bold claim seems specifically fraught considering the fact that every NBA expert would disagree with this finding.

Choosing Jusuf Nurkic for DPOY is like saying the Cal Football team deserved to be in the college national championship, it's more of a antagonizing statement that one driven by lived experience.


![enter image description here](https://docs.google.com/spreadsheets/d/e/2PACX-1vQN629YtX07W4F0cMeIjif4kY4qje4kYsspi2qwAAnY4rW3O_8lgaszKGXMyYRlmAoscHxbpNTwNOpQ/pubchart?oid=1123725965&format=image)
I believe NBA writers and players are biased toward voting for players who are more fun to vote for. The following graph shows RAPTORS PACE data, which shows the impact of players per 48 minutes of play. Typically, a player needs to be faster and able to run the length of the court more times per game to get a higher score in this category. Here we can see that Giannis is ranked higher. 
![enter image description here](https://docs.google.com/spreadsheets/d/e/2PACX-1vQN629YtX07W4F0cMeIjif4kY4qje4kYsspi2qwAAnY4rW3O_8lgaszKGXMyYRlmAoscHxbpNTwNOpQ/pubchart?oid=1827976829&format=image)


## In Reality... Rudy Gobert won Defensive Player of the Year

|                |NBA DPOY 1st Place Voting   
|----------------|----------------------------------------|
|Rudy Gobert|65%    
|Giannis Antetokounmpo|35%       

This is yet another example where the writers chose a player who neither the players, nor RAPTOR would've chosen.

At this point, my thesis for this project is less about the relationship between NBA player opinions at the data, and more about NBA writer opinions and the data. The Players and the data come to similar results, to varying degrees; however, the writers choose players who cannot be understood without being on the pulse of the sport. Simply put, they vote on the best story.

# Question 3: Who is going to win the NBA Finals

The NBA Finals. The mecca of basketball competition. For years, the Golden State Warriors have dominated the league championship after championship. Who did the players pick to win the championship?
## The Players say... 
The players overwhelmingly believed the 2019 Finals would result in similar fashion to the finals that came before. 79.5% of the players believed that The Golden State Warriors would take the title home again.

## 538's RAPTOR says... The Toronto Raptors 

RAPTOR nowhere else shows it's strength than in predicting the NBA Finals champions, because they got it right!




