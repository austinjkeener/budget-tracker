# budget-tracker
By Austin Keener <br>
<i>These are the terms of installation for this code.<i>
## Table of Contents
### 1. Usage <br>
### 2. License<br>

link to repo: https://github.com/austingraphicandweb/budget-tracker
link to deployed application: https://aqueous-dusk-51297.herokuapp.com/
<hr>

## Screenshot

![screenshot](./screenshot.png)


<hr>


## Usage
<i>Copy everything that is in the develop folder within the class repo over to my repo, but not the folder itself. Offline functionality is provided by indexdb from earlier in section 18. Check to make sure app runs locally and then push to heroku. Check out robo 3t to make sure that the database is visible. The connection is made possible through the server.js file using mongoose.connect. When setting up Heroku for this project I need to install the addon 'mlab' within Heroku. Make sure port is set up for ENV variable. Also do the same thing for mongodb by using process.env.PORT and process.env.MONGOD_URI. It is important to test and make sure that the Heroku logs are successful and that the app loads ok. <br>Then I need to add a webmanifest, service worker, cache storage, and indexdb. The web manifest goes into the public folder, for starters. Structure the manifest folder with proper names and file paths relavent to the repo. Also correctly add manifest to the HTML document. Make sure that images get resized. Also fix other warnings within the manifest. <br> Next create the service worker. Make a service worker.js file in the public folder. Test service woker with console.log. Also, add service worker script to HTML doc. Next add cache to service worker. Copy and paste the cache info into serviceworker.js from the pwa repo that was slacked out to the class. Comment out the debuggers in service worker.js and create a favicon icon that goes in the images folder. <br>Lastly create db.js inside the public folder and populate the db.js with the information provided by the teacher. Add the script to the html document, and your done!<i>
<hr>

## Licensing
<i>
MIT License

Copyright (c) [2020] [Austin Graphic and Web]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.<i>
<hr>