## alexa-cookie 

Library to generate a cookie including a csrf for alexa remote

<!--
[![NPM version](http://img.shields.io/npm/v/alexa-remote.svg)](https://www.npmjs.com/package/alexa-remote)
[![Tests](http://img.shields.io/travis/soef/alexa-remote/master.svg)](https://travis-ci.org/soef/alexa-remote)
-->
[![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://github.com/soef/alexa-remote/blob/master/LICENSE)

####Example:
```javascript 1.8
let alexaCookie = require('alexa-cookie');

alexaCookie('amazon-email', 'password', function (err, result) {
    console.log('cookie: ' + result.cookie);
    console.log('csrf: '   + result.csrf);
});

````

####Info: 
Partly based on [Amazon Alexa Remote Control](http://blog.loetzimmer.de/2017/10/amazon-alexa-hort-auf-die-shell-echo.html) (PLAIN shell)<br>
Thank you for that work.