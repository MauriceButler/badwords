# badwords

A highly consumable list of bad (profanity) English words based on the nice short and simple list found in [Google's "what do you love" project](http://www.wdyl.com/) made accessible by [Jamie Wilkinson](https://gist.github.com/jamiew) [here](https://gist.github.com/jamiew/1112488)


This data has been exposed as
- an array
- an object
- a regular expression

depending on what is required for your purposes.


# Install

    npm install badwords

# Usage

``` javascript
var badwordsArray = require('badwords/array');

var badwordsObject = require('badwords/object');

var badwordsRegExp = require('badwords/regexp');
```

#### Note

"Bad words" implementations are frequently prone to the [Scunthorpe problem](https://en.wikipedia.org/wiki/Scunthorpe_problem)

These kind of lists can be used for flagging things, but being used as a basis for outright blocking can cause issues.