## GA
https://docs.google.com/spreadsheets/d/1HgN0kh5VfhBy-iwlsA1O3u-sIQMTalBdrj89-dp5B9k/edit#gid=0

https://accounts.generalassemb.ly/identify

https://my.generalassemb.ly/

## JS tools

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators#assignment_operators


Array commands:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array

Event reference
https://developer.mozilla.org/en-US/docs/Web/Events
Arrow function:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions

https://www.geeksforgeeks.org/

## Hackerrank
https://www.hackerrank.com/domains/tutorials/10-days-of-javascript

## CSS
https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing

http://flexboxfroggy.com/ 

https://codepen.io/underwater/pen/GRjddVM

https://css-tricks.com/snippets/css/complete-guide-grid/

Automatic grid code generator
https://grid.layoutit.com/

https://developer.mozilla.org/en-US/docs/Web/HTML/Viewport_meta_tag

https://developer.mozilla.org/en-US/docs/Web/CSS/@keyframes

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations

https://developer.mozilla.org/en-US/docs/Web/CSS/:first-of-type

https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes

https://css-tricks.com/using-multi-step-animations-transitions/

Clock
https://morioh.com/p/f52aa1424e68

## Git
https://docs.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll

https://docs.github.com/en/github/managing-files-in-a-repository/moving-a-file-to-a-new-location

how to exit:
https://code.likeagirl.io/help-i-was-using-git-to-commit-some-code-and-now-the-window-has-changed-and-i-dont-know-what-s-9348a27e145b

## backend
Google public DNS
https://dns.google/


https://www.npmjs.com/

pgAdmin

https://sequelize.org/master/

MD5 Hash generator
https://www.md5hashgenerator.com/

https://git.generalassemb.ly/john-deere-sei-7/fruit-app/tree/class-progress

https://www.geeksforgeeks.org/commonly-asked-data-structure-interview-questions-set-1/

AVL tree visualization
https://www.cs.usfca.edu/~galles/visualization/AVLtree.html

TRIE visualization
https://www.cs.usfca.edu/~galles/visualization/Trie.html

## Python
https://docs.python.org/3/tutorial/datastructures.html#dictionaries

https://www.geeksforgeeks.org/shuffle-a-deck-of-card-with-oops-in-python/


## LG git hub
https://github.com/Grajales/card-game-of-war/tree/master/src/js

https://github.com/Grajales/grajales.github.io

https://grajales.github.io/

file:///Users/LG29878/sei/sandbox/css-basics/index.html

file:///Users/LG29878/sei/labs/html-css-card-element/lib/index.html

https://en.wikipedia.org/wiki/List_of_proverbial_phrases

https://www.iqair.com/dashboard/profile

Project 3 
https://github.com/PJTeel/unit3-birdapp/

https://three-acorns.herokuapp.com/

https://github.com/PJTeel/unit3-birdapp/projects/1

Project 4
https://github.com/Grajales/project4-frontend
https://github.com/nibingcheng/project4-backend/branches
https://docs.google.com/presentation/u/0/

https://git.generalassemb.ly/john-deere-sei-7/Unit_2_Commands

https://dashboard.heroku.com/apps/parque-aurora-frontend/deploy/github

https://aurora-park-backend.herokuapp.com/
https://parque-aurora-frontend.herokuapp.com/


In Bingcheng's site
https://dashboard.heroku.com/apps/aurora-park-backend

# Unit_2_Commands 
### Creating Express App
`npm init` -creates package.json file. Specify entry point to be `server.js`  
`npm install express`- installs Express  
`touch server.js` -creates server file so you can nodemon  
`npm install nodemon -g` -optional, you probably installed this globally already  
`touch .gitignore` -creates local gitignore file, off that bat add `node_modules`, `.env`  
create models, views, controllers folders
`npm install ejs` -installs EJS  
`npm install method-override --save` -installs method override which you'll need for your forms for PUT & DELETE

### Installing + Running Sequelize
`npm install sequelize-cli sequelize pg` -installs Sequelize  
`npx sequelize init` -instantiates Sequelize in your app. Creates config,models, migrations, seeders  
`npx sequelize model:generate --name NameOfYourModel --attributes column1Name:whatDataType,column2Name:whatDataType,etc.` -generates model and migrations, don't forget to update defaultValue  
`npx sequelize db:migrate` -runs migrations  
`npx sequelize seed:generate --name whatever-name-you-want` -creates new, empty seed file  
`npx sequelize db:seed:all` -runs all the seed files to populate data in your table(s)

### Sequelize workflow
If you've made changes to your DB and want to reset:  
`npx sequelize db:migrate:undo:all` undos all migrations  
`npx sequelize db:migrate` runs all migrations  
`npx sequelize db:seed:all` seeds your DB from scratch  


### Notes:
Remember when you run some type of npm install, you'll need to require the dependency at the top of your JS file (e.g. `require('express)` at top of server.js). Also, all these commands should all be run at the root level of your app directory. Be sure to set up your config.json file to be for your credentials and database name (the database can be created in pgAdmin, but create all your tables in the command line).


##### Repos with the above commands:

Express - https://git.generalassemb.ly/john-deere-sei-7/express-intro  
EJS - https://git.generalassemb.ly/john-deere-sei-7/MVC  
Delete/Update - https://git.generalassemb.ly/john-deere-sei-7/delete-express  
Sequelize- https://git.generalassemb.ly/john-deere-sei-7/sequelize-intro  







