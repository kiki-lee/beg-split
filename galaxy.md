# Create a Space Adventure
* name: Create a Space Adventure Game
* description: Make a Galaga-style game by following this short series of tutorials. You will create a rocket that fires projectiles at enemies, design your outerspace view, create amazing animations, and MORE!  What are you waiting for?  Double-click the first level to begin!
* infoUrl: skillmap/educator-info/space-map-info
* bannerUrl: /static/skillmap/space/spacet6.gif
* backgroundurl: /static/skillmap/backgrounds/space-comp.png
* primarycolor: #2EA9B0
* secondarycolor: #d6f7fa
* tertiarycolor: #5d416b
* highlightcolor: #FFFFFF
* completednodecolor: #504c52
* tags: intermediate, space, projectiles
* alternatesources: github:https://github.com/microsoft/pxt-skillmap-sample/skillmap.md


## space
* name: Design a Space Explorer
* layout: manual

### space-activity1
* name: Prepare Your Ship
* type: tutorial
* description: Get your spaceship ready for an adventure!
* tags: easy, sprites, scroller
* next: space-activity2
* url: /test/skillmap/space/space1
* imageUrl: /static/skillmap/space/spacet1.gif
* position: 0 0

### space-activity2
* name: Ready, Aim, Fire!
* type: tutorial
* description: Equip your ship with projectiles and special effects.
* tags: easy, projectiles, kinds
* next: space-activity3
* url: /test/skillmap/space/space2
* imageUrl: /static/skillmap/space/spacet2.gif
* position: 0 1

### space-activity3
* name: Here Comes Trouble!
* description: Watch out for danger! Add enemies and countdown lives in your game.
* type: tutorial
* tags: intermediate, enemies, kinds
* next: space-activity4a
* url: /test/skillmap/space/space3
* imageUrl: /static/skillmap/space/spacet3.gif
* position: 3 1

### space-activity4a
* name: All Shook Up
* type: tutorial
* description: Animate your ship
* tags: intermediate, animations
* next: space-cert-1
* url: /test/skillmap/space/space4a
* imageUrl: /static/skillmap/space/spacet4a.gif
* position: 3 0




### space-cert-1
* name: Congrats!
* kind: completion
* type: certificate
* imageUrl: /static/skillmap/certificates/space-cert.png
* url: /static/skillmap/certificates/space-cert.pdf
* position: 5 0
* actions:
    * map: [Try 80s Rockstar Maze](/skillmap/rockstar)
    * map: [Try Jungle Jump](/skillmap/jungle)
    * editor: [Mod This Project](/)
* rewards:
    * certificate:
        * url: /static/skillmap/certificates/space-cert.pdf
        * preview:  /static/skillmap/certificates/space-cert.png
    * completion-badge:
        * image: /static/badges/badge-space.png
        * name: Space Explorer