# clear-terminal
Just an easy bash script for clearing terminal outputs. Since clear command in terminal actually doesn't "clear" all the previous scrollable outputs, but instead do a lot of "printf"s, the one and for all method is to use a bash script to clear at the cost of one invocation call.
It clears the scrollback buffer as well as the screen.
### Usage: 
After cloning the repo, just put the bash script a known location. Then invoke the bash script in the following way:


` sh clear.sh`
