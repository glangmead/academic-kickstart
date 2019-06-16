---
author: admin
date: 2002-03-04 02:03:06+00:00
draft: false
title: I'm going to get started
type: post
categories:
- Tech
---

I'm going to get started today on a new piece of software. It will be a multipurpose "Paint by Numbers" application. Paint by Numbers is a puzzle game (I am not yet sure whether this name is a trademark or not) where you are presented with a blank rectangular grid of squares, usually about 20x20 or larger (the bigger it is, the harder it is). The goal is to reproduce the picture by deducing which squares should be colored. The clues are lists of numbers, one list for each row and one list for each column. Each number in the list is the tally for a consecutive run of colored squares. Visit [this Japanese site](http://www02.so-net.ne.jp/~kajitani/cgi-bin/pbn.cgi/index.html) for some examples to try.

I'm going to write the app in Cocoa, the native environment for Mac OS X. In fact, this is just my excuse to learn Cocoa. When Apple computer bought Steve Jobs' company Next in 1995 (?), they did so to obtain the sophisticated Nextstep operating system. This became Mac OS X, and the then-revolutionary Nextstep programming framework became Cocoa. Tim Berners-Lee, the creator of HTML, HTTP, and the first web browser, wrote all of it using Nextstep. Why? Because it was easy, supposedly. I've explored it a little bit and I find it very exciting. It is easy in the sense that many things come for free, as in Java, but it is also hard in that it leaves me running to the documentation all the time -- once I commit the core of Cocoa to memory, this will disappear as well and it probably _will_ seem easy.

I'll write the engine in C++, though, not Objective-C (the language you have to use to use Cocoa). The engine will include the abstraction of what a Paint-by-Numbers puzzle is, and the things the player can do to it. Actually wiring that up to a user of the app will be another layer, the user interface layer. This layer will listen to mouse clicks and whatnot, and will then call the appropriate message in the engine. 

For example, the most common way to interact with the puzzle will be to click on a square cell. When the click is heard, I will have to compute which square on the screen it was in, and therefore which abstract cell it is. Then, I will ask the abstract "paint by numbers cell object," which is invisible to the user, to alter its state (turn it black, for example). Then, I'll have the representation of the cell on the screen update accordingly, by asking the abstract cell what color it is now. 

I'm still working out the architecture, but I should have some progress by day's end.  I have some _[Economist](http://www.economist.com)_ magazine reading to do too.
