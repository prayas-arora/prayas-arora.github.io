---
layout: page
title: Projects
permalink: /projects/
---
This page includes some of my personal projects.
I have skipped my work related projects, you can find those in my [resume](https://bit.ly/2Y7xSkF). 

### The Society Fair

A website for events of societies under CSED, TIET along with attendance, details and media for each event. Also, an interface for students to contact society admins. Link: [sf.thapar.edu](http://appforms.thapar.edu/sf/)
<div style="text-align:center">
    <img src="/SocietyFair/Home.PNG" rel="Society Fair" alt="User Section: Home" class="popitup">
    <img src="/SocietyFair/IEEE.PNG" rel="Society Fair" alt="User Section: Society View" class="popitup">
    <img src="/SocietyFair/IEEE_2.PNG" rel="Society Fair" alt="User Section: Events_View" class="popitup">
    <img src="/SocietyFair/IEEE_open_event.PNG" rel="Society Fair" alt="User Section: Open Event" class="popitup">
    <img src="/SocietyFair/IEEE_POSTER.PNG" rel="Society Fair" alt="User Section: Poster View" class="popitup">
    <img src="/SocietyFair/Event_attendance.PNG" rel="Society Fair" alt="User Section: Event attendance" class="popitup">
    <img src="/SocietyFair/Event_attendance_1.PNG" rel="Society Fair" alt="User Section: Event attendance_2" class="popitup">
    <img src="/SocietyFair/Event_Images.PNG" rel="Society Fair" alt="User Section: Event Images" class="popitup">
    <img src="/SocietyFair/Coordinator_Login.PNG" rel="Society Fair" alt="Admin Section: Coordinator Login" class="popitup">
    <img src="/SocietyFair/Coordinator_Home_Page.PNG" rel="Society Fair" alt="Admin Section: Problem Dashboard" class="popitup">
    <img src="/SocietyFair/Adding_new_event.PNG" rel="Society Fair" alt="Admin Section: Adding new event" class="popitup">
    <img src="/SocietyFair/New_event_2.PNG" rel="Society Fair" alt="Admin Section: Adding new event_2" class="popitup">
    <img src="/SocietyFair/Contact.PNG" rel="Society Fair" alt="User/Admin Section: Contact" class="popitup">
</div>

### Detection of Atrial Fibrillation of heart from a Single Lead ECG recording
The goal of this project was to implement a deep-learning algorithm that classifies electrocardiogram (ECG) recordings from a single-channel handheld ECG device into four distinct categories: normal sinus rhythm (N), atrial fibrillation (A), other rhythm (O), or too noisy to be classified (~). This model was guided by the paper [Convolutional Recurrent Neural Networks for Electrocardiogram Classification](https://arxiv.org/abs/1710.06122) by Zihlmann et al. which was published following the authors' contribution to the [2017 PhysioNet/Computing in Cardiology (CinC) Challenge](https://physionet.org/challenge/2017/). I followed [Andreas Werdich's](https://github.com/awerdich) implementation of the above paper. I improved the results of this model by penalizing weights that apply to higher frequency classes inorder to balance all the classes and reduce prominent peaks in validation accuracy.

### Fallingrain.com data scraper
A web scraper written in python that scrapes [fallingrain.com](http://www.fallingrain.com/world/index.html) and dumps a CSV file containing State, City, Latitude, Longitude, Elevation and Estimated Population for every place in India.

<div style="text-align:center">
    <a href="https://github.com/prayas-arora/web-scraper-fallingrain">View Github Repository</a>
</div>

### User Attendance & Activity Monitoring System
A website that monitors a visitor’s activity, prints exit slips for day scholars and links this data with student IDs. This website is currently live in [Nava Nalanda Central Library, TIET](http://library.thapar.edu/).

### Smart Car Parking System
Focused on making the process of finding a parking spot, a breeze. An array of sensors to detect the car, a machine learning algorithm for finding an optimal parking slot in real time, Google Maps API integration and Digital Image Processing for car recognition. This project is under development.
