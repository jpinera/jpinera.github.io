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

## Background Information

Sustainer was the final project developed in my ICS 314 class, which focuses on understanding software engineering fundamentals and developing proper development practices. The project consisted of 5 group members, each with our own distinct roles and tasks in order to complete a functional,full stack application. More details are provided below. 

<div class="text-center p-4">
  <img width="650px" src="../img/own-projects/sustainer-web-app/sustainer-home-page.png" class="img-thumbnail" >
</div>

## Project Overview & Details

Sustainer is a web app that allows easy access to rent and keep track of containers at large public events. The idea behind this app is to support a circular economic system when consumers order food at food trucks and other vendor locations. This is proposed through the implementation of using reusable containers at events, such that users can return these containers after eating their food. <a href="https://www.zerowasteoahu.org/" target="_blank">**Zero Waste Oahu**</a> (ZWO) is a nonprofit organization that has promoted this idea for a cleaner and stronger impact on the environment. The main problem, however, is that ZWO only receives a 60% return rate for these reusable containers at public events, which include beach cleanups, farmers market shops, and other fundraisers. As a result, it is very difficult to continue reusing these containers for future events when not all of them are being properly returned. 

Sustainer aims to solve this problem by holding users accountable for containers that aren't returned via a collateral-accountability system. The app also allows members of the ZWO organization to keep track of any containers that are in use, or have been returned, by users. Doing so will keep the environment sustainable on the community level. It will also help improve the economic system that is envisioned by ZWO. 

The overall solution revolves around the concept of "transferring ownership" of the reusable containers throughout the process or cycle of ordering food at an event. In order to uniquely identify users, QR codes are created from a consumer's personal account. Upon ordering takeout from a vendor, users will scan their QR ID. Vendors will then scan the container with their food to link the associated container to that specific user. Users will then return the container in an appropriate ZWO bin. At the end of the event, organizers will scan these containers back in to reassign the container to admin owners. Containers that are still associated with a user or unaccounted for will charge the user a certain flat fee of $5 per container. Therefore, the app is  intended for 3 main audiences and consists of the following purposeful functions:
* <span style='font-family: monospace; color: #red;' target='_blank'>**Users**</span>: Create an account to get their QR Code and link a payment method as collateral
* <span style='font-family: monospace; color: #red;' target='_blank'>**Vendors**</span>: Order containers from ZWO for specific events and view the inventory of containers. Scanning of containers for ownership can also be done here.
* <span style='font-family: monospace; color: #red;' target='_blank'>**Admin / Moderators**</span>: Scan and check containers back in. There are also options to charge a user for a container and add new containers to the database.

In terms of the technological toolsets, the app uses Meteor as the main stack for our web app development framework. React Bootstrap was used as UI frameworks for front-end development. JavaScript was the programming language used for coding, along with React hooks to add functionalities and enhance the user interaction experience (UX) on the website. IntelliJ Idea was used as the coding enviroment, with 

You can view and test out our deployed app <a href="https://sustainer.online/" target="_blank">**here**</a>. _However, please note that as of February 2024, the app may be unavailable due to the removal of the deployed servers_. In this case, please see the **Download and Installation** section in the  <a href="https://sus-tainer.github.io/#installation" target="_blank">**documentation here**</a> to run the app locally.


## Roles & Contributions

I was mainly responsible for designing and implementing the GUI in this project. This consisted of creating a sketch of the envisioned interface, deciding the size restrictions of the elements and overall window panel, choosing a fitting color scheme for the buttons, and checking the win conditions of the game.

<img class="img-fluid" src="../img/own-projects/RPS-game/rps_game.png" alt="">

One of the main concepts behind action-driven programming is resetting the method conditions when a user clicks a certain button. Some sample code below illustrates the performed actions that need to be reset in the Java.awt.event library when the user hits **Play Again**. These include the background colors, choice buttons, images, and borders:

When the user decides to stop playing and quits by hitting the **Quit** button, a display message will indicate that the window will automatically close. Furthermore, a _scores.txt_ file is created in the same directory as the ran program window. This file shows the results of every round or game the user played against the computer, including the choices that were made. 

<img class="img-fluid" src="../img/own-projects/RPS-game/scores_txt.png" alt="">

## Learning Points from Project

From this project, I was able to further my knowledge on how object-oriented programming (OOP) works. This project allowed me to practice the employment of creating private object classes and using its methods to create the main back-end frame of the game. I learned that the process of adjusting the pixel width of image icons and the dimensions of the borders in panel elements of the interface can be quite time-consuming in order to create a cohesive and aesthetic-looking GUI. I also enhanced my learning in technical aspects, such as learning how to read/write to a file and set graphical elements with the Java Swing and AWT libraries. More importantly, however, I got to experience the entire of process of creating an entire project, all of which included planning, designing, programming, testing, and implementing the code for the RPS game.

This project was presented at the 2023 <a href="https://www.zerowasteoahu.org/" target="_blank">**Hawaii Annual Coding Challenge**</a> (HACC) for the unique solution that our team had come up with. I found 

### Improving the App

Definitely some improvements.
<br>
<hr>

#### Links 

* View our deployed app: <a href="https://sustainer.online/" target="_blank">**Sustainer**</a>
* View our source code: <a href="https://github.com/sus-tainer/sustainer" target="_blank">**Repository on GitHub**</a>
* Read more about our project: <a href="https://sus-tainer.github.io/" target="_blank">**Organization Home Page & Project Documentation**</a>
