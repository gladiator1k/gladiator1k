gladiator1k
===========

An or1k emulator and sandbox for the JVM (alpha status).

The emulator gets the first part of its name from the gladiators of Ancient Rome, because it is targeted at programming competitions. Its main purpose it to host multiple sandboxed environments. With this approach we can:

- compare the efficiency of submissions in a very direct way (e.g. CPU cycles, operations, "ROM" size)
- give each competitor a fair share of resources
- based challenges around real-world technologies like networking (since or1k is a fully-featured modern architecture)
- safely allow competitors to use low-level techniques
- let competitors run their own game server on a range of platforms (e.g. for local competitions or field-testing submissions)

The project has somewhat different goals and priorities to the javascript-based emulator [jor1k](https://github.com/s-macke/jor1k/wiki), but if you are interested in or1k or emulators then take a look at that project because it is awesome. It is also much further along than gladiator1k.

license
-------

gladiator1k is released under GPLv3+.

For emulator users, don't worry: the license of the emulator itself does not extend to your software just because you run or compile it inside the emulator. This isn't special to gladiator1k but is a common concern.

GPLv3 was chosen because the emulator is intended to be distributed with a number of tools and binaries, covered by GPL-compatible licenses. Using GPL throughout the distribution keeps the licensing easy to explain and gives plenty of freedom in how the emulator and other tools are combined. GPLv3+ is also compatible with a number of other popular licenses used in the Java community.

See LICENSE for the official details.

attributions
------------

Will be here when there are some...

related projects
----------------

* [or1k community portal](http://opencores.org/or1k/OR1K:Community_Portal)
* [jor1k](https://github.com/s-macke/jor1k/wiki) -- an or1k emulator that runs in the browser
* [or1ksim](https://github.com/openrisc/or1ksim) -- the functional reference emulator
* [openrisc](https://github.com/openrisc) -- openrisc organization page on github

milestones
----------

Since there is a lot to do, this project uses Github milestones. The project milestones are viewable [here](https://github.com/gladiator1k/gladiator1k/milestones).

Milestones are named after the gladiators from the 1992-2000 British TV series "Gladiators", chosen alphabetically. The first milestone is Ace, the next will be Blaze, and so on.
