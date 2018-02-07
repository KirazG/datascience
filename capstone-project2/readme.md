## Capstone Project Two Proposal
# The IPL Match Predictor
### 1. What is the problem you want to solve?
IPL competition is played amongst 8 elite clubs. The format of the game is very simple – each team will face the other 7 teams twice once in their home ground and then in other team’s ground. At the end of all the 56 matches, the top four will qualify for the playoff. The first two ranked team will play against each other in Qualifier 1 and the third and fourth team will play against each other in Qualifier 2. The winner of Qualifier 1 one will be qualified for the final and the loser will play against the winner of Qualifier 2 in the Eliminator. 

Group games do not necessarily end with one side winning. They can either have ‘no result’ if weather prevents the game from being finished or be ‘Super-over if both teams end on the same score. In the knock out rounds, ‘no result’ games are replayed on a reserve day and ‘tied’ matches are decided by ‘super-over, ensuring that there is always a winner.

In each IPL team, a total of 11 players will play the match and it must comprise of 7 Indians and 4 foreign players. The rule of 7 Indians is mandatory and was introduced to promote local players. So one of the challenges all the team faces in each match is to select the 4 foreign players from a total of 8 players. 

I am trying to solve three problems 

**Predict the outcome**
To predict the result of a T-20 IPL match based on various parameters such Home advantage, First Bat, Ground conditions, Toss, Team combinations. 

**To assist the coach & captain in team selection** 
Who should be included on each grounds against each opposition? Who is probably going to perform better? 

**Fantasy League Prediction**
What should be the composition of your fantasy league team? Fantasy league team is a visual game played by the cricket fans. In a day, the fans are allowed to pick their playing 11 from the four teams who play on a day. 

### 2. Who is your client and why do they care about this problem? In other words, what will your client DO or DECIDE based on your analysis that they wouldn’t have otherwise?
Each of the IPL team. I will publish my findings to the team's twitter handle and social forums. Based on the rate of success, the team can try to adapt to the findings.

### 3. What data are you going to use for this? How will you acquire this data?
There are no ready-made data available for this. Data will be scraped from www.cricinfo.com and www.cricbuzz.com using a range of web crawlers written in Python. This raw data will be cleaned, wrangled and combined into multiple datasets such as matches, teams, batsman, and bowlers.

### 4. In brief, outline your approach to solving this problem (knowing that this might change later).
For predicting the outcome of a match, I will try to use Naïve Bayes, logistic regression, random forests and gradient boosted trees. For the second problem to assist in team selection, I will gather individual player records to determine the best team for a particular match. Also, use some of the set matching algorithms to decide the batting order. 

I will also refer to some of the research papers given below

#### Autoplay : A Data mining approach to ODI cricket simulation and prediction
https://pdfs.semanticscholar.org/4667/1ddcbb7bcee189ede56937c440b2ec4d0147.pdf

#### Evaluation of a Batsman’s Performance in Cricket Using Fuzzy Logic
http://ijcst.com/vol54/Spl1/11-Vikas-Kumar.pdf

##### Using Machine Learning to Predict the Outcome of English County twenty over Cricket Matches
https://arxiv.org/pdf/1511.05837.pdf


### 5.	What are your deliverables? Typically, this would include code, along with a paper and/or a slide deck.
I will be submitting the following as part of my final project
- Code in python Notebook
- Data Dictionary
- A blog
- A slide Deck




