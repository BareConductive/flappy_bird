[![Bare Conductive](http://bareconductive.com/assets/images/LOGO_256x106.png)](http://www.bareconductive.com/)

# Bare Conductive "Flappy Bird" Game

Proximity-based game that uses the [Bare Conductive Touch Board](http://www.bareconductive.com/shop/touch-board/) and the [Adafruit NeoPixel Shield](https://www.adafruit.com/product/1430) and is based on the concept of the popular game "Flappy Bird". The game set-up is similar to our other game ["Hole in the Wall"](https://github.com/BareConductive/hole_in_the_wall).

In order to use the NeoPixel shield and play sounds simultaneously, the connection between the digital pin D6 and Din on the NeoPixel shield needs to be interrupted by cutting a trace. The NeoPixel Din pin then needs to be connected to pin 11 on the Touch Board. 

Three MP3 files (named TRACK000.mp3, TRACK001.mp3 and TRACK002.mp3) are used to add sound effects to the game. You can download these MP3 files [here](http://www.bareconductive.com/assets/resources/hole_in_the_wall_audio.zip). 

The electrodes on the Touch Board have following functions:

* E0 - Start or reset the game
* E2 - Increase volume (if audio is enabled)
* E3 - Decrease volume (if audio is enabled)
* E5 - Increase brightness
* E6 - Decrease brightness
* E11 - Move bird up an down

As this game is based on proximity the size of your sensor influences the game mechanics. Have a read [here](https://www.bareconductive.com/make/sensor-design-basic-rules-of-thumb/) to find out how to create the best sensors with our [Electrical Paint](https://www.bareconductive.com/shop/electric-paint-50ml/). 

## Requirements
* You should make sure that you have followed our [Setting up Arduino with your Touch Board](http://www.bareconductive.com/make/setting-up-arduino-with-your-touch-board/) tutorial before using this (or any other) of our code examples


## Install
1. Close the Arduino IDE if you have it open.
1. Download the [.zip](https://github.com/BareConductive/flappy_bird/archive/public.zip) or clone the repository to your local machine - if downloading the .zip, extract the contents somewhere that suits you.
1. Take the **flappy_bird** folder and move it to **Arduino Sketchbook Folder**. This will be different for each operating system: 

	**Windows**
	
	Libraries\\Documents\\Arduino
	
	or
	
	My Documents\\Arduino	
	
	**Mac**
	
	Documents/Arduino
	
	**Linux (Ubuntu)**
	
	Home/Arduino


	If this folder does not exist, create it first.
1. Reopen the Arduino IDE - you should now be able to open the sketch in the **File -> Sketchbook** menu.