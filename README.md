# track-creator

See in it action [here](http://townsean.github.io/track-creator/)! (Work in Progress)

## Synopsis

The track creator is an Aurelia web app that gives users the ability to create custom PitchCar tracks online. Users can create tracks and share exported photos of their tracks with others.

## Motivation

PitchCar is a finger flicking, dexterity racing game for 2 - 8 players. The race track consists of variety of pieces that fit together like a puzzle. Several months ago I introduced PitchCar to my coworkers. The game was a hit among them. In one discussion someone asked if there was an online track generator. I looked into it and learned there was a Windows desktop track generator. However, the desktop application had no new updates in the past 7 years.   

I have decided to take on the challenge of creating a online track creator.  I figured this would be a great learning experience and I have grown rusty in writing software for fun after work hours.

## Install

```
npm install
```

```
jspm install
```

```
npm start
```

## Design Notes

Some design notes:
* [interact.js](interactjs.io) library for drag, drop and snap 
* [Green Sock Draggable](https://greensock.com/draggable?sub-product=draggable) - an alternative to interact.js
* [Font style](https://fonts.google.com/specimen/Faster+One?selection.family=Faster+One) for Track Creator

Features:
* build digital tracks 
* drag drop track pieces to build one track
* track pieces should snap together
* export track to image
* sort tracks by expansion. Have the following tabs: All, Extension 1, Extension 2, Long Straights, The Cross, Stunt Race
* double tap / click to show or hide track rails

## Maintainers

* [Ashley Grenon - @townsean](https://github.com/townsean)

## License (MIT)

The MIT License (MIT)
Copyright (c) 2017 Ashley Grenon

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
