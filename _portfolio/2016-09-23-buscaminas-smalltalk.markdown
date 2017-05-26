---
layout:     post
title:      "Minesweeper in Smalltalk"
date:       2016-09-23
comments:   true
summary:    "Simple minesweeper game with Smalltalk (Pharo)"
image:      "minesweeper.png"
---

Minesweeper game was developed during [Object Technology course](https://sites.google.com/site/tecnologiadeobjetos2016/home). The game was made with Smalltalk (Pharo implementation, which was chosen for this course). I developed it over the image provided for the book ["Pharo by Example"](http://pharobyexample.org/image/PBE-OneClick-1.1.app.zip)

![Game GUI]({{ site.url }}/public/blog/2016-09-23/screenshot.png)

## Installation
In "Files" section you can find a link to a zip file, it contains a Pharo image with the Minesweeper package and some pictures used by the game.
Replace pharo.image and pharo.changes with the ones that are in the zip file, then copy and paste the picture files in the same path with pharo.image. Finally, start Pharo.

It's also available in a [SmalltalkHub repo](http://smalltalkhub.com/#!/~YulianaApaza/Yuliana-Minesweeper/){:target="\_blank"}.
For more info about Monticello versioning system and SmalltalkHub, you can read Chapter 7 of the book ["Deep into Pharo"](http://pharobooks.gforge.inria.fr/PharoByExampleTwo-Eng/latest/PBE2.pdf){:target="\_blank"}

## Documentation

Current documentation has class diagrams, sequence diagrams, and object diagrams. All classes are in Minesweeper package, which has 2 sub-categories: Minesweeper-core (Model) and Minesweeper-GUI (View).

In "Files" section you can find a link to the document in PDF (still in Spanish though).

## Files

- Pharo image with the game: [minesweeper-smalltalk-1.0.zip](https://github.com/yg-apaza/minesweeper-smalltalk/archive/v1.0.zip)
- Docs: [Report.pdf]({{ site.url }}/public/blog/2016-09-23/Informe.pdf){:target="\_blank"}
