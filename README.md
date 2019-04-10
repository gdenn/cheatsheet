# Cheatsheet

Here are some commands and hotkeys that i use on a daily basis for the following tools / apps:
* Tmux - session management in a single terminal window like a boss
* Vim - most infamous and hackable terminal text based editor

## Glossary

Following some explanations if you are not familiar with the hotkey notation

* __C - b__ - hold the CTRL and b key at the same time
* __C - b %__ - hold CTRL and b key at the same time, then press % (SHIFT and 5)

## Tmux

__Note__: Hotkeys on MacOs might differ!

| hotkey/command | description |
| ---- | ---- |
| C - b c | new window |
| C - b n | switch to new next window |
| C - b p | switch to previous window |
| C - b <number> | switch to window by number |
| C - b “ | horizontal split pane |
| C - b % | vertical split pane |
| C - b z | fullscreen on current pane |
| C - b C <arrow key> | resize pane into arrow key direction |
| C - b d | deattach from session |
| C - b D |choose which session to detach |
| C - b <arrow key> | navigate split panes |
| tmux ls | list all sessions |
| tmux attach -t <number> | attach to session by number |

## Vim

__Note__: all commands starting with `:` as well as the hotkeys
needs to run in cmd mode (type ESC) and not insert mode!

It is in generally a good practice to always switch to cmd mode after you 
finished editing/inserting a word. Make it a natural behaviour to press ESC at 
the end and you will never have to ask yourself if you are currently in insert or
cmd mode.

My vimrc is based on a fork of [amix/vimrc](https://github.com/amix/vimrc), as 
theme i use currently [gruvbox](https://github.com/morhetz/gruvbox).

| hotkey/command | description |
| ---- | ---- |
| :e <file> | open new buffer with file |
| :q | exit |
| :q! | exit no save |
| :wq | exit and save |
| :ls | list buffers |
| :b <number> | jump to buffer with number |
| :vsp <file> | vertical split to file |
| :sp <file> | horizontal split to file |
| :/<word> | search for word |
| :?<word> | forward search |
| :! <cmd> | run shell command |
| :%s/foo/bar/g | replace foo by bar in the whole file |
| :s/foo/bar/g | replace foo by bar in marked block |
| :r <file> | insert file content into current file |
| C - o | last buffer |
| C - n | next buffer |
| x | delete character |
| A | append at the end of the line |
| a | append at next character |
| 0 | to the line beginning |
| u | undo |
| C - R | redo |
| xp | switch to characters |
| . | repeat last command |
| e | move to the end of the word |
| o | open line under cursor and switch to insert mode | 
| dw | delete word |
| ce | change until end of word |
| dd | delete line |
| yy | copy line |
| > | indent block |
| yw | copy one word |
| p | paste |
| v | enter visual block |
| gg | move to start of file |
| GG | move to end of file |

## Suggestions?

I am always searching for new cmds and hotkeys that can improve my workflow. If you got
something that could be an asset drop me an issue or open a PR in this repo.
