
Hextris Reverse Engineered
==========
I am reviewing Hextris' code in order to understand the level mechanics and HTML5 game programming in general. I found that the first couple of minutes were too easy and I wanted the game to initialize at a higher level - which was my initial motivation for looking into the code. The conclusion I have come to so far is that the "level" is best set by modifying this.nextGen in the wavegen.js file. I prefer to set it at 2000. 



Here is Hextris' original Readme: 



Hextris
==========

Contributors:
 - Logan Engstrom (@lengstrom)
 - Garrett Finucane (@garrettdreyfus)
 - Noah Moroze (@nmoroze)
 - Michael Yang (@themichaelyang)

#Contributions
Please submit pull requests to clay-improvements

# Releases
#### iOS: https://itunes.apple.com/us/app/hextris/id903769553?mt=8
![](http://i.imgur.com/KBYZcf5.png)

#### Android: https://play.google.com/store/apps/details?id=com.hextris.hextris
![](http://i.imgur.com/mxj8yKs.png)

#### Firefox OS: https://marketplace.firefox.com/app/hextris-app
![](http://i.imgur.com/RhECXPg.png)

## Press kit

http://hextris.github.io/presskit/info.html

## License

This work is under a GPL v3 license.
