## Budget Tracker
This Budget Tracker application allows users to add expenses and deposits to their budget with or without a connection. When entering transactions offline, the total budget will populate when brought back online.

## Links

Deployed Application: https://budget-tracker017.herokuapp.com/
Link to watch the app: https://drive.google.com/file/d/1plbss2xMqKtUIFDY5g2zL6TWRlDb1AKi/view

## Technologies

<ul>
    <li> Service Workers </li>
    <li> Mongo DB </li>
    <li> Manifest </li>
    <li> Mongoose </li>
    <li> Express </li>
</ul>

## Description

The purpose of this application is for users to be able to add expenses to their budget with or without a connection.  Expenses that are entered offline are also re-populated when a user is back online. With provided code, I worked on building a manifest.webmanifest and service-worker.js to have this application work successfully offline. 

The manifest.webmanifest page holds the basic meta description of the application including the images and color themes. It also tells the server the main url and that it is a standalone application. 

The service-worker.js file holds most of the information to convert the application to a functioning offline product. This page consist of four main components. First, all the pages that would like to cache, so they show up when the application goes offline. These pages are listed under FILES TO CACHE. Second is the install code, that starts the process of installing the application. Third, is the activate and fourth is the fetch code to have the application work offline. The service worker page was vital to making this application successfully work offline. 

## Images 
<img src="images\budgetoffline.png">