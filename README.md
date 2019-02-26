# tankcoin-frontend-js
Frontend for tankcoin app written in Javascript and ChartJS


## Deliverble:

- User can login/create with username 
- User can create game and do transaction actions (buy/sell) 
- User can see the game leaderboard at the end of the game 
- User can see analytics at the end of the game 

## Instruction:

- The goal of the game is to amass the highest possible net value by trading TANKCOIN(TC)s
- create user or login
- click start to run the game
- user has a begining cash balance
- the chart display current market value of a TC
- user have 2 actions to choose:
  - Buy action will buy TC at current market price
  - Sell action will sell TC at current market price
- The game duration is 1 minute

## Game logics:

- TC value is created from a normal distribution with randomly modifier: skewness and kurtosis
- Events are random factors that would adjust TC value (based on the story outcome)
- Each game created will have a number of events that user need to react to
