Chrome-Vim-Bindings
===================

Overview
--------

Forked from the work done by [dbergey](https://github.com/dbergey/) on [Type-To-Navigate](https://github.com/dbergey/Type-To-Navigate/).

Use vim-style keybindings in Google Chrome. Might work in Safari -- I'm not sure and haven't tested yet. dbergey's "Type-To-Navigate" works well in Safari.

Usage
-----

Not in search mode:

- **/:** start search mode
- **backspace:** go back
- **j:** scroll down
- **k:** scroll up

In search mode:

- **[:alpha:]:** find matching elements on page. Start typing and the page will begin highlighting results
- **esc:** leave search mode
- **enter:** enter result mode

In result mode:

- **enter:** when on a link, follow the link
- **n:** go to next matching result
- **N:** go to previous matching result

Future Plans
------------

- regex support

License
-------

Licensed under a "do whatever" license. Reproduce, fork, whatever.

Type-To-Navigate is licensed under [the MIT license](http://creativecommons.org/licenses/MIT/).

Author
------
Chris Czub
derivative work from Type-To-Navigate by:
Daniel K. Bergey  
[http://twitter.com/dbergey](http://twitter.com/dbergey)
