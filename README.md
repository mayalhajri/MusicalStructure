# MusicalStructure
![alt text](https://i.imgur.com/2p8ceXu.jpg)
![alt text](https://i.imgur.com/N8MOcM5.jpg)
![alt text](https://i.imgur.com/M2Da0hW.jpg)
![alt text](https://i.imgur.com/Pb6nlPj.jpg)
![alt text](https://i.imgur.com/W71Tf3b.jpg)
![alt text](https://i.imgur.com/Ux0uSIX.jpg)

# Project Overview
This project is a chance for you to combine and practice everything you learned in this section of the Nanodegree program. You will be making the structure of a music app using intents and empty activities.

The goal is to design and create the structure of a Music app which would allow a user to play audio files. There are many music player apps, and they make a wide variety of design choices. It will be your job to decide what kind of music app your structure would turn into and build out that structure using intents. Will you build an app to play music from the user’s library of music? Will you build an app to stream random songs from a database? Will you build a musical suggestion engine? Those choices are up to you!

# Why this project?
In the most recent portion of the Nanodegree program, you learned how to think about the structure of an app and how to use OnClickListeners and explicit Intents to link between different activities within your own app. Practicing these skills will drastically improve the quality of the apps you build down the road.

# What will I learn?
This project is about combining various ideas and skills we’ve been practicing throughout the course. They include:

Designing an app experience to achieve a certain goal,
Creating new activities ,
Using explicit Intents to link between activities in your app ,
Using OnClickListeners to add behavior to buttons using Java code.

# Build Your Project
For this project, you will be thinking deeply about the structure of an app and laying out that structure in Android.

# Project Goals
You won't need to implement the actual music playing functionality. You just need to describe it. The goal of this project is to plan for building an app that has the structure of a music playing app to practice app design and the use of explicit intents to navigate around the app.

Each Activity should contain a TextView that describes the Activity. If you decide to mock up the content, or add real content, the reviewer might comment on your work, but it will not be considered to meet the requirements.

# Getting Started
First, take a look at different kinds of music player apps. If you're having trouble, check out the Play Music app, the Pandora Radio app, and the Spotify app to start with.

Think about what kind of music player you would like to build. Will you make a streaming app? One that plays music from the device's library? Will you make a music discovery app?

# Design Planning
Once you've chosen, write out a couple of ways you could structure your app. Think about where a user will start and what the most common use case of the app will be.

Select a potential structure and create an app with that structure in Android Studio. Your app should have 3 to 6 Activities. Some ideas for Activities would be:

"Now playing" screen

List artists, albums, playlists, or podcasts

Detail screen or screens for individual artists, albums, or podcasts

Store screen for buying music online

Search screen

Each Activity should contain a TextView which tells a user the point of the screen. You should also add a collection of buttons indicating what Activities can be reached from the current one. Use OnClickListener objects to make your buttons change Activity using Intents. Each activity should have a TextView that displays the purpose of the activity, as well as buttons that will let you navigate to other activities.

For example, a "Now Playing" Activity should have a TextView that describes the screen. It can also contain buttons that move to the Song Detail or Artist Detail Activities.

Finally, do some research on the technical hurdles and add a potential solution to each screen. The solution could be Android libraries or classes, an API on the internet, or code you could plan on writing. You do not need to actually implement any functionality.

# The required components for this project are:
App should have 3 to 6 Activities
Each Activity contains a TextView explaining the Activity and the buttons that allow the user to change Activity
One of those Activities is a Payment Activity. For this Activity, find an external library or API that can be used in this situation. In the TextView of this activity, describe the library or API and how it can be used.
Many students ask, why is the Payment Activity required? When creating an app, developers commonly rely on existing external libraries or APIs so they don't have to re-write and maintain functionality that already exists. Processing payments or logins are common examples. As the creator of the Music app, your focus is on creating a smooth music playing experience, so leveraging existing code whose focus is on payments allows you to focus on developing your Music Player rather than developing Payment processing functionality.

Your project will be evaluated using the [Musical Structure project rubric.](https://review.udacity.com/#!/rubrics/159/view)
