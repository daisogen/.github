# Farewell
Today is October 21st, 2023. I haven't touched a single line of Daisogen since April. I started Daisogen at a time when I had a lot of free time and no real sense of purpose. Having finished [Strife](https://github.com/the-strife-project), I wanted to explore other approaches at operating systems, and thought that making yet another OS from scratch was the way to go.

Nowadays I'm employed full-time and way less time to work on my projects, so I'd rather invest that time in things that make me grow and don't require extensive hours to get anything done (even worse if they require reinventing the wheel). The drivers are definitely the worst part: they require the most effort and have little to do with actual kernel development, which is the part I was mostly interested in after I finished Strife.

For this reason, as of today, I'm forever abandoning Daisogen and, by extension, real osdev. I might touch kernel development in the future, maybe even bootloaders, but I will never write a SATA driver or an ELF parser again. IIRC (I won't check), Daisogen's code is at a working point. There are no broken commits that I recall, so its code might actually be useful for someone in the future: it's in Rust so it's way easier to read (simpler, shorter, etc) than Strife's C++ codebase. It is higher level though, as I didn't have to implement any data structure myself. No STL here.

**A word of caution** for those interested in getting into osdev: this is the most expansive and challenging area of CS. Most other areas are contained in this one: algorithms, data structures, concurrency, compilers, CPU architecture, and even computer graphics. Attaining a level of comprehension about computing sufficient to embark on kernel development demands hundreds of hours. If you aren't already fluent in assembly, consider spending your time on some other project that will be more useful to you. If you still want to get into it, welcome to the path to omniscience! Start at the [osdev wiki](https://wiki.osdev.org) but **do not** believe all the advice it gives. There is no up to date alternative to the wiki, so, by far, the best place to go is the [osdev Discord server](https://discord.gg/RnCtsqD), a great chat in which I have made plenty of friends.

Thanks for reading.

P.S.: if you want to check out what I'm up to, have a look at [my blog](https://jlxip.net/blog).
