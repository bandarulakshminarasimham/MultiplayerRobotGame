# RobotDirection_V3
Multiplayer HTML5 video game using NodeJS

This is a HTML5 and NodeJS Multiplayer Robot game, which can MOVE, TURN on a square table surface(100X100).

Set Up
	* Clone the repository git clone https://github.com/bandarulakshminarasimham/RobotDirection_V3.git and change directory to its root folder
	* Install Node.js (includes NPM)
	* Install Mocha JS testing framework
		npm install mocha –g
	* Install dependencies in package.json, including Chai assertions
		npm install

Testing
	* npm test

Run Local Web Server
	* Start the development server with auto re-bundling using npm start and opening in a web browser http://localhost:2000

Tech Stack

	* Client-side
		o Html5
	* Server-side
		o Node.js v7+, NPM v3.10.8
		o Express (web server)
	* Mocha testing framework
	* Chai BDD

Description
	The application is a simulation of a toy robot moving on a square tabletop, of dimensions 100 units x 100 units. There are no other obstructions on the table surface.
	The robot is free to roam around the surface of the table, but must be prevented from falling to destruction. Any movement that would result in the robot falling from the table must be prevented

How to play the game

	Step 1: Browse the URL (http://localhost:2000) and enter Nickname then select “start” to play game.
		Nickname entry screen cap: https://github.com/bandarulakshminarasimham/RobotDirection_V3/blob/master/images/Nickname_screencap.PNG
		Game surface screen cap: https://github.com/bandarulakshminarasimham/RobotDirection_V3/images/GameSurface.png
	
	Step 2:  A player can see all the users who entered the game and their commands. 
		Commands: Press below keys on keyboard to play
			L/l to turn LEFT (90 degree)
			R/r to turn RIGHT (90 degree)
			D/d to reverse the direction (180 degree)			
			M/m to move by 1 position, hold the key to move faster




