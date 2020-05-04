# Readings-Notes-Repository

## Class 11 notes for my Readings in Code Fellows 301 Course

[Back To Main](README.md)


### Reading
[Watch EJS tutorial from WalkThroughCode on YouTube, Videos 1-5](https://www.youtube.com/playlist?list=PL7sCSgsRZ-slYARh3YJIqPGZqtGVqZRGt)

Note that this series of videos should take approximately 20 minutes to watch

#### 1st video
Was a basic introduction getting ready for other videos

#### 2nd Video
dicusses the ```const path = require('path')``` for using the join method to combine paths together and makes a server.js which displays a page with Hello World

#### 3rd Video
Is about inject variables via ejs into a page
This is where he uses strawberries and compares them to mustache, explains how to pass variables in, requested we like and subscribe which was unexpected

#### 4th Video
Uses API and imports resources, as well as defining routes

#### 5th video
Uses the json placeholder API
discusses labeling functions as async and using ```await```
then chaining promise with a then() to properly handle it


Additional Resources
Reference: [Google Books API Docs](https://developers.google.com/books/docs/v1/using#WorkingVolumes)


**Reference:** [EJS Docs](http://ejs.co/)

**Bookmark/Skim**

**Skim:** [EJS Tutorial](https://scotch.io/tutorials/use-ejs-to-template-your-node-application)

**Skim:** [Source Code for the EJS Tutorial](https://github.com/scotch-io/node-ejs)

Review the code that goes along with the tutorial

```// load the things we need```
```var express = require('express');```
```var app = express();```

```// set the view engine to ejs```
```app.set('view engine', 'ejs');```

```// use res.render to load up an ejs view file```

```// index page ```
```app.get('/', function(req, res) {```
```	res.render('pages/index');```
```});```

```// about page ```
```app.get('/about', function(req, res) {```
```	res.render('pages/about');```
```});```

```app.listen(8080);```
```console.log('8080 is the magic port');```