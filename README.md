# `makolor` - compiler messages in color!
Colorizes compiler output from `make` to increase visibility of compiler warnings and other messages among large amounts of text

Initial 'fork' from [this stackoverflow post](https://stackoverflow.com/a/14923025/8112846) by [Reza Toghraee](https://stackoverflow.com/users/975403/reza-toghraee)

You've probably had this problem before: You have a `C` program with `#warning` messages that you have to compile a bunch of times and the warnings end up near the very top of 100+ lines of output, or worse yet, somewhere in the middle. You still want to see everything else, or just don't feel like piping it through `grep` umpteen times. Well `makolor` is definitely one out of a multitude of possible solutions! (Doesn't sound very convincing, I know)

Alternately, you want builders of your software to clealy see errors and warnings at compile time. `makolor` can be helpful here as well.

Advanced programmers can stop reading here. Really advanced programmers didn't need to read any of this at all. Yet more advanced programmers could have written this themselves. The most advanced programmers either already did, or have some other solution, or are just being lazy and want to leech off of this repo. WHAT ARE YOU DOING HERE? ( ͡° ͜ʖ ͡°)

## Installation Instructions
### Prerequisites
All that is required, aside from your favorite compiler, is `bash`, `pearl`, and `make`.

Clone or download a ZIP of this here repository, make sure `makolor` is executable and alias `make` to it. Just issue `alias make=/path/to/makolor`. You can also copy `makolor` somewhere into your system path and just run `makolor` instead of `make`. If you aren't sure where that is, issue `echo $PATH` into a terminal. To install systemwide, `/usr/local/sbin` is usually a good place. Drop it into `~/bin` or `~/sbin` if there are other users on the system and for some reason you don't want them using it.

### Distribution with source code or somewhere else
The `makolor` script can be run from prettymuch anywhere and it's fine by me if you want to include it along with a software package. I do not care. Let me know if it helps you.
