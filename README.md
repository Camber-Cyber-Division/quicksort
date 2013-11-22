quicksort
=========

Instructions
------------

1. If you do not already have a github account, create one.
2. Fork this project.
3. Update the LICENSE file with whatever license you prefer.
4. Add a copyright, license, and warranty notice at the top of each source file
   you create.
 * If you use the LICENSE file included, the information you need to include at
   the top of each source file can be found in the *License* section of this
   README. Just change __your-name-here__ to your full name.
5. Add a simple echo program written in C to the project that takes a binary
   stream of unsigned integers as input and prints them to standard out. The
   program should compile with GCC on a x86\_64 GNU/Linux system running Debian
   Stable.
 * It will be compiled with the following flags:

          gcc -std=c99 -pedantic -Wall -Werror -Wextra -O0 -g -ggdb myecho.c -o myecho
 * The program will be executed as follows:

          # <n> is the number of unsigned integers to be piped to stdin
          dd if=/dev/urandom bs=4 count=<n> | myecho
6. Add a program written in C to the project that provides a recursive
   implementation of the quicksort algorithm. The program will take a binary
   stream of unsigned integers as input and print them in sorted order to
   standard out.  The program should compile with GCC on a x86\_64 GNU/Linux
   system running Debian Stable.
 * It will be compiled with the following flags:

          gcc -std=c99 -pedantic -Wall -Werror -Wextra -O0 -g -ggdb mysort.c -o mysort
 * The program will be executed as follows:

          # <n> is the number of unsigned integers to be piped to stdin)
          dd if=/dev/urandom bs=4 count=<n> | mysort
7. Extra Credit: For a list of 256 integers we would expect on average to see
   2048 iterations through the algorithm.  How many would we expect for lists
   of size 2, 1024, 2048, and 65536?
8. Add any notes regarding your solution to the *Solution Notes* section.
9. Submit a link to your completed solution as well as any questions to
   <jcook@camber.com>.


Solution Notes
--------------

*Add solution notes here*


License
-------

This file is part of Shortest-Path-Server.

Copyright (c) 2013 __your-name-here__

Shortest-Path-Server is free software: you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by the Free
Software Foundation, either version 3 of the License, or (at your option) any
later version.

Shortest-Path-Server is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or
FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more
details.

You should have received a copy of the GNU General Public License along with
Shortest-Path-Server.  If not, see <http://www.gnu.org/licenses/>.
