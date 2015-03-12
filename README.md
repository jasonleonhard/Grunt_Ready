# ExtendMe

![ExtendMe icon](http://img.ehowcdn.com/article-new-thumbnail/ehow/images/a06/he/0j/extend-netgear-network-800x800.jpg)

<pre>
A collection of several technologies I've been playing with all in one place. This project is not focused on one particular thing, theme or even effiency. It merely serves as a place to try several web dev concepts and see if they can combine nicely at times.
</pre>

## Usage

You can get started with:

```git fork https://github.com/un5t0ppab13/ExtendMe.git```

##Install node.js

___Mac___

Go to nodejs.org.
Click install, (to download the pkg).
Open the pkg and run through the install process.
That’s it! Check it worked with a simple Hello, World! example.


___Linux/GNU___ (Ubuntu)

On the latest version of Ubuntu, you can simply:
sudo apt-get install nodejs nodejs-dev npm
On earlier versions, you might need to update your repository:
	sudo apt-get install python-software-properties
	sudo add-apt-repository ppa:chris-lea/node.js
	sudo apt-get update
	sudo apt-get install nodejs nodejs-dev npm
Then, check it worked with a simple Hello, World! example.

___Windows___

Since Windows package managers are less common, we recommend just downloading the Windows binary.

Other Linux distributions

If you need help installing in other Linux distributions, you can consult Joyent guide for Mint, Elementary OS, Debian, LMDE, openSUSE, SLE, Fedora, RHEL/CentOS/Scientific Linux 6, Arch Linux and more.
Hello, Node.js

Here’s a quick program to make sure everything is up and running correctly.
// hello_node.js
var http = require('http');
http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Hello Node.js\n');
}).listen(8124, "127.0.0.1");
console.log('Server running at http://127.0.0.1:8124/');
Run the command by typing node hello_node.js in your terminal.
Now, if you navigate to http://127.0.0.1:8124/ in your browser, you should see the message.

Node was installed at
   /usr/local/bin/node

npm was installed at
   /usr/local/bin/npm

Make sure that /usr/local/bin is in your $PATH.

Congrats

You’ve installed node.js and npm.

***don't do this step unless you like issues***

	npm update -g npm
	sudo !!

## Install bower.io

	npm install -g bower
	sudo !!


## Install grunt.js and grunt command line interface
	npm install -g grunt grunt-cli
	sudo !!


## Now lets dance!

1. Change to the project's root directory.
2. Install project dependencies with: 
	npm install
	sudo !!
	bower install
	sudo !!
3. Run Grunt with 
	grunt
or 
	grunt serve
4. http://localhost:9000/
	

# still struggling?
make sure all node_modules are the same 

## License

All rights reserved
Copyright (C) 2014 Un5t0ppab13

[Check out my profile page page](http://github.com/un5t0ppab13).


# NEW SOLUTION
	rmr4r ExtendMe/
	git clone https://github.com/un5t0ppab13/ExtendMe.git
	cd ExtendMe/
	alias nomnom="rm -rf node_modules && npm cache clean && npm i"
	nomnom
	bower install
	grs
 