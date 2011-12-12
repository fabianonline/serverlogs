Start: Mitte 2010
Ende: offen

Problem
=======
System hängt sich einfach mitten im Betrieb auf.
Teilweise anscheinend nur bei gewisser IO-Last, manchmal aber auch einfach so.
Hat man Glück gehabt, bootet das System nach einem Reset dann normal und läuft wieder; ansonsten kann es aber auch vorkommen, dass fsck das Journal wiederherstellt und / oder das RAID einen Resync braucht (der dann wieder viel IO-Last verursacht, was einen schnelleren Reboot nötig macht...)

Ursache
=======
Unbekannt.

Problemlösungsschritte
======================
* Diverse Boot-Parameter (noapic, nolapic, libata.apci=false, libata.noncg=1 usw.) - ERFOLGLOS
* Kernel-Update - NOCH NICHT GETESTET
* Netzteil gewechselt - ERFOLGLOS
* Kühlung verbessert - ERFOLGLOS (wobei die Southbridge schon recht warm wurde...)