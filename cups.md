# Pick-a-Cup
* name: Pick-a-Cup
* description: Create a simple carnival game where you shuffle three cups, then guess which cup is hiding the ball.
* infoUrl: skillmap/educator-info/cup-map-info
* bannerUrl: /static/skillmap/cups/cup3.gif
* backgroundurl: /static/skillmap/backgrounds/cup-comp.png
* primarycolor: #ffffff
* secondarycolor: #fff53d
* tertiarycolor: #e4cdc2
* completednodecolor: #a4839e
* highlightcolor: #ffff00
* allowcodecarryover: true
* tags: easy, beginner, tutorials


## pick-a-cup
* layout: manual


### cup1
* allowcodecarryover: false

* name: Welcome to the Show
* type: tutorial
* description: Make a simple clicker game talent show starring your favorite animals!
* tags: easy, clicker, points
* next: cup2
* url: /skillmap/star/star1
* imageUrl: /static/skillmap/star/star1.gif
* position: 0 0



### cup2
* name: Join the Audience
* type: tutorial
* description: Add an audience that applauds as you click!
* tags: easy, clicker, game, events
* next: cup3
* url: /skillmap/star/star2
* imageUrl: /static/skillmap/star/star2.gif
* position: 1 0


### cup3
* name: The Biggest Star
* type: tutorial
* description: Add code to create a spray of stars with each click!
* tags: easy, clicker, projectiles
* next: cup-cert
* url: /skillmap/star/star3
* imageUrl: /static/skillmap/star/star3.gif
* position: 1 1




### cup-cert
* name: Congrats!
* kind: completion
* type: certificate
* url: /static/skillmap/certificates/star-cert.pdf
* imageUrl: /static/skillmap/certificates/star-cert.png
* position: 3 1
* actions:
    * map: [Try Space Explorer](/skillmap/space)
    * editor: [Edit Your Project with a Full Toolbox](/)
* rewards:
    * certificate:
        * url: /static/skillmap/certificates/star-cert.pdf
        * preview: /static/skillmap/certificates/star-cert.png
    * completion-badge:
        * image: /static/badges/badge-star.png
        * name: Star of the Stage



