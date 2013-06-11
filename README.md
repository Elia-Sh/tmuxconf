tmux.conf
========


Use the tmux config file for the following features:
* bind ctrl+a instead of ctrl+b
* start window indexing at 1 instead of default 0
* scrollback buffer 10000 lines
* vi visual copy paste mode
* orange status bar
* additional key binding configuration

## Re-Attach Alias
use alias to reattach to running tmux sessions -
add the next line to `.bashrc`:

```alias atmux="tmux attach"```

## How to use
Copy ```tmux.conf``` file to home directory and rename the file to: ```.tmux.conf```

tmux automatically loads ```.tmux.conf``` on startup

to reload the conf file use ```ctrl + a``` (a is my prefix key) and then run: ```:source-file ~/.tmux.conf``` from the tmux command line (":" will focus on the command line)
