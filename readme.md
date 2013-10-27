Javascript Tower Platformer
===========================

An HTML5 rotating-tower platform game inspired by the old c64 game "Nebulus"

 * [play the game](http://codeincomplete.com/projects/tower-platformer/index.html)
 * [read more](http://codeincomplete.com/posts/2013/10/27/rotating_tower_platformer/)
 * [view the source](https://github.com/jakesgordon/javascript-tower-platformer)

SUPPORTED BROWSERS
==================

Should work in any modern browser with canvas support

DEVELOPMENT
===========

The game is 100% client side javascript, html and css. It should run when served up by any web server.

FUTURE FEATURES
===============

 * level exit
 * game menu
 * multiple levels
 * dissolving platforms
 * elevators
 * shortcut doors
 * countdown timer
 * mobile touch support
 * sound fx and music

TECH DEBT
=========

 * should use an FSM to manage player state (standing/left/right/falling/climbing/hurt/etc)
 * allow monsters to overlap (make cell.monster an array instead of single object)
 * use images for tower gradient and platforms (instead of raw ctx stroke/fill calls)
 * direction-agnostic monster sprites (abstract)
 * tiny gap in ground rendering in FF/IE where image wraps (need to render image on (0.5, 0.5) boundaries)

License
=======

[MIT](http://en.wikipedia.org/wiki/MIT_License) license.

