Simply Log
====================
![Simply Log Dependency badge](https://david-dm.org/anonmily/simply-log.svg)

An expressive type testing utility library.

[GITHUB:	https://github.com/anonmily/simply-log](https://github.com/anonmily/simply-log)

[NPM:		https://www.npmjs.com/package/simply-log](https://www.npmjs.com/package/simply-log)

## Installation - Node
To install as a Node package, simply install via npm:

    npm install simply-log

Then, you can require and start using the package as you wish:

	var log = require('simply-log');
	log.info('this is an informational message');	// grey
	log.warning('I'm warning you');					// yellow
	log.error('Something went horribly wrong');		// red

## Usage

Logging depends on two environmental variables, SHOW_DEBUG and SHOW_ERRORS

| Version | Notes                                                                                                                                                                            |
|---------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Info   | Informational, grey. Visible when SHOW_DEBUG=true |
| Warning  | Warning, yellow. Visible when SHOW_DEBUG=true  |
| Success | Success, green. Visible when SHOW_DEBUG=true	|
| Error  | Error, red. Visible when SHOW_DEBUG=true and SHOW_ERRORS=true  |