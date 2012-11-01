#The Isogenic Game Engine - Prototype Version

This repository contains the latest build of the Isogenic Game Engine (IGE) prototype version 1.1.0. The prototype version is free to use and is made available for you to be able to evaluate the IGE before you decide to purchase a license.

## Examples

It also contains the various examples that are included with the full version of the IGE and each example includes a "deploy" folder where you can run a compiled version of the example. "Compiled" is not meant in the strict computer programming sense since you cannot compile JavaScript but in the more general sense in that the full IGE includes a handy script that scans your project, determines all the dependencies and then packages up all your game code and engine code that you used into one single game.js file.

The deployment packager also removes any server-side code from the source automatically so when writing multiplayer / networked games none of your server-side code is visible to the client even if they do a view-source on the game.js file.

## FYI
The prototype version of the engine is built from many (but not all) of the classes that the full version contains. Notable exceptions are some of the 3d physics and all networking classes. Since the engine has been packaged into a single file (./engine/core/ige.js) it contains many classes that you might not use in your game. The ige.js file weighs in at just over 400kb but if you check some of the examples in their deploy/game.js file you can see that when packaged the engine can be reduced quite a lot... to under 100kb in a lot of cases.

This makes the prototype version great for development and testing but less awesome for production deployment. If you are going to deploy your game for production use please purchase a license so that you can properly package your game and it's dependencies.

## License

You may use the IGE prototype for non-commercial, educational or hobbyist purposes only. If you wish to create a game that utilises the IGE and generates income from any source connected to the game via online means (this includes in-game purchases, banner adverts in the game or on the page the game runs on, bank transfers that were originated offline but were meant for in-game purchases etc) then you need to purchase a license for the engine. Examples of income that is not counted as requiring a license are t-shirts featuring the game or game art, accessories or other real-world items that are not part of the "digital" game etc. You can purchase a license from our website listed below.

## Questions? Issues? Bugs?
If you have any comments, questions, requests, issues or bug reports please use the GitHub issue tracker for this repository: https://github.com/coolbloke1324/ige_prototype/issues

## Phone Home
The Isogenic Game Engine website can be found here: http://www.isogenicengine.com

