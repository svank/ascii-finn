# ASCII FInn

### Enabling superior research everywhere

This includes seven script files:

+ `finn`, which will print a random ASCII image of Finn
	+ Include the name of an ASCII image on the command line to print that one specifically
+ `finnsay`, `finnthink`, and `finnshout`, which will print Finn with a custom message in a speech bubble
	+ Usage: `finnshout SyntaxError on line 22!`
	+ These three require `cowsay` to be installed on your system (`sudo apt install cowsay` in Ubuntu)
+ `wrap_say`, `wrap_think`, and `wrap_shout`, which allow you to run another command and pass the output to finnsay/think/shout
	+ Usage: `wrap_shout ls /usr/`
	+ To make it easier, use `alias "ls=wrap_say ls"` to include Finn in your normal activities.
	+ Since these use finnsay/think/shout, they also require `cowsay` to be installed.

To enable these scripts, I recommend either including this repository's directory in your PATH, or symlinking the executables to a directory in your path (e.g. ~/bin).

