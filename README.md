# postscript-procs
PostScript utility procedures

PostScript (PS), a page description language (PDL), was developed from the 1970's through to the 90's but has long been supplanted as a PDL, mainly by PDF. You don't normally code in PS; it is usually program-generated. However PS is more than just a PDL, it is a complete programming language in its own right, using Reverse Polish Notation syntax. It is an interpreted, stack-based language similar to Forth, so is very fast. PDF is based on PS but as a programming language is much simplified.

The need to drive a device programmatically crops up occasionally for which PS is preferred over PDF because of its language benefits. An example I had was implementing a driver for a vinyl cutting machine in a sign lettering application. However the available PS operators, or 'functions', are quite limited compared with mainstream languages, therefore utility procedures are helpful. For example there is no proc to concatenate two strings!

The utility procedures here are organised in collections which should be obvious. For more procs see Don Lancaster’s book PostScript Secrets.
