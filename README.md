# Hybrid-Mobile-App
 
## Synopsis
This project is a hybrid mobile application. It combines the approach for a native application and the approach for a mobile web application to arrive at an end product that is embedded in the web view with partial implementation in native code, comparable to native applications in terms of speed, and has some access to device capabilities. This application uses a json-server as a static web server to store data and allow users to access data. Additionally, Ionic adds its own services and directives that can be used in the design of the application.
 
## Technologies
* AngularJS
* Ionic
* Cordova
* JSON Server
 
## Ionic Framework
Ionic is an HTML5 based SDK that enabled you to design mobile applications with a native look and feel. It is essentially an Angular single page application- it uses Angular as a framework for it's JavaScript portion and all AngularJS features are accessible within Ionic.
 
#### Prerequisites
* NodeJS
* Gulp
* Bower
 
#### Installing Ionic:
<pre><code> sudo npm install cordova ionic -g </code></pre>
 
#### Scaffolding an Application:
<pre><code> sudo ionic start   </code></pre>
 
#### Adding Platforms:
<pre><code> sudo ionic platform add ios
 sudo ionic platform add android</code></pre>
 
#### Viewing Ionic App in Browser:
<pre><code> sudo ionic serve </code></pre>
 
## Cordova
Cordova is used by the Ionic Framework to reach out to a native platorm (iOS/Android/etc) acting as a wrapper for Ionic.
 
## JSON Server
The JSON server is a node module that provides a simple way to set up a web sever that supportss a REST API server. It can also provide static web content from a folder
 
#### Installing
<pre><code> sudo npm install json-server -g </code></pre>
 
#### Starting the Server
Navigate to where the JSON server files are located. In this application they are located at Hybrid-Mobile-App/json-server/. Here, there is a file called db.json which contains data for our application.
<pre><code> json-server --watch db.json </code></pre>
 
 
 
 
