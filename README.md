# text-eidtor-PWA

## Project
As a developer, I want an application that creates notes and code snippets with 
or without internet connection. I make notes on a regular daily bases for iam increasing
my understanding of new concepts in programming languages. It would be a great loss if I 
were to lose connection to the internet one day. This application would make note 
taking accessible to me anytime and anywhere.

## Description

To have my application function as intended, I have provided the following:

  * Javascript files will be bundled by using Webpack
  * Opening the text editor invokes IndexedDB to create a database storage
  * Entering content and clicking off the DOM window will save the content
  * Reopening the text editor after closing will retrieve content from the IndexedDB
  * Clicking the install button will add the application to my desktop as an icon
  * Loading the web application will have a registered service worker using Workbox
  * Registering a service worker will have the static assets preached upon 
  loading along with subsequent pages
  * Deploying to Heroku should have proper scripts for a webpack application

## Installation
The npm packages and programs used for the application include: 

 * Express
 * IDB
 * Webpack
 * HTML WebpackPlugin
 * Workbox
 * Node.js
 * Concurrently
 * Javascript

The user can install the application into their device by clicking the install
button after opening the application on the browser. Otherwise, use it from the
deployed application link.
