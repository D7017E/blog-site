---
layout: post
title:  "Week 37: Planning and Research"
date:   2022-09-14 15:44:00 +0200
published: true
---

Together with [Grepit AB](https://www.grepit.se/) we are developing
a smart home system. This smart home system will consist of a
mobile application, a backend, and a robotic arm that will
automatically insert a charging cable into an electric vehicle.

This first week we started by defining the areas of development.
We came to the conclusion that we needed three groups:
<ol>
    <li> Frontend </li>
    <li> Backend </li>
    <li> Robot arm & AI </li>
</ol>

### Frontend

The frontend is a mobile application that can
scan a QR code to connect to the smart home. It will
also support user registration, inviting users to 
a smart home, and the setting of user roles. It is
also through this app that the smart home is controlled
by the user.

### Backend

The backend will consist of services and databases.
These services will handle communication between
the mobile app and the various smart home systems.
They will also persistently store data about users and 
smart homes in different databases.

It is via the backend that the robot arm's start signal
is sent.

### Robot arm & AI

To facilitate the automatic insertion of a charging 
cable, we thought it necessary to use some sort of AI
or machine learning. This means collecting training data,
pictures of charging ports, and training a model on that
data.

The robot arm will be controlled with the help of an
existing API. 