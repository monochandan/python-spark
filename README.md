## Libraries:

- pandas==2.2.2
- matplotlib==3.9.0
- pyspark==3.5.1
- findspark==2.0.1
- plotly==5.22.0

## CSV datasets:

      matches: ['Match_ID', 'Div', 'Season', 'Date', 'HomeTeam', 'AwayTeam', 'Home_Team_Goal', 'Away_Team_Goal', 'Final_Result']
      teams: ['Season', 'TeamName', 'KaderHome', 'AvgAgeHome', 'ForeignPlayersHome', 'OverallMarketValueHome', 'AvgMarketValueHome', 'StadiumCapacity']
      teams_in_matches:['Match_ID', 'Unique_Team_ID']
      teams_unique:['TeamName', 'Unique_Team_ID']

      
## Questians solved by this project:

#### Frage 1: Who are the winners of the D1 division in the Germany Football Association (Bundesliga) in the 2010 to 2016?

<img width="494" alt="image" src="https://github.com/monochandan/python-spark/assets/29684226/e0900bef-4645-4187-9ca9-35df16735cbf">
      
#### Frage 2: Which teams have been relegated in that 6 years? 

  - For example: last 3 teams from 2010 who left out from the race

 <img width="386" alt="image" src="https://github.com/monochandan/python-spark/assets/29684226/eb9f2c3c-a279-4e16-b298-69be4e7e30fb">

#### Frage 3: Does Octoberfest affect the performance of Bundesliga? 

  - By ration of goals per game:

     <img width="499" alt="image" src="https://github.com/monochandan/python-spark/assets/29684226/0dbee4c4-98a7-40ce-bb86-f71d469b10c2">

  - By ratio of games drow per month:

     <img width="503" alt="image" src="https://github.com/monochandan/python-spark/assets/29684226/7c931d12-2528-4631-bf27-f4c540c29304">

  - By monthly match played:

     <img width="501" alt="image" src="https://github.com/monochandan/python-spark/assets/29684226/2395262d-dcd3-4b2f-93cb-bc7d98d683f5">


#### Frage 4: Which season of Bundesliga was the most competitive in the last decade?

  <img width="499" alt="image" src="https://github.com/monochandan/python-spark/assets/29684226/db934b7c-67f6-4843-8f26-5fc62807a85b">

#### Frage 5: What's the best month to watch Bundesliga?


  
