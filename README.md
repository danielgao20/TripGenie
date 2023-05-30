# TripGenie

A revolutionary way to travel.

<!-- ![Home Page](https://github.com/danielgao20/TripGenie/blob/master/images/homepage.png) -->
<img src="https://github.com/danielgao20/TripGenie/blob/master/images/homepage.png" alt="Home Page" width="500">

## Overview

In 2023, planning a trip is a daunting task. The seemingly endless options for hotels, flights, and destinations, combined with the constraints of time and cost, turns a simple chore into a logistical nightmare. 

### That's where TripGenie comes in. 

TripGenie streamlines trip planning by taking care of the logistics, freeing travelers from the burden of organizing every detail. Our goal is to make travel planning more accessible, efficient, and enjoyable for everyone. Put simply, your trip is our command.

## Core Functionality

After logging in, users are taken to the app’s homepage, where they can scroll through a 3-D globe with markers indicating places they’ve already traveled to and future destinations. This page also features a navigation bar on the bottom that allows the user to view past and favorite trips. The middle button is the heart of the app, which if clicked will prompt the user to answer a series of questions about their upcoming trip. These responses will be recorded and analyzed by machine learning algorithms to create a personalized experience that caters to each individual’s needs.

<img src="https://github.com/danielgao20/TripGenie/blob/master/images/trippages.png" alt="Trip Pages" width="500">
<img src="https://github.com/danielgao20/TripGenie/blob/master/images/itinerarypage.png" alt="Itinerary Page" width="500">

## How TripGenie was built

The front end of the app was primarily built using Flutter and FlutterFlow. FlutterFlow was the driving tool behind the UI of the app. Using this UI design, we used Flutter and its Dart language to create the design of the app as well as its animations. The large globe featured in the home page of the app was an implementation of an existing API. The app’s functionality was driven by its backend. Essentially, we used Python and Google Cloud to create a function that is triggered by an http request. This triggered function then triggers our machine learning model to return results based on the unique data the user enters as responses to question prompts.  

Here is our full-stack flow chart:

<img src="https://github.com/danielgao20/TripGenie/blob/master/images/tripgenieflow.jpg" alt="Flow Chart" width="500">

## Challenges

As with any fullstack project, it’s essential that the front end and back end are seamlessly integrated. In our project, the many moving parts, consisting of different APIs, frameworks, and languages initially made it difficult to create one consistent app. Fortunately, by the end of the competition, we were able to figure out how to integrate each component of the app together, making for a simple and smooth experience for the user.

## Accomplishments 

Above all, we’re proud of building a completed project from scratch. Building any sort of project on a tight schedule is no easy task, so the team is very pleased to have built an app that serves a real-world purpose rather than having built an app for the sake of making one. 

## Looking Ahead

While we're happy with the product we've made, we recognize that the best trips are shared expereinces. That's why we want to implement a feature that allows for group trip planning, which seamlessly allows users to create a trip for a group of up to 18 companions.
