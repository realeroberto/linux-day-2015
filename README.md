# All'ombra del Leviatano: Filesystem in Userspace

My talk at the [Linux Day 2015](http://lug.uniroma2.it/ld15/) in Rome (in Italian).

The [`master`](https://github.com/reale/linux-day-2015/tree/master) branch contains the source code, whilst the [`gh-pages`](https://github.com/reale/linux-day-2015/tree/gh-pages) branch contains the generated [web pages](https://reale.me/linux-day-2015).

The slides are also available in a printable format at [issuu](https://issuu.com/roberto-reale/docs/linux-day-2015) as well as at [SlideShare](https://www.slideshare.net/robertoreale/allombra-del-leviatano-filesystem-in-userspace-87942584).

## English Abstract

I offer a brief historical introduction as well as a technical overview of FUSE, an ingenious combination of a userspace interface and kernel code that allows us to implement, effortlessly, a filesystem in userspace. The reference implementation is fully FOSS, being covered by GPL for the kernel part, and by LGPL for the C library.

From a computer-theoretical point of view, through FUSE the Linux kernel draw closer to more “academic”, microkernel-based operating systems, like the Hurd.

A minimal but functional implementation of a toy filesystem is proposed as a working example.

## Abstract in italiano

L’intervento propone una brevissima introduzione storica e una panoramica tecnica di FUSE, la geniale combinazione di codice kernel e di API utente che consente di implementare, con sforzo ridotto, file system direttamente in user space.

L’implementazione di riferimento è pienamente FOSS, essendo coperta da GPL per la parte kernel, e da LGPL per la libreria C.

L’argomento ha peraltro un suo interesse anche dal punto di vista teorico, in quanto FUSE avvicina per certi versi il kernel Linux a sistemi operativi più “accademici” come Hurd.

Si intende concludere l’intervento presentando un semplice “working example”, un’implementazione minimale ma funzionante di un “toy file system”.

## License Notice

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>
