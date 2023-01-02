# Progressive Web Applications (PWA) Challenge: Text Editor

# Description

# User Story

```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client-server folder structure
WHEN I run `npm start` from the root directory
THEN I find that my application should start up the back end and serve the client
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
THEN I find that the content in the text editor has been retrieved from our IndexedDB database
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using Workbox
WHEN I register a service worker
THEN I should have my static assets precached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Mock Up

## Grading Rubric

```
Technical Acceptance Criteria: 40%
Satisfies all of the above acceptance criteria plus the following:
Application uses IndexedDB to create an object store and includes both GET and PUT methods.
Application works without an internet connection.
Application automatically saves content inside the text editor when the DOM window is unfocused.
Application is bundled with webpack.
Application has created a service worker with Workbox that caches static assets.
Application uses Babel in order to use async / await.
Application has a generated manifest.json using the WebpackPwaManifest plug-in.
Application can be installed as a Progressive Web Application.

Deployment: 32%
Application is deployed to Heroku at live URL with build scripts.
Application loads with no errors.
Application’s GitHub URL is submitted.
GitHub repo contains application code.

Application Quality: 15%
Application user experience is intuitive and easy to navigate.
Application user interface style is clean and polished.
Application resembles the mock-up functionality provided in the Challenge instructions.

Repository Quality: 13%
Repository has a unique name.
Repository follows best practices for file structure and naming conventions.
Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.
Repository contains multiple descriptive commit messages.
Repository contains a quality README file with description, screenshot, and link to deployed application.
```

```
[Google Lighthouse Links](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk/related?hl=en) to an external site.is a tool that helps improve the performance of web applications by providing audits for performance, accessibility, Progressive Web Apps, and more. It's included in Chrome DevTools and is available as a plugin.

Live Server Links to an external site.is a VS Code extension that allows you to launch a local development Server with a live reload feature for static & dynamic pages. You will use Live Server when working with the client directory of your project.

[Concurrently](https://www.npmjs.com/package/concurrently) Links to an external site.is an npm module that allows you to run multiple commands at the same time.

webpack Links to an external site.is a module bundler for JavaScript that simplifies front-end web development by generating static assets from modules with dependencies and using plugins and loaders to help automate certain optimization strategies. You’ll use the webpack Links to an external site.and webpack CLI Links to an external site.packages in your project.

Babel Links to an external site.is mainly used to convert ECMAScript 2015+, also known as ES6, code into a backwards-compatible version of JavaScript that can be used on older browsers.

IndexedDB Links to an external site.is a Web API capable of storing large amounts of data directly in the browser.

idb Links to an external site.is a small wrapper that makes it easier to implement IndexedDB CRUD methods.

Workbox Links to an external site.is a set of libraries that can generate a production-ready service worker for your Progressive Web App.

HtmlWebpackPlugin Links to an external site.is used to generate an HTML page in the build directory.

webpack-pwa-manifest Links to an external site.is a plugin that generates a manifest.json for your PWA, with auto icon resizing and fingerprinting support.

heroku-prebuild Links to an external site.is a hook used to tailor the pre-build process.
```