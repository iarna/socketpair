socketpair
==========

Creates a pair of socket-like streams that read and write to each other

```javascript

var socketpair = require('socketpair');

stdin.pipe(socketpair[0]);
socketpair[1].pipe(stdout);
```
