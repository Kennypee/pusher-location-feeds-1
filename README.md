# Real-time location-based traffic feed with Kotlin, Pusher and Node

Often times we like to track and visualize our applications in a central place. Feeds are great for this! In this tutorial, we'll build an Android app with an activity feed that allows users to broadcast their locations and share with all other connected users in realtime.  [Read More Here](https://paper.dropbox.com/doc/Pusher-Content-Style-Guide-and-Working-Instructions-t6XraokBLrRQ2jVsCW9k5)

## Getting Started

We’ll build an Android app to monitor the activities of a Node.js REST API. Every time the endpoint of the API is hit, Pusher will publish an event with some information (location shared by the user) to a channel. This event will be received in realtime, on all the connected Android devices.

## Prerequisites

This tutorial uses the following technologies

•	Pusher

•	Android Studio

•	Node

•	Webtask

To follow along, you’ll need to sign up with Pusher and gain access to your dashboard to create a pusher project. You will also need to have Android Studio v3+ installed to build the client part of this application. To build our server side script, you’ll need to download and install Node if you don’t already have it installed.  Finally you’ll need to create an account with Webtask to host our server.

## Built With

* [Pusher](https://pusher.com/) - APIs to power the realtime features
* [Maven](https://maven.apache.org/) – For Dependency Management
* [Webtask](https://webtask.io) – To host our Node server
