# postscript-procs
### PostScript Language Utilities

PostScript (PS) is not dead! It is an ‘underappreciated yet superb general purpose computing language’ – [_PS guru Don  Lancaster_](https://www.tinaja.com/post01.shtml) – and great fun!

PS, a page description language (PDL), was developed from the 1970's through to the 90's but has long been supplanted by PDF for most rendering tasks. You don't normally code in PS; it is usually program-generated. However PS is more than just a PDL, it is a complete programming language in its own right, using Reverse Polish Notation syntax: an interpreted, stack-based language similar to Forth, so very fast. PDF on the other hand, although based on PS, is not useful as a programming language.

Besides that, the need to drive a device programmatically crops up occasionally for which PS is preferred over PDF because of its language benefits. An example I had was implementing an EPS driver for a vinyl cutting machine in a sign lettering application. See also my [TTF to PS tool](https://github.com/scriptituk/ttf2pscid2) which uses PS to parse binary font files very efficiently.

The available PS operators, i.e. 'functions', are quite limited compared with mainstream languages, therefore utility procedures are helpful. For example there is no proc to concatenate two strings!

So this project offers general utilities for PS as a _language_ rather than just as a PDL.

The utilities here are organised in collections which should be obvious:

* `string.ps` – string procs, some quite unusual, including UTF and JSON tools
* `sort.ps` – Insertion, Shell and fast Quick sorting algorithms
* `math.ps` – some missing arithmetic functions
* `stat.ps` – statistical averaging and variance algorithms
* `file.ps` – basic filesystem functions
* `util.ps` – uncategorised utilities, including JPEG reading and image tiling

For more procs see Don Lancaster’s [PostScript Secrets](https://www.tinaja.com/glib/pssecrets.pdf) and [Gonzo Utilities](https://www.tinaja.com/post01.shtml#gonzo).
