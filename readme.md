Jtime
=====

Your time tracking companion for Jira.

Installation
------------

1. To install and run this project, you will need `bower` and `gulp` installed

    npm install -g bower
    npm install -g gulp

2. Install dependencies

    npm install
    bower install

3. copy file `config.sample.js` to `config.js` and edit values
4. 
    - For dev just run
  
        gulp

    - To run in production mode
    
        gulp build
        npm start
        
5. Open your browser and go to http://localhost:3000/projects/JIRA_PROJECT_KEY/2015-01