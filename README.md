# Predicting-NBA-players-positions

# Introduction

NBA players are selected to the All-Star game by position. This means that the All-Star team isn't necessarily the top players, but the top players at each position. This year Nikola Vucevic made the team averaging 23.8 PPG 3.7 APG and 11.5 RPG while players such as Russel Westbrook averaged 21.9 PPG 11.3 RPG and 11.3 APG and didn't make the team. The argument often used is that a player can average less stats but have their team performing better to make it to the All-Star game, but the Orando Magic and Washington Wizards were performing about the same. The real reason is because there are many more elite point guards in the NBA tha elite centers. 

In the game of basketball, there are 5 players on the court at a time on each team. Traditionally there have been 5 different positions. However, from a stastical viewpoint are there truly 5 different positions in the game of basketball? 


# Model Description
We will use data from: https://www.basketball-reference.com/leagues/NBA_2020_per_game.html to build 3 machine learning models to predict the a player's position based on their statistics. We will use RandomizedSearch Cross Validation for parameter selection.

  1. **3 Position Model**
  
    Predicting a player's position from one of 3 options
    1. Guard
    2. Wing
    3. Big Man

  2. **5 Position Model**

    Predicting a player's position from the traditional 5 positions
    1. Point Guard
    2. Shooting Guard
    3. Small Forward
    4. Power Forward
    5. Center

  3. **2 Position Model**
   
    Predicting a player's position from one of 2 options
    1. Ball Handler
    2. Big Man
  

**Machine Learning Algorithms Used: Random Forest, Multiclass Logistic Regression**

# Results

  1. **3 Position Model**

  Predicted a player's position with 81% Accuracy using a Random Forest Algorithm.

  2. **5 Position Model**

  Predicted a player's position with 66% Accuracy using a Random Forest Algorithm.

  3. **2 Position Model**

  Predicted a player's position with 88% Accuracy using a Random Forest Algorithm.




# Interpretation

From the results we can see that as the number of positions the model is predicting between goes down the model accuracy goes up. This is because players such as LeBron James, Luka Doncic, and Giannis Antetokounmpo are listed as Forwards, but in all reality are the primary ball handler when they are on the floor. This demonstrates that statistically in the Modern NBA there is no significant difference between players at each position. The NBA is clearly moving towards an era of positionless basketball. Should the NBA change it's All-Star game selection process to be positionless? If the top players in the league are all one position, why should we roster average players for the sake of meeting a position requirement? 

@AdamSilver
   
   
