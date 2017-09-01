---
layout: project
type: project
image: images/typemecover.jpeg
title: TypeMe
permalink: projects/cotton
date: 201
labels:
  - Java
summary: A typing memory game that I developed for ICS 111. 
---

<img class="ui image" src="{{ site.baseurl }}/images/cotton-header.png">

This program is a memory game in which the player will be shown a random number of words.  The goal is for the user to memorize the words within the time given and input those words correctly and in the same order.  The game features a lives system and three difficulties: easy, medium, and hard.  Harder difficulties will have more words to memorize, less time to memorize the words, and less number of lives.  Inputting the words correctly will increase your score; as your score increases, the amount of time you must memorize the words decreases. Inputting the words incorrectly or running out of time results in the player losing a life.  If the user runs out of lives, then their final score is displayed.  The user is also prompted to input their name, after which they can view the leaderboard where the top ten players and their scores are displayed.  After the leaderboard is shown, the user can go back to the main menu and play again.

I worked on troubleshooting the program to see if any errors are made and needs to be fixed. Mostly worked on the user input, which gets the keyboard input and types it onto the screen, writing it to a save file and reading it. Also, worked on hiding the input that was printed on to the screen after it was typed. Helped on other things such as the timer, lives, randomization of words, etc. Created a randomization function as well as a class for user input. Created a loop so that when the game ends, the game restarts if the user wants to continue playing. Created a leaderboard to display on screen after the user runs out of lives.

I had learned quite a lot from this project. Especially since it was my first ever game that I had to create with a group. Even though the game itself is not much, it gave me a taste of what it would be like to work as a group in the future. Learning from this experience that not everyone is the same and that everyone also learns at a different pace that you yourself would. Therefore, I had realized that communication amongst team members is essential to a positive environment and to achieve a common goal as a group.

The source code for this game will be in: <a href="https://github.com/saehyuns/Projects/tree/master/TypeMe"><i class="large github icon "></i>TypeMe</a>

