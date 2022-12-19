Daisōgen is an flat operating system: all processes run in kernel mode, or ring 0, with full permissions. _One Page Table to rule them all_. This makes it easy and fun to work with,
following the line of what LoseThos was meant to become. Any process can substitute another or MITM its functions to extend the functionality of
the system as a whole, or make it more efficient. Daisōgen is, thus, an empty canvas on which to draw cool stuff.

This is my second operating system project; the previous one was [Strife](https://github.com/the-strife-project), which was mostly based on security.
This one is the opposite, a completely insecure-by-default OS. However, it does take some ideas from Strife, such as the microkernel (this one is
AmigaOS style, with the point of plugging and unplugging modules on the fly) and the pointer directory (which was called PSNS in Strife).

The default Daisōgen is simple: ISO9660 and FAT32 support, an IDE driver, an ELF parser, and not much else. Everything else you want to add or replace,
such as a network stack, is done after booting. You can add your programs to a modified ISO so that a distribution with extra stuff is loaded automatically.

The official projects, those in this GitHub organization, are written in Rust, but they can be written in any freestanding language (such as C or C++), so
Rust isn't necessarily _the_ language of Daisōgen, it's just the choice for this set of programs.
