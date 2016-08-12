![GitHub Logo](http://www.heise.de/make/icons/make_logo.png)

Maker Media GmbH und c't, Heise Zeitschriften Verlag

***

#BDLC

BLDC-Controller zum Selbstbau mit Platinenlayout (nur bedrahtete Bauteile, keine SMD). Nach einer Idee von [Ulrich Radig](http://www.ulrichradig.de/home/index.php/avr/brushless-motor-controller).

Als Leistungs-MOSFETs kommen alle Typen mit 30 bis 60V Spannungsfestigkeit und min. 10A Strombelastbarkeit in Frage. Sie benötigen 3 Stück N-Kanal-MOSFETs (z.B. [IRFZ 34](https://www.reichelt.de/index.html?ACTION=3;ARTICLE=8819;SEARCH=IRFZ%2034)) und 3 Stück P-Kanal-MOSFETs (z.B. [IRF 9Z34N](https://www.reichelt.de/index.html?ACTION=3;ARTICLE=8819;SEARCH=IRFZ%209Z34)).

Das einseitige Platinenlayout wurde mit dem kostenlosen DesignSpark PCB 7.2 (für Windows) erstellt und kann damit leicht für eigene Zwecke angepasst werden.

Die Sourcen können mit AVR-GCC (WinAVR) kompiliert werden. Das HEX-File lässt sich auch über die Arduino-IDE in einen ATmega328 mit Bootloader flashen. Beachten Sie, dass die Registerbelegung für die AVR-Serie ATmega48/88/168/328 ausgelegt ist, nicht für den älteren ATmega8. Das Programm passt auch in einen ATmega48.

Bitte beachten Sie den Artikel in **[Make: 5/2016](http://www.heise.de/make/inhalt/2016/04/102/)**.
