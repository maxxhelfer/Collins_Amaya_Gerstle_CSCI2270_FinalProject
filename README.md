# Collins_Amaya_Gerstle_CSCI2270_FinalProject
CSCI 2270 Final Project


 Design a blackjack game simulator with the use of vectors and linked lists.

-----------------------------------------------------------------------------------------------------------

Project Summary:

We are designing and implementing a blackjack game in which we are using vectors and linked lists. We will be using a Player structure that includes a linked list for the player's hand. The game will have the option to play with multiple decks, just like in a casino. The decks will be held in a vector, with each node being a card. Then we will have a random generator to shuffle the cards (we will have no dealer, just the computer dealing). Each player is initially allocated a certain amount of money with which to place bets. The player can decide their bet amount for each round. If you bust, our program will tell the other players you busted. Bets are automatically handled at the end of each round, and the player's money is updated. We will follow standard rules and we will try our best to implement a GUI, however since we haven't learned anything about GUIs we have no promises. 

-----------------------------------------------------------------------------------------------------------

How to Run:

*Setting up*
To set up the program in your complier you can either download all of the program files or copy and paste them into a new project.  Unlike common projects, our project uses two header files and two .cpp files.  Be careful in making sure that both are in the program project.  As far as choosing a compiler it is really up to you, program is designed around Code::Blocks. 

*Playing the program*
When the program starts, the user is prompted with a main menu.  The menu gives the user the choice to either begin or quit the blackjack game.  Once the decision is made to start the game, the user must make 4 choices; 1) Choose the number of decks to play with, 2) Choose how many players will be in the game 3) Enter how much money each player will start with, & 4) The names of each of the players. From there on, the user interface consists of command line prompts.  The program begins to deal and begins the game by giving each user a randomized pair of cards.  Then the user has the option to hit or stay.  The program is able to recognize the sum of the two cards in the user's hand.  The program is also able to tell if the amount the user bets is over the amount of allocated playing funds.  The program is also able to tell when the sum is a perfect blackjack and automatically awards the player.
  
-----------------------------------------------------------------------------------------------------------
  
Dependencies: None

-----------------------------------------------------------------------------------------------------------

System Requirements: Program built on Ubuntu Linux Code::Blocks but any IDE will work fine.

-----------------------------------------------------------------------------------------------------------

Group Members:

  David Gerstle (https://github.com/gerstled)
  Raul Amaya (https://github.com/ramaya38)
  Oliver Collins (https://github.com/OliverCollins)
  
-----------------------------------------------------------------------------------------------------------

Contributors: None

-----------------------------------------------------------------------------------------------------------

Open Issues/Bugs: No code for handling when a player runs out of money, and can no longer bet. 
  
