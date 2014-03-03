Vim Sheet
=========

Navigation
----------

- h: left
- j: down
- k: up
- l: right
- w: jump to the next word
- e: jump to the end of the current word
- b: jump to the last word 
- H: jump to the top of the document
- L: Goto the last line
- 3G: Goto the third line starting from the top of the document
- L: Goto the last line
- 3L: Goto the third line starting from the end of the document
- J: join the current line and the next line
- 3J: join the current line and the next two lines

Windows
-------

- :sp <Filename>: open <Filename> in new horizontal window
- :vs <Filename>: open <Filename> in new vertical window
- ctrl-w j: focus the next window
- ctrl-w k: focus the previous window
- ctrl-w ctrl-w: cycle through all windows
- :qa: close all windows at once

Spell Checking
--------------

- :local spell [spelllang=en_us]: enables spell checking for the optional language
- zg: add the word under the cursor to the dictionary

[Fugitive](https://github.com/tpope/vim-fugitive)
-------------------------------------------------

- :Gstatus: git status
- :Gwrite: git add %
- :Gremove: git rm %
- :Gread: git checkout %
- :Gcommit
