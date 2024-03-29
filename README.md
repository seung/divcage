Scribbler
=========
Currently Deployed at: http://scribblers.herokuapp.com/

This project utilizes the HTML5 [getUserMedia API] to manipulate the Canvas.

  - Currently the project is scoped to a single player game that will draw finger motion on a white board.
    - Version 0.6
  - There will potentially be a lobbying system that will delegate multi-player games in the next version.
    - Version 0.8
  - The game might get more complex [i.e. follow the leader or draw a specific image]
    - Version 1.0

Developers
-----------

####Seung Lim - [seung]
  - Worked on Algorithm for tracking pixel values on the screen & wrote tests using the Jasmine Framework

####Chad Reed - [chadreed-intl]
  - Worked on optimizing the tracking Algorithm with Seung and focused on the speed & usability of draw

####Tyson Daughtery - [gigmania]
  - Worked on intial wireframing/big picture & UI 

####Anthony Singhavong - [bigthyme]
  - Worked on the server, the Google Speech to Text API, and the final UI

####Philip Rosen - [philipjrosen]
  - Worked with the html5 canvas API and wrote code to integrate some of the UI features with the canvas functionality

Current Version
-
0.6.0 - Updating master README.md and prepping for soft release

Tech
-----------

This game uses a number of open source projects to work properly:


* [Twitter Bootstrap] - Great UI boilerplate for modern web apps
* [node.js] - Evented I/O for the backend
* [Express] - Fast node.js network app framework [@tjholowaychuk]
* [jQuery] - Dom manipulation
* [Google Web Speech] - Unreleased Speech to text api that is native to modern browsers

License
-----------

MIT
