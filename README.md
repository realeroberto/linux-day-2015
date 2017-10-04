# All'ombra del Leviatano: Filesystem in Userspace

My [talk](https://robertoreale.me/linux-day-2015) at the [Linux Day 2015](http://lug.uniroma2.it/ld15/) in Rome (in Italian).

The slides are available in a printable format at [issuu](https://issuu.com/roberto-reale/docs/linux-day-2015) as well as at [SlideShare](https://www.slideshare.net/robertoreale/allombra-del-leviatano-filesystem-in-userspace).

## English Abstract

TODO

## Abstract in italiano

L’intervento propone una brevissima introduzione storica e una panoramica tecnica di FUSE, la geniale combinazione di codice kernel e di API utente che consente di implementare, con sforzo ridotto, file system direttamente in user space.

L’implementazione di riferimento è pienamente FOSS, essendo coperta da GPL per la parte kernel, e da LGPL per la libreria C.

L’argomento ha peraltro un suo interesse anche dal punto di vista teorico, in quanto FUSE avvicina per certi versi il kernel Linux a sistemi operativi più “accademici” come Hurd.

Si intende concludere l’intervento presentando un semplice “working example”, un’implementazione minimale ma funzionante di un “toy file system”.
