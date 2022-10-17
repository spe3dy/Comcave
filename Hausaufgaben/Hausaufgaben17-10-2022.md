# Hausaufgaben vom 17-10-2022


Geben Sie fuer die Abkuergun DNS den vollstaendigen Begriff an und erkaleren Sie die Hauptaufabe von DNS:

 - DNS : Dynamic Name System ( Server) 
 - Dient dazu , die Server / Rechner via Namen anzusprechen.
   Da dieser sonst nur via IP angesprochen werden kann.

In einem Meeting werden ueber die Kenngroessen Daempung sowie Uebertragunsgeschwindigkeit gesporchen.
Erleuteren Sie Daempfung 
Wie sauber die Signale ueber die Leitung gehen. 
Erleutern Sie Uebertragungsgeschwindigkeit

   - Wie schnell was ins  / aus dem Lan / Wan geladen werden kann

Erlaeutern Sie Reichweite:

- Das ist die angegeben Strecke die ein Kabel genutzt werden kann.Das normale Lan Kabel sollte maximal 100 Meter
  haben, da sonst Verlusste in Kauf genommen werden.

DNS und DHCP sind meist in einem „Multifunktionalen“ Gerät voreingerichtet.
Welche Auswirkung auf das Netzwerk könnte sich ergeben, wenn zusätzlich ein „Managed Switch“ mit DHCP-Funktion in das Netz eingebunden wird.

 - Wenn es einen zusaetzlichen Switch gibt, der DHCP – Server spielt, kann es dazu kommen, dass das Routing im 
   Netzwerk nicht mehr stimmt. Sprich der Router vergibt ggf eine IP die nicht zu dem Netzwerk gehoert was geroutet werden soll.
   Da ggf kein GW gesetzt ist / wird

Welche Maßnahmen sind/wären zu treffen? 

 - i.d.R gibt es bei Mananged Switchen die Option zu sagen, dass nur der einer Port fuer DHCP – Server sind. 

Nennen sie Zweit Vorteile von LWL Kabel

 - Leitet keinen Strom.
 - Schneller Geschwindigkeit
 - Fehler unanfaelliger

Nennen Sie2 Pysikalische Netzwerk Topoligien

 - Meshtopologien
 - Bustopologien
 - Sterntopologien


Raid 10 ist das Sinnvollste, da kombiniert Sicherheit und gesteigerte Lese-/Schreibgeschwindigkeit – also die Eigenschaften beider RAID-Level.








Es gibt 3 Internet Angebote dazu, Wählen Sie entsprechen Ihrer Berechnung 

 - Durch den Upload, werden schon ca 12,5 Mbit/s verbraucht. Um nen Puffer zu haben, sollten wir die 15 Mbit/s nehmen.

Anbieter der Wahl :  SecOnline15 Mbit/s15 Mbit/s239,00 mtl    SDSL3

100.000 Tebibyte



VPN mit Statischen IPs :
Fehler sind : 
 - PC 1 hat eine flache IP (.0 wird nicht verwendet)
 - PC 2 falsche IP ( .1 ist die IP vom GW)
 - PC 22 SubNetMask ist falsch (255.255.255.0) 
 - PC 23 hat ein falsches GW (192.168.2.1) 
 - Pc 23 hat eine falsche IP (192.168.2.23)
 - PC N hat eine falsche IP (.255 ist Broadcast IP) 
 - PC x und n haben eine falsche Namens-struktur
 - PC x hat ein falsches GW (192.168.1.1)
