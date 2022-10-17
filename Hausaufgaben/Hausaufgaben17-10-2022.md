# Hausaufgaben vom 17-10-2022


Geben Sie fuer die Abkürzung DNS den vollständigen Begriff an und erkläeren Sie die Hauptaufgabe von DNS:

 - DNS : Dynamic Name System ( Server) 
 - Dient dazu , die Server / Rechner via Namen anzusprechen.
   Da dieser sont nur via IP angesprochen werden kann.

In einem Meeting werden ueber die Kenngroessen Dämpfung sowie Übertragungsgeschwindigkeit gesprochen.
Erleuteren Sie Daempfung 
     - Wie sauber die Signale ueber die Leitung gehen. Zudem hängt die Dämpfung ebenfalls vom verwendeten Kabel sowie den Endgeräten ab, welche die Dämpfung ebenfalls       beeinflussen.
Erleutern Sie Uebertragungsgeschwindigkeit

   - Wie schnell was ins  / aus den Lan / Wan geladen werden kann

Erlaeutern Sie Reichweite:

- Das ist die angegeben Strecke die ein Kabel genutzt werden kann.Das normale Lan Kabel sollte maximal 100 Meter
  haben, da sonst Verlusste in Kauf genommen werden.
  
  -------------------------------------

DNS und DHCP sind meist in einem „Multifunktionalen“ Gerät voreingerichtet.
Welche Auswirkung auf das Netzwerk könnte sich ergeben, wenn zusätzlich ein „Managed Switch“ mit DHCP-Funktion in das Netz eingebunden wird.

 - Wenn es einen zusaetzlichen Switch gibt, der DHCP – Server spielt, kann es dazu kommen, dass das Routing im 
   Netzwerk nicht mehr stimmt. Sprich der Router vergibt ggf eine IP die nicht zu dem Netzwerk gehoert was geroutet werden soll.
   Da ggf kein GW gesetzt ist / wird

Welche Maßnahmen sind/wären zu treffen? 

 - i.d.R gibt es bei Mananged Switchen die Option zu sagen, dass nur der einer Port fuer DHCP – Server sind. 

-------------------------------------

Nennen sie Zweit Vorteile von LWL Kabel

 - Leitet keinen Strom.
 - Schneller Geschwindigkeit
 - Fehler unanfaelliger

-------------------------------------

Nennen Sie2 Pysikalische Netzwerk Topoligien

 - Meshtopologien
 - Bustopologien
 - Sterntopologien

-------------------------------------

 Der neue File Server soll mit einem RAID-System die Datenverfügbarkeit erhöhen.

Raid 10 ist das Sinnvollste, da kombiniert Sicherheit und gesteigerte Lese-/Schreibgeschwindigkeit – also die Eigenschaften beider RAID-Level.
 
                                                                          A                              B
    RAID-Level:                                                           10                             5
    Die Anzahl an Festplatten die max. verlorengehen dürfen:              Je Sub max. 1                  1
    Nettospeicherkapazität des RAID-Systems in TiB:                       12 TiB                         18 TiB
    Speichereffizienz:                                                    50%                           25%

                     

A = (4/2)*6TiB=12TiB
B = (4-1)*6TiB=18TiB - 6TiB für die Parität


-------------------------------------
Ermitteln Sie zunächst die Zahl der Scans/Aufnahmen pro Tag. (2 Punkte) Der Rechenweg ist anzugeben:

Teile/Stunde 30 * 16 (Arbeits)Stunden = 480 Teile
480 Teile / 3 Scans = 160, was zudem die Anzahl der Teile ist, die nur von einer Seite gescannt werden.
Der Rest (480-160)=320 Teile * 2 Scans = 640 Scans.

Insgesamt ergeben sich daraus: 160 Scans + 640 Scans = 800 Scans pro Tag.

 Ermitteln sie anschließend das zu speichernde Datenvolumen pro Tag.

(50cm/2,54cm)*400 dpi = 7.875 Pixel
(30cm/2,54cm)*400 dpi = 4.725 Pixel
7.875 Pixel * 4.725 Pixel = 37.209.375 Pixel

37.209.375 * 24 Bit = 893.025.000 Bit
893.025.000 Bit / 8 = 111.628.125 Byte
111.628.125 Byte / 1000 = 111.629 KiloByte
109.012 KibiByte / 1000 = 112 MegaByte (Rundungsfehler nicht berücksichtigt)

1 Bild hat die Größe von 112 MegaByte.

800 Scans * 112 MegaByte = 89.600 MegaByte
89.600 MegaByte / 1024 = 88 GibiByte


-------------------------------------


Es gibt 3 Internet Angebote dazu, Wählen Sie entsprechen Ihrer Berechnung 

 - Durch den Upload, werden schon ca 12,5 Mbit/s verbraucht. Um nen Puffer zu haben, sollten wir die 15 Mbit/s nehmen.

Anbieter der Wahl :  SecOnline15 Mbit/s15 Mbit/s239,00 mtl    SDSL3

-------------------------------------

100.000 Tebibyte

-------------------------------------
 In der Zentralle ist für die Speicherung ein RAID-5-System mit Fünf Festplatten vorgesehen
 
 Bei 2 TiByte wird nur eine Kapazität von 10 TiB erreicht. 2 TiB werden für die Parität abgezogen (netto = 8 TiB)
 Bei 4 TiByte wird eine Kapazität von 20 TiB erreicht, von denen jedoch 4 TiB für die Parität abgezogen werden (netto = 16 TiB).
 Bei 8 TiByte wird eine Kapazität von 40 TiB erreicht, von denen 8 TiB für die Parität abgezogen wird (netto = 32 TiB).
 
 Da das Ziel eine Netto-Kapazität von 18 TiB verlangt, fallen sowohl die 2 TiByte, als auch die 4 TiByte Festplatten aus, da diese in einem RAID 5 unter dem geforderten Ziel liegen. Übrig bleibt nur die 8 TiByte Festplatten.


-------------------------------------

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
