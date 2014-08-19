nrepl.js
========

javascript nrepl client

example usage:

```
nrepl = require(nrepl.js);
nrepl.connect(7889, function [err, client] {
  client.eval("(+ 2 3)", function [err, result] {
    console/log(result);
  });
});
```
