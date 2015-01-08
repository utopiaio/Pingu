# Pingu-Noot
a simple package that pings a given ip address a returns the result in a cool JSON format

## Installation
```shell
$ npm install pingu-noot
```

#usage
```JavaScript
var pinguNoot = require('pingu-noot');

pinguNoot({c: 2, timeout: 1000}, '8.8.8.8', function (stat) {
  console.log(stat);
});
```
