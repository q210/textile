Since I couldn't find a good Textile parser for Node.js, I repurposed this one.

Very little input was provided by me, all the hard work was done by Christian P. @ https://github.com/christianp/jstextile

I have forked it, add the package.json, and made sure it still worked in browser and in Node.

### Usage:

	textiled.parse(inputString [, options]);

As for options, this is the only usage of options I could find:

### Options:

	{
		nowrapPlainBlocks: true; // Not exactly sure what it does, but its the only option.
	}


Original Readme by Christian Perfect:

	A better javascript textile converter, because I couldn't find one.
