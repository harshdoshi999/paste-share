#About
NodeJS module to create/share pastes created on PasteShare and returns shortern URL!

# Installation

Install via NPM

```js

npm install paste-share --save

```

# Example

i. Create Paste

```js

var paste = require('paste-share');

var title = "What is Lorem Ipsum?";
var content = "Something about lorem ipsum...";
paste.create(title, content, function(err, url){
    console.log(url);
});

```

ii. Get Paste Content using Token ID

```js

var paste = require('paste-share');

var token = 'ee2855561f36181b247b02f399d76435be695d6a';
paste.get(token, function(err, res){
	console.log(res);
});

```

# Any issue or want more features? Contact me!

This module has been tested under limited scenarios. If you find any issue please feel free to report via one of the below platforms:

Github: <a href="https://github.com/harshdoshi999/paste-share/issues">nutrient-database</a> | 
Email: harshdoshi999@gmail.com | 
Skype: harshxxx3
