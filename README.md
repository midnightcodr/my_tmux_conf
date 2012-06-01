##About
	My tmux config based on http://blog.hawkhost.com/2010/07/02/tmux-%E2%80%93-the-terminal-multiplexer-part-2/, tested in Mac OSX Lion.

##Deployment guide
	back up your existing ~/.tmux.conf if it already exists
	cd ~
	curl -O https://raw.github.com/midnightcodr/my_tmux_conf/master/.tmux.conf
	start a new tmux session and detach from it, if there's no tmux session running
	tmux source-file ~/.tmux.conf
	tmux att 
