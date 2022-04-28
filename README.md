# music_collection

ABOUT

A tool build with the use of API for Spotify to display a list of a users saved albums in the form of cover picture, title, artists, release-year and list of tracks.


HOW TO RUN

1. run the following command (skip this step if nvm is already installed)

	curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash

2. restart the terminal
3. run the command (skip this step if node is already installed)

	nvm install node

4. go to the authorization_code directory

	cd authorization_code

5. run the following in the terminal

	node app.js

6. go to the following webpage on the desired browser (ex. chrome)

	http://localhost:8888


You should now be able to log into your spotify account and see a list of all of your saved albums -!

If you wish to save the list in pdf form for later use do the following steps

1. open chrome
2. go to the following webpage: http://localhost:8888
3. click the 3 dots in the upper right hand corner, and select 'Print...'
4. make sure 'Destination' is set to 'Save as PDF' and press 'Save'

You should now have a saved file on your computer with a list of your spotify albums!
