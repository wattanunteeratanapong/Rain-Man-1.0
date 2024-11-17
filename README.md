# Rain Man 1.0
![caca63488d914e978915f7a4262f20917515299e91b767fad0a8bd37f795add7 _SX1080_FMjpg_](https://github.com/user-attachments/assets/2f5021a9-748d-4e16-b6a9-ac283aee165e)<br><br>
Have you ever heard of a movie called "Rain Man"? Well "Rain Man" is a movie about two brother, the elder brother is a man who is really really smart plus he had a photographic memory, he could remember everything that he saw, with these ability he outsmart the casino in a game of Blackjack, he using his brain to calculate probability in his head and make a lot of money. Blackjack is a game that heavily relie on math more than most of the other games, which often depend heavily on luck or bluffing. With a good mathmatical strategy, player might be able to turn an odd to my favor just like a Rain Man did. So i decide to do this project, to tried to create algorithm that replicate his play style. <br><br>


## Overview
According to my past repository, i tried to find which side have more edge. Conclusion from that experiment, the edge is really on the house side. If we didn't have any strategy and play 1v1 against the dealer, the longer we play the more we likely to lose. Because of Blackjack is design for a dealer to have more edge than a player. By letting player play before the dealer, this could lead to player getting busted before the dealer are actually play. But with a good technique, it could reduce busted rate and help manage cash in a long run. <br>
You can also checkout this repository if you wanna know why odd are on the house side : <br>
https://github.com/wattanunteeratanapong/Blackjack-House-Edge-Study <br>

Technique that we are gonna use in this project 
1. Hi-Lo Card Counting System (For manage a bet amount in each round, if true count is high we bet high, if it's low we bet low)
2. Basic Strategy Chart (For lower risk of getting busted)
<br>

## Control Variable
- This scenerio test 1v1 against dealer
- Using 6 deck of card, similar to a real casino
- Re-Shuffle the deck after it is below 70% of total amount of deck, similar to a real casino
- "Splitting" and "Doubling Down" are not allow in this experiment
- Test around 10 million times, the more testing times the closer to theoratical probability
<br>

## Hi-Lo Card Counting Technique 
Hi-Lo Card Counting Technique is used for keeping track of the ratio of high to low cards remaining in the deck <br>
2, 3, 4, 5&nbsp;&nbsp;&nbsp;are valued at +1 (low cards) <br>
7, 8, 9&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;are valued at &nbsp;&nbsp;0 (neutral) <br>
J, Q, K, A&nbsp;&nbsp;are valued at -1 (high cards) <br>
Running Count as cards are dealt, players keep a "running count" based on the assign value<br>
True Count is a division of running count and the estimated number of remaining decks<br>
The higher true count is the higher we should bet <br><br>
![S__120848389](https://github.com/user-attachments/assets/ed07af38-9a1f-4374-afc6-6a8b9e582f80) <br>
<br>

## Basic Strategy Chart 
Basic Strategy Chart is a chart that tell the player to "Hit" or "Stand", depend on player and dealer hand. This technique significantly lower player busted rate. <br><br>
![S__120848388](https://github.com/user-attachments/assets/0533cb70-34a1-4aa1-8119-8590cb9b2293) <br>
Credit : <a href="https://www.blackjackapprenticeship.com/blackjack-strategy-charts/">Learn Blackjack Strategy</a> <br>
<br>


## Simulation

## Result

## Conclusion

## Source
<a href="https://youtu.be/eyoh-Ku9TCI?si=7lreOZh8m4uysgaU">How to Play Blackjack | wikiHow</a>
<br>

<a href="https://youtu.be/rjfLuM-Pqr8?si=2WPhj4LbADi6T7jW">Can I make money counting cards? | Mike Boyd</a>
<br>

<a href="https://youtu.be/SHK2C-QQR-k?si=cSkeUIwglOLbW2gK">How to Count Cards (and Bring Down the House)</a>
<br>

<a href="https://youtu.be/G_So72lFNIU?si=BCeG_7-1XNIjAAPz">Blackjack Expert Explains How Card Counting Works | WIRED</a>
<br>

<a href="https://www.wikihow.com/Count-Cards-in-Blackjack#:~:text=Every%20time%20a%20card%20is,subtract%201%20from%20the%20total">How to Count Cards in Blackjack</a>
<br>

<a href="https://news.williamhill.com/casino-guides/blackjack-hit-stand/#:~:text=In%20general%2C%20if%20you%20have,showing%2C%20then%20you%20should%20stand">To hit or stand in Blackjack – that is the question!</a>
<br>

<a href="https://www.blackjackapprenticeship.com/blackjack-strategy-charts/">Learn Blackjack Strategy</a> 
<br>
