# BlackJack Program: Author: Muhammad Haseeb & Date: 06/07/2023
This is a code for a Blackjack simulator that is a one on one game between the dealer and a player. This code includes the rules of blackjack, probabilities, and strategy. This program breakdown is as follows:
1. The code assigns each card in a deck to a value in an array. Then two users receive two cards respectively at random using a rand function. 
2. The code displays the cards they received. Then the code will add the user 1's card values and display the total value of their cards. Then the code will add user 2's card values and display the total value of their cards. 
3. If any user gets an ace and a face card, they win immediately. If both users receive an ace and a face card respectively, the game is over and there are no losers. Give user 1 the choice to receive additional cards. After each new card, display the new total value of user 1 and the individual cards and suits they currently have. 
4. Calculate and display the probability of user 1 exceeding a total card value of 21 with the 2 initial cards.  Additionally, Calculate and display the probability of user 1 exceeding a total card value of 21 if an additional card is chosen and the total card value didn't exceed 21. Display the cards received on a new line. If the value of user 1 exceeds 21, they lose and if user 1 stays with their card value, they allow user 2 to keep receiving cards and display the total value after each card and suit on a new line. 
5. If user 1 has a total value of 21, wait to see if user 2 will receive either a total value of 21 or exceed the total value of 21. If user 2 gets a value of 21, then display that there are no losers. 
6. If the total of user 2  exceeds a value of 21, then display that the player has lost and user 1 has won. If user 2 has a greater value than user 1 or has a total value of 21, then display that user 2 wins.

How to Play:
1. User 1 is the player and User 2 is the dealer.
2. 2 Cards will be dealed and the addition of the cards will be displayed.
3. User 1 will be prompted with the choice to receive a card or stay with the current total value. Type "y" in the console to hit or "n" in the console to stay.
4. Analytical probabilities will be show before and after a ard choice to see the competitive edge user 1 has in beating the dealer. The proability shows the percentage chance the player has of exceeding a 21 value with a "hit". This gives the user strategical insight.
5. The player can hit until busting or stay and the dealer will run through a script where they will hit until either beating the user (getting closer to 21) or busting (exceeding the total card value of 21).
6. Then a user can run the code again to repeat the game.
