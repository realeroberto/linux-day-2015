# All’ombra del leviatano: Filesystem in Userspace

L’intervento propone una brevissima introduzione storica e una panoramica tecnica di FUSE, la geniale combinazione di codice kernel e di API utente che consente di implementare, con sforzo ridotto, file system direttamente in user space.

L’implementazione di riferimento è pienamente FOSS, essendo coperta da GPL per la parte kernel, e da LGPL per la libreria C.

L’argomento ha peraltro un suo interesse anche dal punto di vista teorico, in quanto FUSE avvicina per certi versi il kernel Linux a sistemi operativi più “accademici” come Hurd.

Si intende concludere l’intervento presentando un semplice “working example”, un’implementazione minimale ma funzionante di un “toy file system”.
