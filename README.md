# HSTA
Developed for CS 506 at The University of Wisconsin-Madison

There are three separate distinct repos containing the project.

https://github.com/chesslooter/hsta-web
This repo contains all of the source code for the web client of our application. You can view the site at chesslooter.github.io/hsta-web, and test it from there.

https://github.com/chesslooter/hsta-desktop
This repo contains our desktop client. Follow the instructions related to using the app yourself in order to test this portion.

https://github.com/jcordell/hsta-server
This repo contains all of the code for our server back-end, which is deployed using Heroku.
Testing:
  Pull down the master branch. Ensure that node is installed. Ensure that my-sql is installed (https://dev.mysql.com/downloads/), and connects to User root. Password is Badgers1!. In a terminal in the root directory, execute the command "npm install". After the modules install, run the command "npm test". This will run through the suite of tests we have prepared.


In order to use our app yourself:

Download our client from (https://github.com/chesslooter/hsta-desktop) (Iter2 Desktop branch, commit 3e29a0aff88cba49664e484ae24f15a2a5bcb7a6 ) 

Install node (npm comes with) 

Install Hearthstone (via battle.net)

Install Hearthstone Deck Tracker (https://hsdecktracker.net/) 

Ensure your Hearthstone account is eligible to play against other players. 

In Hearthstone, create a deck you wish to use. 

Using a terminal, in /hsta-desktop/desktop/HSDesktopClient/, use the command npm install, followed by npm run electron-build
Also run npm install in /hsta-desktop/desktop/LogHandler/

Once running, note that our server can take 30-45 seconds to start after hitting “Login” if it has not been used recently.

Right click your deck and select the option to generate a deck link. (https://www.youtube.com/watch?v=kmXPpJosR7E decklist copying example)

Log in to our app. 

Using the add deck feature, copy the link to your deck provided in game to add a deck to your account. 

Using that deck, queue up for a game and press the start validation button. 

Enjoy losing to somebody who knows how to play the game. Or just concede, clicking the gear in the lower right hand corner to bring up the menu. 
