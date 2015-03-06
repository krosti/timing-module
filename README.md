timing-module
-------------------

CommonJS module which wraps Navigation Timing API. This module it's actually reusing
the [timing.js](https://github.com/addyosmani/timing.js/).


##How to install
```
$ npm install timing-module
```

##How to use
```javascript
var timing = require('timing-module');
```


---


##API

###getTimes()
Outputs extended measurements using Navigation Timing API.

  * @param  Object opts Options (simple (bool) - opts out of full data view)
  * @return Object  measurements

```javascript
timing.getTimes(); // [object Object]
```

###printTable()

Uses ```console.table()``` to print a complete table of timing information.

  * @param  Object opts Options (simple (bool) - opts out of full data view)

```javascript
timing.printTable();
```

###printSimpleTable()

Uses ```console.table()``` to print a summary table of timing information.

```javascript
timing.printSimpleTable();
```
