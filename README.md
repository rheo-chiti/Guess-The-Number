# Guess-The-Number
```This application tries to guess the user number and also tells the number of moves taken.```
## Screenshots
<pre>Start Game Screen                 Game Screen                        Game Over Screen</pre>
<p float="left" >
<img src="https://github.com/rheo-chiti/Guess-The-Number/blob/master/Images/StartGameScreen.jpeg" width=250 height=400 hspace="10"  title="Start Game Screen" alt="gfdfjgd"/>
<img src="https://github.com/rheo-chiti/Guess-The-Number/blob/master/Images/GameScreen.jpeg" width=250 height=400  title="Game Screen" alt="gfdfjgd" hspace="10"/>
<img src="https://github.com/rheo-chiti/Guess-The-Number/blob/master/Images/GameOverScreen.jpeg" width=250 height=400  title="Game Screen" alt="gfdfjgd" hspace="10"/>
</p>


## How to run this on your system

- Install node from [here](https://nodejs.org/en/)  
- Install npm and expo  
- Install expo client for your [device](https://docs.expo.io/versions/latest/get-started/installation/)  
- Install Visual Studio Code from [here](https://code.visualstudio.com/)  
- Install Git from [here](https://git-scm.com/downloads)  
- Fork the repository  
- Clone the repository in VS Code by searching for ```Git: Clone``` and then enter the url of the forked repository  

## Working

- User can enter any number between 1 and 99   
- Computer will try to guess the number   
- Final screen displays the number of guesses made by the computer

## Technologies  
- [React Native](https://facebook.github.io/react-native/docs/tutorial)  

## Components   
- [Card](https://github.com/rheo-chiti/Guess-The-Number/blob/master/components/Card.js)   
- [Number Container](https://github.com/rheo-chiti/Guess-The-Number/blob/master/components/NumberContainer.js)   
- [Body Text](https://github.com/rheo-chiti/Guess-The-Number/blob/master/components/BodyText.js)  

## Screens  
- [Start Game Screen](https://github.com/rheo-chiti/Guess-The-Number/blob/master/screens/StartGameScreen.js)  
- [Game Screen](https://github.com/rheo-chiti/Guess-The-Number/blob/master/screens/GameScreen.js)  
- [Game Over Screen](https://github.com/rheo-chiti/Guess-The-Number/blob/master/screens/GameOverScreen.js)  


## How this app works  
User choose a number between ```1 and 99``` and then starts the game.After that the computer tries to guess the number and the user tells whether the predicted number is less than the choosen number or greater than the choosen number. If the user tries to give the wrong instructions an alert dialog is displayed. After getting the instruction, computer again display another number by the help of a ```random function```. All the guesses made by the computer is also displayed on GameScreen with the help of [FlatList](https://facebook.github.io/react-native/docs/flatlist). When the computer guess the choosen number , number of rounds to reach the choosen number is also displayed.  

## Future Features  
- UI Improvements/Animations  
- Game Logic Improvement  
