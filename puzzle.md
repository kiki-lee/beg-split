# Guess My Number
* name: Guess my Number
* description: Create a number guessing game using JavaScript
<!--* infoUrl: skillmap/educator-info/puzzle-map-info-->
* bannerUrl: /static/skillmap/puzzle/puzzle-activity-5.gif
* backgroundurl: /static/skillmap/backgrounds/puzzle-bg.png
* primarycolor: #2EA9B0
* secondarycolor: #F392BD
* tertiarycolor: #83C252
* highlightcolor: #FAED28



## guess-my-number
* name: Guess My Number
* layout: manual

### puzzle1
* allowcodecarryover: false
* name: Meet the Wizard
* type: tutorial
* description: Help your wizard choose a number
* url: /skillmap/puzzle/puzzle1
* imageUrl: /static/skillmap/puzzle/puzzle-activity-1.gif
* tags: text, puzzle, random
* next: puzzle2
* position: 0 2

### puzzle2
* name: The Big Reveal
* type: tutorial
* description: Reveal the chosen number at the end of the game to make it more satisfying.
* url: /skillmap/puzzle/puzzle2
* imageUrl: /static/skillmap/puzzle/puzzle-activity-2.gif
* tags: text, puzzle, random
* next: puzzle3
* position: 1 2

### puzzle3
* name: Try, Try Again
* type: tutorial
* description: Didn't guess the number instantly? Give your users another try.
* url: /skillmap/puzzle/puzzle3
* imageUrl: /static/skillmap/puzzle/puzzle-activity-3.gif
* tags: easy, events
* next: puzzle4
* position: 1 3

### puzzle4
* name: High / Low
* type: tutorial
* description: Let the player know if their guesses are high or low so they can narrow in on the correct answer. 
* url: /skillmap/puzzle/puzzle4
* imageUrl: /static/skillmap/puzzle/puzzle-activity-4.gif
* tags: easy, events, overlap
* next: puzzle5
* position: 2 3

### puzzle5
* name: Accept a Challenge
* type: tutorial
* description: Now that you have a game, add or change some features to make it your own!
* url: /skillmap/puzzle/puzzle5
* imageUrl: /static/skillmap/puzzle/puzzle-activity-5.gif
* tags: easy, events, overlap, lives
* next: puzzle-cert-1
* position: 2 2


### puzzle-cert-1
* name: Congrats!
* kind: completion
* type: certificate
* imageUrl: /static/skillmap/certificates/puzzle-cert.png
* url: /static/skillmap/certificates/puzzle-cert.pdf
* position: 4 1
* actions:
    * map: [Try 80s Rockstar Maze](/skillmap/rockstar)
    * map: [Try Space Explorer](/skillmap/space)
    * editor: [Edit Your Project with a Full Toolbox](/)
* rewards:
        * certificate:
            * url: /static/skillmap/certificates/puzzle-cert.pdf
            * preview: /static/skillmap/certificates/puzzle-cert.png
        * completion-badge:
            * image: /static/badges/badge-puzzle.png
            * name: puzzle Monkey