qcd
===

A Bash utility that enables quick `cd`s using shortcuts.


## Example

	$ cd code/qcd
	
	# Add a shortcut `qcd` for the current directory
	$ qcd -a qcd .
	
	$ cd ~/Desktop/
	$ qcd qcd
	$ pwd
	/Users/professorfarnsworth/code/qcd
	
	$ qcd -a another-project ../another-project-dir/
	$ qcd another-project
	$ pwd
	/Users/professorfarnsworth/code/another-project-dir
	$ qcd qcd
	$ pwd
	/Users/professorfarnsworth/code/qcd
	
	# Remove the `another-project` shortcut
	$ qcd -r another-project


## Install
Mac OS X users can install `qcd` with Homebrew:

	$ brew install https://raw.githubusercontent.com/teddywing/qcd/master/Homebrew/qcd.rb

On other platforms, grab the code and add the following lines to your Bash profile:

	source ~/path/to/qcd
	source ~/path/to/qcd.bash-completion


## License
Copyright © 2016 Teddy Wing. Licensed under the GNU GPLv3+ (see the included COPYING file).
