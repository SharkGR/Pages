---
title: Εγκατάσταση Mods
date: 2017-04-05 21:00:00
author: mak
forum-topic: 300
header:
    overlay_color: "#000"
    overlay_filter: "0.5"
    overlay_image: /assets/img/mods-setup/mods-install-header.png
---

{% include toc icon="gears" title="Περιεχόμενα" %}

{% capture imgbase %}{{ site.baseurl }}/assets/img/mods-setup/{% endcapture %}

Αν ξέρετε πως δουλεύει το arma3sync, τα στοιχεία που χρειάζεστε είναι:

```
Autoconfig: ftp://a3server.hellenic-milsim.community/.a3s/autoconfig
```


# Εγκατάσταση arma3sync

* Κατεβάζουμε το πρόγραμμα [απο εδώ][a3sdownload] (κάτω κάτω που λέει _Click to download ArmA3Sync_)
* Κάντε την εγκατάσταση και τρέξτε το πρόγραμμα

Την πρώτη φορά θα σας ζητήσει να του πείτε που είναι εγκατεστημένο το Arma. Ο φάκελος του Steam συνήθως βρίσκεται στην τοποθεσία: `C:\Program Files (x86)\Steam\steamapps\common\Arma 3`.

<img src="{{ imgbase }}1.png" class="align-center">

Βρείτε το `arma3_x64.exe` και πατήστε _Open_

<img src="{{ imgbase }}2.jpg" class="align-center">



# Κατέβασμα Mods

Πατήστε πάνω δεξια που λέει _Repositories_

<img src="{{ imgbase }}3.jpg" class="align-center">

μετά στον **μπλε σταυρό**

<img src="{{ imgbase }}4.jpg" class="align-center">

Στο παράθυρο _New Repository_ βάζουμε το εξής στο πεδίο _Public auto-config url_: `ftp://a3server.hellenic-milsim.community/.a3s/autoconfig`

<img src="{{ imgbase }}5.jpg" class="align-center">

Πατήστε _Import_ και μετα _ΟΚ_.

Στη συνέχεια επιλέξτε _Notify_ και _Auto_, και πατάμε το τελευταίο εικονίδιο

<img src="{{ imgbase }}7.jpg" class="align-center">

Περιμένετε να τελειώσει η μπάρα

<img src="{{ imgbase }}8.jpg" class="align-center">

Πατήστε _Select All_ και το κουμπί _Play_ <i class="fa fa-play" aria-hidden="true"></i>

<img src="{{ imgbase }}9.png" class="align-center">


# Ρύθμιση Modsets

Αφου τελειώσει το κατέβασμα, γυρίστε στην αρχική καρτέλα _Addons_, και πατήστε το κουμπί
_Modsets_.

<img src="{{ imgbase }}10.jpg" class="align-center">

Επιλέξτε το _All_ πατήστε _ΟΚ_.

<img src="{{ imgbase }}11.jpg" class="align-center">

Τέλος, επιλέξτε to _All_ απο το πάνελ _Addon Groups_, και πατήστε _Start Game_

<img src="{{ imgbase }}12.png" class="align-center">

[a3sdownload]: http://www.armaholic.com/page.php?id=22199
