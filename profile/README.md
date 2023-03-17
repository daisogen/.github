Daisōgen is a metaoperating system: a very reduced set of programs that can be combined with others, at will, to build a functional operating system. The most important programs are [the distribution builder](https://github.com/daisogen/Daisogen), and [the kernel](https://github.com/daisogen/kernel). The first is what helps you build a working iso file in a way that's easy to understand. The kernel is a very special one: all processes run in supervisor mode, with full permissions. It's also flat: _One Page Table to rule them all_. This makes it easy and fun to work with, following the line of what LoseThos was meant to become at its time. Any process can substitute another or monkeypatch existing functions to extend the functionality of
the system as a whole, or make it more efficient. Daisōgen is, thus, an empty canvas on which to draw cool stuff.

This is my second operating system project; the previous one was [Strife](https://github.com/the-strife-project), which was mostly based on security.
This one is the opposite, a completely insecure-by-default OS. However, it does take some ideas from Strife, such as the microkernel (this one is
AmigaOS style, with the point of plugging and unplugging modules on the fly) and the pointer directory (which was called PSNS in Strife).

[Start here.](https://github.com/daisogen/Daisogen)
