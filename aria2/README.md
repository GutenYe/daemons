## Install

	$ mkdir -p ~/.config/aria2
	$ edit ~/.config/aria2/aria2.conf
	  dir=/home/USER/Downloads
	  rpc-secret=SECRET            # you can generate a secret by `date +%s | sha256sum | base64 | head -c 32 ; echo`
	$ touch ~/.config/aria2/session.lock
	# cp aria2.init /etc/init.d/aria2
	# insserv aria2

## Usage

	# service aria2 start
	# service aria2 stop
	# service aria2 restart
	# service aria2 status

## Configuration

Edit `~/.config/aria2/aria2.conf` and read `man(aria2c)` for references.
