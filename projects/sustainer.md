---
layout: project
type: project
image: img/own-projects/sustainer-web-app/sustainer-logo.png
title: "Sustainer"
date: 2023-12-07
published: true
labels:
  - Web App
  - Full Stack
  - Software Development
  - JavaScript
  - Meteor
  - MongoDB
  - React Boostrap
  - Git / GitHub
  - IntelliJ IDEA
  - Digital Ocean
summary: "A web app that monitors and keeps track of reusable containers at large public events."
---

Sustainer was the final project developed in my software engineering ICS 314 class. The project consisted of 5 group members, each with our own distinct roles and tasks in order to complete a functional,full stack application. More details are provided below. 

## Project Overview & Details

I was responsible for designing and implementing the GUI in this project. This consisted of creating a sketch of the envisioned interface, deciding the size restrictions of the elements and overall window panel, choosing a fitting color scheme for the buttons, and checking the win conditions of the game. 

Upon entering the game, the left panel contains a choice of 3 buttons of where the user can either learn how to play the game, play the game (after playing at least one time), or quit the game. A bottom-middle panel of options is displayed for the user to pick their choice of rock, paper, or scissors. The bottom left panel contains a score counter for the number of times that a user has won, lost, or tied the game. 

Once the user has chosen an option, the computer will randomly make a choice and a text bubble will display the result of the game. In addition, the score counter will update based on the results. The user can then hit **Play Again** to play more games. The picture below shows an example of the user playing through the game and the implemented GUI.

## Roles & Contributions

<img class="img-fluid" src="../img/own-projects/RPS-game/rps_game.png" alt="">

One of the main concepts behind action-driven programming is resetting the method conditions when a user clicks a certain button. Some sample code below illustrates the performed actions that need to be reset in the Java.awt.event library when the user hits **Play Again**. These include the background colors, choice buttons, images, and borders:

When the user decides to stop playing and quits by hitting the **Quit** button, a display message will indicate that the window will automatically close. Furthermore, a _scores.txt_ file is created in the same directory as the ran program window. This file shows the results of every round or game the user played against the computer, including the choices that were made. 

<img class="img-fluid" src="../img/own-projects/RPS-game/scores_txt.png" alt="">

## Learning Points from Project

From this project, I was able to further my knowledge on how object-oriented programming (OOP) works. This project allowed me to practice the employment of creating private object classes and using its methods to create the main back-end frame of the game. I learned that the process of adjusting the pixel width of image icons and the dimensions of the borders in panel elements of the interface can be quite time-consuming in order to create a cohesive and aesthetic-looking GUI. I also enhanced my learning in technical aspects, such as learning how to read/write to a file and set graphical elements with the Java Swing and AWT libraries. More importantly, however, I got to experience the entire of process of creating an entire project, all of which included planning, designing, programming, testing, and implementing the code for the RPS game.

<br>
<hr>

#### Links 

* View our deployed app: <a href="https://sustainer.online/" target="_blank">**Sustainer**</a>
* View our source code: <a href="https://github.com/sus-tainer/sustainer" target="_blank">**Repository on GitHub**</a>
* Read more about our project: <a href="https://sus-tainer.github.io/" target="_blank">**Project Documentation & Background Information**</a>
