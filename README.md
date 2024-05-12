# 19 Progressive Web Applications (PWA): Text Editor

## Description

By utilising PWA features, we will be building a text-editor that runs in the browser. It will showcase features of data persistence techniques that serve as a redundancy in case one of the options is not
supported by the browser and will also function offline.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Usage](#usage)
- [Deployed-Link](#Deployed-Link)

## Technology Used
- Javascript
- Express
- PWA mechanics


## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application
```

## Usage
- Upon retreiving the data, you must run the commanc 'npm i' to install the required applications for the files to fun.
- Once the above command is completed, you are able to run the code through 'npm start'.
- Go to the following link: http://localhost:3000/ to see the application.

## Deployed-Link
Deployed -Link: https://pwa-text-generator.onrender.com
