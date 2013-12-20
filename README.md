Postman
=======
Postman helps you be more efficient while working with APIs. Postman is a scratch-your-own-itch project. The need for it arose while one of the developers was creating an API for his project. After looking around for a number of tools, nothing felt just right. The primary features added were a history of sent requests and collections.
A number of other features have been added since the initial release. A small list is below. To see a fancier page and a video tutorial, check out http://www.getpostman.com

Swagger Starter
=======
This version of Swagger is intended to offer you a feature to create all of your collections based on a Swagger metadata URL, the same one used by Swagger-UI to build the UI. That way, you can use all the amazing tools and features below with POSTMan.

- One Collection Per Service as the main swagger.json output
- All the requests for each of the services in the collection
- Create different environments based on the URL matches (2 different hosts with the same swagger.json - QA, DEV, etc)

Features
========

Create requests quickly.

- Compact layout
- HTTP requests with file upload support
- Formatted API responses for JSON and XML
- HATEOAS support
- Image previews
- Request history
- Basic Auth and OAuth 1.0 helpers
- Autocomplete for URL and header values
- Key/value editors for adding parameters or header values. Works for URL parameters too.
- Use environment variables to easily shift between settings. Great for testing production, staging or local setups.
- Keyboard shortcuts to maximize your productivity

Document and share APIs.

- Use collections to organize requests.
- Document requests inside collections. You can even store entire HTML notes. Postman uses Bootstrap so you can use it too to style your notes.
- Download and share collections with your team of developers.

For more details checkout the Postman wiki - https://github.com/a85/POSTMan-Chrome-Extension/wiki.

Postman for Chrome can be downloaded from https://chrome.google.com/webstore/detail/fdmmgilgnpjigdojojpjoooidkmcomcm

Postman for Google Chrome is licensed under the Apache Licence, Version 2.0 (http://www.apache.org/licenses/LICENSE-2.0.html).

Installing the zip file
=========================

If you downloaded the Postman zip file here is what you need to do to install it as a developer extension:

1. Go to Tools > Extensions inside Chrome by clicking on the wrench icon on top right.
2. Select "Load unpacked extension"
3. Select the "chrome" folder with manifest.json in it's root
4. Postman will be installed as a developer extension. The installation from the Chrome Web Store will remain independent with all your data.

Building and Developing
=========================
1. Install the dependencies
<pre>
sudo npm install -g grunt grunt-cli
</pre>
2. Generate the template.js and request.js files by running grunt. You can watch the folder for changes using:
<pre>
	grunt watch
</pre>
3. For misc. grunt tasks, look at grunt.js.

Submitting bugs
===============

Please add the Postman version along with your operating system and Chrome version along with bug requests. 


Pull requests
=========================

Please send pull requests to the dev branch. The master branch contains the latest code which has been put in production.
