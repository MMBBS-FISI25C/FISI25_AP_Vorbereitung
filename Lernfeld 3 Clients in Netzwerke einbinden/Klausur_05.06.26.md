# Lernfeld 3: Clients in Netzwerke einbinden – Klausur 05.06.26

## Ziel dieses Lernzettels

Dieser Lernzettel ist so geschrieben, dass ein Freund ohne Vorwissen dich damit abfragen kann.

Für deinen Freund gilt:

1. Lies zuerst die kurze Erklärung.
2. Stelle dann die Fragen.
3. Vergleiche deine Antwort mit den Musterantworten.
4. Wenn du etwas vergisst, soll dein Freund dir einzelne Stichworte als Hilfe geben.

---

## 1. Netzwerk-Grundlagen

### Was ist ein Netzwerk?

Ein Netzwerk verbindet Geräte miteinander, damit sie Daten austauschen können.

Beispiele:

- PC greift auf Drucker zu
- Laptop ruft eine Webseite auf
- Smartphone verbindet sich mit WLAN
- PC bekommt automatisch eine IP-Adresse vom DHCP-Server

### Wichtige Begriffe

| Begriff | Erklärung |
|---|---|
| **Client** | Gerät oder Programm, das einen Dienst anfordert, z. B. PC, Browser |
| **Server** | Gerät oder Programm, das einen Dienst bereitstellt, z. B. Webserver, DHCP-Server |
| **Endgerät** | Gerät am Rand des Netzwerks, z. B. PC, Laptop, Drucker, Smartphone |
| **Zwischengerät** | Gerät, das Daten weiterleitet, z. B. Switch, Router, Access Point, Firewall |

---

### Netzwerktypen

| Netzwerktyp | Bedeutung | Beispiel |
|---|---|---|
| **LAN** | Local Area Network, lokales Netzwerk | Heimnetz, Schulnetz, Firmennetz |
| **WAN** | Wide Area Network, großes Netzwerk über weite Strecken | Internet, Standortvernetzung |

---

### Abfragefragen

1. Was ist ein Netzwerk?
2. Was ist der Unterschied zwischen Client und Server?
3. Was ist ein Endgerät?
4. Was ist ein Zwischengerät?
5. Was ist der Unterschied zwischen LAN und WAN?

---

## 2. Netzwerktopologien

Eine **Topologie** beschreibt, wie ein Netzwerk aufgebaut ist.

### Physikalische Topologie

Die physikalische Topologie zeigt, wie Geräte tatsächlich verbunden sind.

Beispiel:

```text
PC ---- Switch ---- Router ---- Internet
```

Sie zeigt also:

- Kabelwege
- Gerätepositionen
- Anschlüsse
- physische Verbindungen

### Logische Topologie

Die logische Topologie zeigt, wie Daten logisch durch das Netzwerk fließen.

Beispiel:

```text
PC → Switch → Router → Internetserver
```

Sie zeigt also:

- IP-Netze
- Datenfluss
- Kommunikationswege
- VLANs/Subnetze, falls vorhanden

---

### Häufige Topologien

| Topologie | Erklärung |
|---|---|
| **Stern-Topologie** | Alle Geräte sind mit einem zentralen Switch verbunden |
| **Bus-Topologie** | Alle Geräte teilen sich eine gemeinsame Leitung |
| **Ring-Topologie** | Geräte sind ringförmig verbunden |
| **Mesh / vermascht** | Geräte haben mehrere Verbindungen untereinander |

Heute ist im LAN besonders die **Stern-Topologie mit Switches** üblich.

---

## 3. Hierarchische Netzwerkarchitektur

Größere Netzwerke werden oft in drei Schichten aufgebaut.

| Schicht | Aufgabe |
|---|---|
| **Access Layer** | Endgeräte werden angeschlossen, z. B. PCs, Drucker, Access Points |
| **Distribution Layer** | Verbindet Access-Switches, kann Routing, Filterung und VLAN-Verteilung übernehmen |
| **Core Layer** | Schnelles Backbone/Rückgrat des Netzwerks |

### Merksatz

> Access = Zugang für Endgeräte  
> Distribution = Verteilung  
> Core = schnelles Zentrum

---

### Abfragefragen

1. Was ist eine physikalische Topologie?
2. Was ist eine logische Topologie?
3. Was ist eine Stern-Topologie?
4. Welche drei Schichten hat die hierarchische Netzwerkarchitektur?
5. Was macht der Access Layer?
6. Was macht der Core Layer?

---

## 4. Protokolle und Netzwerkverkehr

### Was ist ein Protokoll?

Ein Protokoll ist ein Regelwerk für die Kommunikation zwischen Geräten.

Vergleich:

> Ein Protokoll ist wie eine gemeinsame Sprache mit festen Regeln.

---

### Netzwerkverkehrsarten

| Art | Bedeutung | Beispiel |
|---|---|---|
| **Unicast** | Ein Sender an genau einen Empfänger | PC sendet an Server |
| **Broadcast** | Ein Sender an alle Geräte im lokalen Netz | ARP-Anfrage |
| **Multicast** | Ein Sender an eine bestimmte Gruppe | Streaming an eine Gruppe |

---

### Wichtige Protokolle

| Protokoll | Aufgabe |
|---|---|
| **HTTP** | Überträgt Webseiten |
| **HTTPS** | Überträgt Webseiten verschlüsselt |
| **TCP** | Sorgt für zuverlässige Datenübertragung |
| **IPv4** | Logische Adressierung und Weiterleitung von Paketen |
| **SMTP** | E-Mails versenden |
| **POP3** | E-Mails vom Server abrufen, oft lokal speichern |
| **IMAP** | E-Mails auf dem Server verwalten und synchronisieren |
| **Ethernet** | Kommunikation im lokalen kabelgebundenen Netzwerk |
| **ARP** | Ermittelt zu einer IP-Adresse die passende MAC-Adresse |
| **DNS** | Wandelt Namen in IP-Adressen um |
| **DHCP** | Vergibt automatisch IP-Konfigurationen |

---

### Abfragefragen

1. Was ist ein Protokoll?
2. Was ist Unicast?
3. Was ist Broadcast?
4. Was ist Multicast?
5. Wofür wird HTTP verwendet?
6. Wofür wird TCP verwendet?
7. Wofür wird SMTP verwendet?
8. Was ist der Unterschied zwischen POP3 und IMAP?
9. Welche Aufgabe hat IPv4?

---

## 5. Zahlensysteme

## 6. OSI-Modell und TCP/IP-Modell

### OSI-Modell

Das OSI-Modell hat 7 Schichten.

| Schicht | Name | Aufgabe |
|---|---|---|
| 7 | Application | Anwendungen, z. B. HTTP, SMTP, DNS |
| 6 | Presentation | Darstellung, Verschlüsselung, Formatierung |
| 5 | Session | Sitzungen verwalten |
| 4 | Transport | TCP/UDP, Ende-zu-Ende-Kommunikation |
| 3 | Network | IP-Adressen, Routing |
| 2 | Data Link | MAC-Adressen, Ethernet, Frames, Switches |
| 1 | Physical | Kabel, Stecker, Signale, Funk |

---

### Besonders wichtig für LF3

| OSI-Schicht | Thema |
|---|---|
| **Layer 1 Physical** | Kabel, Signale, Übertragungsmedien |
| **Layer 2 Data Link** | Ethernet, MAC-Adressen, Switches |
| **Layer 3 Network** | IP-Adressen, Routing, Router |

---

### TCP/IP-Modell

| TCP/IP-Schicht | Entspricht ungefähr OSI |
|---|---|
| Application | OSI 5 bis 7 |
| Transport | OSI 4 |
| Internet | OSI 3 |
| Network Access | OSI 1 bis 2 |

---

### Abfragefragen

1. Wie viele Schichten hat das OSI-Modell?
2. Welche Schicht ist der Physical Layer?
3. Welche Schicht ist der Data Link Layer?
4. Welche Schicht ist der Network Layer?
5. Auf welcher Schicht arbeitet Ethernet hauptsächlich?
6. Auf welcher Schicht arbeitet IP?
7. Auf welcher Schicht arbeitet TCP?

---

## 7. Physical Layer

Der **Physical Layer** ist OSI-Schicht 1.

Er beschäftigt sich mit der physischen Übertragung von Daten.

Dazu gehören:

- Netzwerkkabel
- Stecker
- elektrische Signale
- Lichtsignale
- Funkwellen
- Übertragungsmedien

---

### Übertragungsmedien

| Medium | Erklärung |
|---|---|
| **Kupferkabel** | z. B. Twisted-Pair-Kabel mit RJ45-Stecker |
| **Glasfaser** | Übertragung mit Licht, schnell und störungsarm |
| **Funk** | WLAN, Bluetooth, Mobilfunk |

---

### Störquellen

| Störquelle | Erklärung |
|---|---|
| **EMI** | Elektromagnetische Interferenzen, z. B. durch Stromleitungen |
| **RFI** | Hochfrequenzstörungen, z. B. durch Funkquellen |
| **Crosstalk** | Übersprechen zwischen Adern oder Kabeln |

---

### Kennzahlen

| Begriff | Bedeutung |
|---|---|
| **Latenz** | Verzögerung bei der Datenübertragung |
| **Throughput** | Tatsächlich übertragene Datenmenge pro Zeit |
| **Goodput** | Nutzdatenrate ohne Protokoll-Overhead und Wiederholungen |

Beispiel:

Wenn insgesamt 100 Mbit/s übertragen werden, aber davon nur 90 Mbit/s echte Nutzdaten sind, beträgt der **Goodput 90 Mbit/s**.

---

### Standardorganisationen

| Organisation | Bedeutung |
|---|---|
| **IEEE** | Standards für Ethernet und WLAN, z. B. 802.3 und 802.11 |
| **ISO** | OSI-Modell |
| **IETF** | Internetstandards, RFCs |
| **TIA/EIA** | Verkabelungsstandards |

---

### Abfragefragen

1. Was macht der Physical Layer?
2. Welche drei Übertragungsmedien gibt es?
3. Was ist Latenz?
4. Was ist Throughput?
5. Was ist Goodput?
6. Was ist Crosstalk?
7. Warum ist Glasfaser weniger störanfällig als Kupfer?

---

## 8. Ethernet und Switching

### Ethernet

Ethernet ist die wichtigste Technik für kabelgebundene lokale Netzwerke.

Ethernet verwendet:

- MAC-Adressen
- Frames
- Switches
- Netzwerkkabel

---

### MAC-Adresse

Eine **MAC-Adresse** ist die Hardwareadresse einer Netzwerkkarte.

Beispiel:

```text
A4:B1:C1:22:7F:09
```

Eigenschaften:

- 48 Bit lang
- meistens hexadezimal dargestellt
- dient zur Kommunikation im lokalen Netzwerk
- arbeitet auf OSI-Schicht 2

---

### OUI

Die ersten 24 Bit einer MAC-Adresse heißen **OUI**.

OUI bedeutet:

```text
Organizationally Unique Identifier
```

Sie kennzeichnen den Hersteller der Netzwerkkarte.

Beispiel:

```text
A4:B1:C1:22:7F:09
```

`A4:B1:C1` ist der OUI-Bereich.

---

## 9. Switch

Ein Switch verbindet Geräte in einem lokalen Netzwerk.

Er arbeitet hauptsächlich auf **OSI-Schicht 2** und nutzt **MAC-Adressen**.

### MAC-Adresstabelle

Ein Switch merkt sich:

```text
Welche MAC-Adresse ist an welchem Port erreichbar?
```

Beispiel:

| MAC-Adresse | Switch-Port |
|---|---|
| AA:AA:AA:AA:AA:01 | Port 1 |
| BB:BB:BB:BB:BB:02 | Port 2 |

Wenn ein Frame an eine bekannte Ziel-MAC geschickt wird, sendet der Switch ihn nur an den passenden Port.

---

### Was passiert bei unbekannter Ziel-MAC?

Wenn der Switch die Ziel-MAC nicht kennt, sendet er den Frame an alle Ports außer dem Eingangsport.

Das nennt man:

```text
Flooding
```

---

### Weiterleitungsmethoden

| Methode | Erklärung | Vorteil | Nachteil |
|---|---|---|---|
| **Store-and-Forward** | Switch empfängt den kompletten Frame, prüft ihn und leitet ihn dann weiter | Fehlerhafte Frames können verworfen werden | etwas langsamer |
| **Cut-Through** | Switch leitet weiter, sobald die Ziel-MAC gelesen wurde | sehr schnell | fehlerhafte Frames können weitergeleitet werden |

---

### Speicherverfahren im Switch

| Verfahren | Erklärung |
|---|---|
| **Port-basiertes Speichern** | Jeder Port hat eigenen Pufferspeicher |
| **Shared Memory** | Alle Ports teilen sich einen gemeinsamen Speicher |

---

### Abfragefragen

1. Was ist Ethernet?
2. Was ist eine MAC-Adresse?
3. Wie lang ist eine MAC-Adresse?
4. Was ist der OUI?
5. Was macht ein Switch?
6. Was steht in einer MAC-Adresstabelle?
7. Was macht ein Switch bei unbekannter Ziel-MAC?
8. Was ist Store-and-Forward?
9. Was ist Cut-Through?
10. Was ist der Unterschied zwischen portbasiertem Speicher und Shared Memory?

---

## 10. ARP

ARP bedeutet:

```text
Address Resolution Protocol
```

ARP wird verwendet, um zu einer bekannten IP-Adresse die passende MAC-Adresse herauszufinden.

---

### Beispiel

Ein PC möchte an diese IP-Adresse senden:

```text
192.168.1.20
```

Er kennt aber die MAC-Adresse nicht.

Dann sendet er per Broadcast:

```text
Wer hat 192.168.1.20?
```

Das Gerät mit dieser IP antwortet:

```text
Ich habe 192.168.1.20, meine MAC-Adresse ist AA:BB:CC:DD:EE:FF.
```

Diese Information wird in der **ARP-Tabelle** gespeichert.

---

### ARP-Tabelle

Die ARP-Tabelle speichert IP-zu-MAC-Zuordnungen.

Beispiel:

| IP-Adresse | MAC-Adresse |
|---|---|
| 192.168.1.20 | AA:BB:CC:DD:EE:FF |

Befehl zum Anzeigen:

```text
arp -a
```

---

### Abfragefragen

1. Wofür steht ARP?
2. Welche Aufgabe hat ARP?
3. Warum verwendet ARP Broadcast?
4. Was steht in der ARP-Tabelle?
5. Mit welchem Befehl kann man die ARP-Tabelle anzeigen?

---

## 11. PDU, Kapselung und Entkapselung

### PDU

PDU bedeutet:

```text
Protocol Data Unit
```

Das ist die Dateneinheit einer bestimmten Netzwerkschicht.

| OSI-Schicht | PDU |
|---|---|
| Application | Daten |
| Transport | Segment |
| Network | Paket |
| Data Link | Frame |
| Physical | Bits |

---

### Merksatz

```text
Daten → Segment → Paket → Frame → Bits
```

---

### Kapselung

Beim Senden werden Daten schichtweise verpackt.

Beispiel:

```text
Daten
→ TCP-Segment
→ IP-Paket
→ Ethernet-Frame
→ Bits
```

---

### Entkapselung

Beim Empfänger wird alles wieder ausgepackt.

```text
Bits
→ Ethernet-Frame
→ IP-Paket
→ TCP-Segment
→ Daten
```

---

### Abfragefragen

1. Was bedeutet PDU?
2. Wie heißt die PDU auf Layer 4?
3. Wie heißt die PDU auf Layer 3?
4. Wie heißt die PDU auf Layer 2?
5. Wie heißt die PDU auf Layer 1?
6. Was bedeutet Kapselung?
7. Was bedeutet Entkapselung?

---

## 12. Network Layer und IP

Der **Network Layer** ist OSI-Schicht 3.

Er ist zuständig für:

- IP-Adressen
- Routing
- Kommunikation zwischen verschiedenen Netzwerken

---

### Eigenschaften von IP

| Eigenschaft | Erklärung |
|---|---|
| **Verbindungslos** | Vor dem Senden wird keine feste Verbindung aufgebaut |
| **Best Effort** | IP versucht zuzustellen, garantiert es aber nicht |
| **Unzuverlässig** | IP selbst bestätigt keine erfolgreiche Zustellung |
| **Medienunabhängig** | IP funktioniert über Kupfer, Glasfaser, WLAN usw. |

Wichtig:

> IP liefert keine Garantie. Zuverlässigkeit übernimmt z. B. TCP.

---

### Routing

Routing bedeutet:

```text
Ein Router entscheidet, wohin ein IP-Paket weitergeleitet wird.
```

Ein Router verbindet verschiedene Netzwerke.

Beispiel:

```text
PC-Netzwerk → Router → Internet
```

---

### Switch vs. Router

| Switch | Router |
|---|---|
| verbindet Geräte im gleichen Netzwerk | verbindet verschiedene Netzwerke |
| nutzt MAC-Adressen | nutzt IP-Adressen |
| arbeitet hauptsächlich auf OSI-Schicht 2 | arbeitet auf OSI-Schicht 3 |
| nutzt MAC-Adresstabelle | nutzt Routingtabelle |

---

### Abfragefragen

1. Was macht der Network Layer?
2. Was bedeutet Routing?
3. Was macht ein Router?
4. Was bedeutet „verbindungslos“ bei IP?
5. Was bedeutet „Best Effort“?
6. Warum gilt IP als unzuverlässig?
7. Was ist der Unterschied zwischen Switch und Router?

---

## 13. IP-Header, TTL und MTU

### IP-Header

Der IP-Header enthält Steuerinformationen für die Übertragung.

Wichtige Felder:

| Feld | Bedeutung |
|---|---|
| Quell-IP | IP-Adresse des Senders |
| Ziel-IP | IP-Adresse des Empfängers |
| TTL | Lebensdauer des Pakets |
| Protokoll | z. B. TCP oder UDP |
| Fragmentierungsinformationen | wichtig, wenn Pakete geteilt werden müssen |

---

### TTL

TTL bedeutet:

```text
Time To Live
```

Die TTL verhindert, dass Pakete endlos im Netzwerk kreisen.

Jeder Router verringert die TTL um 1.

Wenn die TTL 0 erreicht:

```text
Das Paket wird verworfen.
```

---

### MTU

MTU bedeutet:

```text
Maximum Transmission Unit
```

Sie gibt an, wie groß ein Paket maximal sein darf, damit es über ein Medium übertragen werden kann.

Typischer Ethernet-Wert:

```text
1500 Byte
```

---

### IPv4 und IPv6

| Version | Länge | Beispiel |
|---|---|---|
| **IPv4** | 32 Bit | 192.168.1.10 |
| **IPv6** | 128 Bit | 2001:db8::1 |

---

### Abfragefragen

1. Was steht im IP-Header?
2. Was bedeutet TTL?
3. Warum gibt es TTL?
4. Was passiert bei TTL = 0?
5. Was bedeutet MTU?
6. Wie viele Bit hat IPv4?
7. Wie viele Bit hat IPv6?

---

## 14. IPv4-Adressierung

Eine IPv4-Adresse besteht aus 32 Bit.

Beispiel:

```text
192.168.1.10
```

Sie wird in vier Blöcke mit je 8 Bit geschrieben.

```text
192 . 168 . 1 . 10
 8     8    8    8 Bit
```

---

### Netzwerkanteil und Hostanteil

Eine IP-Adresse besteht aus:

- Netzwerkanteil
- Hostanteil

Beispiel:

```text
192.168.1.10/24
```

`/24` bedeutet:

- 24 Bit Netzwerkanteil
- 8 Bit Hostanteil

---

### Präfixlänge und Subnetzmaske

| Präfix | Subnetzmaske | Hostbits | Nutzbare Hosts |
|---|---|---|---|
| /24 | 255.255.255.0 | 8 | 254 |
| /25 | 255.255.255.128 | 7 | 126 |
| /26 | 255.255.255.192 | 6 | 62 |
| /27 | 255.255.255.224 | 5 | 30 |
| /28 | 255.255.255.240 | 4 | 14 |
| /29 | 255.255.255.248 | 3 | 6 |
| /30 | 255.255.255.252 | 2 | 2 |

Formel:

```text
Nutzbare Hosts = 2^Hostbits - 2
```

Warum minus 2?

- eine Adresse ist die Netzwerkadresse
- eine Adresse ist die Broadcastadresse

---

## 15. Netzwerkadresse und Broadcastadresse

### Netzwerkadresse

Die erste Adresse eines Netzwerks.

Sie bezeichnet das Netzwerk selbst und darf keinem Host zugewiesen werden.

Beispiel:

```text
192.168.1.0/24
```

---

### Broadcastadresse

Die letzte Adresse eines Netzwerks.

An diese Adresse werden alle Geräte im Subnetz angesprochen.

Beispiel:

```text
192.168.1.255
```

---

### Hostadressen

Alle Adressen zwischen Netzwerkadresse und Broadcastadresse.

Beispiel bei:

```text
192.168.1.0/24
```

| Typ | Adresse |
|---|---|
| Netzwerkadresse | 192.168.1.0 |
| erste Hostadresse | 192.168.1.1 |
| letzte Hostadresse | 192.168.1.254 |
| Broadcastadresse | 192.168.1.255 |

---

## 16. Logisches UND

Das **logische UND** wird verwendet, um aus IP-Adresse und Subnetzmaske die Netzwerkadresse zu berechnen.

Regel:

| Bit A | Bit B | Ergebnis |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

Nur wenn beide Bits 1 sind, ist das Ergebnis 1.

---

### Beispiel

```text
IP-Adresse:    192.168.1.10
Subnetzmaske:  255.255.255.0
Netzwerk:      192.168.1.0
```

---

## 17. Private und öffentliche IP-Adressen

### Private IPv4-Adressbereiche

Private IP-Adressen werden in lokalen Netzwerken verwendet.

| Bereich | CIDR |
|---|---|
| 10.0.0.0 bis 10.255.255.255 | 10.0.0.0/8 |
| 172.16.0.0 bis 172.31.255.255 | 172.16.0.0/12 |
| 192.168.0.0 bis 192.168.255.255 | 192.168.0.0/16 |

Private IP-Adressen sind nicht direkt im Internet erreichbar.

---

### Öffentliche IP-Adressen

Öffentliche IP-Adressen sind weltweit eindeutig und im Internet erreichbar.

---

## 18. VLSM

VLSM bedeutet:

```text
Variable Length Subnet Mask
```

Damit kann man ein Netzwerk in unterschiedlich große Subnetze aufteilen.

Beispiel:

Ein Unternehmen braucht Subnetze für:

- 100 Hosts
- 50 Hosts
- 20 Hosts
- 2 Hosts

Dann verwendet man nicht überall gleich große Subnetze, sondern passende Größen.

---

### Vorgehen bei VLSM

1. Anforderungen nach Hostanzahl sortieren, größte zuerst.
2. Passende Subnetzgröße bestimmen.
3. Subnetze der Reihe nach vergeben.
4. Pro Subnetz bestimmen:
   - Netzwerkadresse
   - erste Hostadresse
   - letzte Hostadresse
   - Broadcastadresse

---

### Abfragefragen zu IPv4/Subnetting

1. Wie viele Bit hat eine IPv4-Adresse?
2. Was bedeutet `/24`?
3. Was ist eine Subnetzmaske?
4. Was ist eine Netzwerkadresse?
5. Was ist eine Broadcastadresse?
6. Warum zieht man bei der Hostanzahl 2 ab?
7. Wie berechnet man die Netzwerkadresse?
8. Was sind private IP-Adressen?
9. Nenne die drei privaten IPv4-Bereiche.
10. Was bedeutet VLSM?

---

## 19. Subnetting-Beispiel 1

Aufgabe:

```text
IP-Adresse: 192.168.10.34/27
```

Gesucht:

- Subnetzmaske
- Netzwerkadresse
- Broadcastadresse
- nutzbarer Hostbereich

---

### Schritt 1: Präfix bestimmen

```text
/27 = 255.255.255.224
```

Hostbits:

```text
32 - 27 = 5
```

Anzahl Adressen:

```text
2^5 = 32
```

Nutzbare Hosts:

```text
32 - 2 = 30
```

---

### Schritt 2: Blockgröße bestimmen

```text
256 - 224 = 32
```

Subnetze gehen also in 32er-Schritten:

```text
192.168.10.0
192.168.10.32
192.168.10.64
192.168.10.96
...
```

Die IP `192.168.10.34` liegt im Bereich:

```text
192.168.10.32 bis 192.168.10.63
```

---

### Ergebnis

| Wert | Ergebnis |
|---|---|
| Subnetzmaske | 255.255.255.224 |
| Netzwerkadresse | 192.168.10.32 |
| erste Hostadresse | 192.168.10.33 |
| letzte Hostadresse | 192.168.10.62 |
| Broadcastadresse | 192.168.10.63 |
| nutzbare Hosts | 30 |

---

## 20. Subnetting-Beispiel 2

Aufgabe:

```text
IP-Adresse: 192.168.5.70/26
```

---

### Schritt 1

```text
/26 = 255.255.255.192
```

Blockgröße:

```text
256 - 192 = 64
```

Subnetze:

```text
192.168.5.0   - 192.168.5.63
192.168.5.64  - 192.168.5.127
192.168.5.128 - 192.168.5.191
192.168.5.192 - 192.168.5.255
```

Die IP `192.168.5.70` liegt im Bereich:

```text
192.168.5.64 - 192.168.5.127
```

---

### Ergebnis

| Wert | Ergebnis |
|---|---|
| Subnetzmaske | 255.255.255.192 |
| Netzwerkadresse | 192.168.5.64 |
| erste Hostadresse | 192.168.5.65 |
| letzte Hostadresse | 192.168.5.126 |
| Broadcastadresse | 192.168.5.127 |
| nutzbare Hosts | 62 |

---

## 21. DNS, DHCP und APIPA

### DNS

DNS bedeutet:

```text
Domain Name System
```

DNS übersetzt Namen in IP-Adressen.

Beispiel:

```text
www.google.de → 142.250.x.x
```

Merksatz:

> DNS ist das Telefonbuch des Internets.

---

### DHCP

DHCP bedeutet:

```text
Dynamic Host Configuration Protocol
```

DHCP vergibt automatisch Netzwerkeinstellungen an Clients.

Dazu gehören:

- IP-Adresse
- Subnetzmaske
- Standardgateway
- DNS-Server

---

### DHCP-Ablauf: DORA

| Schritt | Bedeutung |
|---|---|
| **Discover** | Client sucht DHCP-Server |
| **Offer** | Server bietet eine IP-Adresse an |
| **Request** | Client fordert diese Adresse an |
| **Acknowledge** | Server bestätigt die Vergabe |

---

### APIPA

APIPA bedeutet:

```text
Automatic Private IP Addressing
```

Wenn ein Windows-Client keinen DHCP-Server erreicht, gibt er sich selbst eine Adresse aus dem Bereich:

```text
169.254.0.0/16
```

Beispiel:

```text
169.254.12.44
```

Das bedeutet meistens:

> Der Client hat keine gültige IP-Adresse vom DHCP-Server bekommen.

Mit APIPA ist meist nur lokale Kommunikation möglich, kein normaler Internetzugang.

---

### Abfragefragen

1. Was macht DNS?
2. Was macht DHCP?
3. Welche Informationen vergibt DHCP?
4. Wofür steht DORA?
5. Was ist APIPA?
6. Welche IP-Adresse deutet auf APIPA hin?
7. Was ist wahrscheinlich kaputt, wenn ein Client eine 169.254.x.x-Adresse hat?

---

## 22. Wireshark und Ethernet Frames

Mit Wireshark kann man Netzwerkverkehr analysieren.

Bei einem Ethernet-Frame sieht man z. B.:

- Quell-MAC-Adresse
- Ziel-MAC-Adresse
- EtherType, z. B. IPv4 oder ARP
- Nutzdaten

Wichtig:

Ein Ethernet-Frame gehört zu OSI-Schicht 2.

Ein IP-Paket steckt im Ethernet-Frame.

---

### Abfragefragen

1. Wofür wird Wireshark verwendet?
2. Was kann man in einem Ethernet-Frame sehen?
3. Auf welcher OSI-Schicht ist ein Ethernet-Frame?
4. Was steckt in einem Ethernet-Frame, wenn IPv4 verwendet wird?

---

## 23. Topologiekonfiguration bewerten

Bei einer Topologie wie „ChangeIT - Smart City“ muss man prüfen, ob das Netzwerk sinnvoll und korrekt eingerichtet ist.

Typische Prüfpunkte:

- Sind die IP-Adressen korrekt?
- Stimmen Subnetzmasken?
- Ist das Standardgateway korrekt?
- Funktioniert DHCP?
- Funktioniert DNS?
- Können Geräte sich gegenseitig per Ping erreichen?
- Sind Subnetze sinnvoll dimensioniert?
- Sind Access-, Distribution- und Core-Layer sinnvoll aufgebaut?
- Sind Router/Switches korrekt verbunden?

---

### Nützliche Befehle

| Befehl | Aufgabe |
|---|---|
| `ipconfig` | zeigt IP-Konfiguration unter Windows |
| `ipconfig /all` | zeigt detaillierte IP-Konfiguration |
| `ping` | testet Erreichbarkeit |
| `tracert` | zeigt den Weg zu einem Ziel |
| `arp -a` | zeigt ARP-Tabelle |
| `nslookup` | testet DNS-Auflösung |

---

### Typische Fehlersuche

Wenn ein Client keine Verbindung hat:

1. Kabel/WLAN prüfen
2. IP-Konfiguration prüfen
3. APIPA-Adresse prüfen
4. Gateway anpingen
5. DNS testen
6. Routing prüfen
7. ARP-Tabelle prüfen
8. Falls nötig: Wireshark verwenden

---

### Ping-Reihenfolge

```text
ping 127.0.0.1
```

Testet den eigenen TCP/IP-Stack.

```text
ping eigene IP
```

Testet die eigene Netzwerkkonfiguration.

```text
ping Standardgateway
```

Testet Verbindung zum Router.

```text
ping 8.8.8.8
```

Testet Internet ohne DNS.

```text
ping google.de
```

Testet Internet mit DNS.

---

## 24. Wichtigste Unterschiede

### Switch vs. Router

| Switch | Router |
|---|---|
| verbindet Geräte im gleichen Netzwerk | verbindet verschiedene Netzwerke |
| nutzt MAC-Adressen | nutzt IP-Adressen |
| arbeitet auf Layer 2 | arbeitet auf Layer 3 |
| nutzt MAC-Adresstabelle | nutzt Routingtabelle |

---

### MAC-Adresse vs. IP-Adresse

| MAC-Adresse | IP-Adresse |
|---|---|
| Hardwareadresse | logische Adresse |
| OSI-Schicht 2 | OSI-Schicht 3 |
| wichtig im lokalen Netzwerk | wichtig für Routing zwischen Netzwerken |
| Beispiel: AA:BB:CC:DD:EE:FF | Beispiel: 192.168.1.10 |

---

### Unicast vs. Broadcast vs. Multicast

| Art | Empfänger |
|---|---|
| Unicast | genau ein Empfänger |
| Broadcast | alle im lokalen Netzwerk |
| Multicast | bestimmte Gruppe |

---

### TCP vs. IP

| TCP | IP |
|---|---|
| zuverlässig | unzuverlässig / Best Effort |
| bestätigt Daten | keine Zustellgarantie |
| Transport Layer | Network Layer |
| arbeitet mit Ports | arbeitet mit IP-Adressen |

---

## 25. Kurze Merksätze

- Ein **Client** fordert Dienste an.
- Ein **Server** stellt Dienste bereit.
- Ein **Switch** leitet anhand von **MAC-Adressen** weiter.
- Ein **Router** leitet anhand von **IP-Adressen** weiter.
- **ARP** findet zu einer IP-Adresse die passende MAC-Adresse.
- **DNS** macht aus Namen IP-Adressen.
- **DHCP** vergibt automatisch IP-Konfigurationen.
- **APIPA** bedeutet oft: DHCP nicht erreichbar.
- **IP** ist verbindungslos und arbeitet nach Best Effort.
- **TCP** sorgt für zuverlässige Übertragung.
- Eine **PDU** ist die Dateneinheit einer Schicht.
- **TTL** verhindert endlose Paketweiterleitung.
- **MTU** gibt die maximale Paketgröße an.
- **Network Address** = erste Adresse im Subnetz.
- **Broadcast Address** = letzte Adresse im Subnetz.
- **VLSM** spart IP-Adressen durch unterschiedlich große Subnetze.

---

## 26. Großer Fragenkatalog zum Abfragen

### Grundlagen

1. Was ist ein Netzwerk?
2. Was ist ein Client?
3. Was ist ein Server?
4. Was ist ein Endgerät?
5. Was ist ein Zwischengerät?
6. Was ist der Unterschied zwischen LAN und WAN?

### Topologie

1. Was ist eine physikalische Topologie?
2. Was ist eine logische Topologie?
3. Was ist eine Stern-Topologie?
4. Was sind Access-, Distribution- und Core-Layer?

### Protokolle

1. Was ist ein Protokoll?
2. Was ist HTTP?
3. Was ist TCP?
4. Was ist IPv4?
5. Was ist SMTP?
6. Was ist POP3?
7. Was ist IMAP?
8. Was ist Ethernet?

### Verkehrstypen

1. Was ist Unicast?
2. Was ist Broadcast?
3. Was ist Multicast?
4. Wann wird Broadcast oft verwendet?

### OSI-Modell

1. Wie viele Schichten hat das OSI-Modell?
2. Was macht Layer 1?
3. Was macht Layer 2?
4. Was macht Layer 3?
5. Wo arbeitet ein Switch?
6. Wo arbeitet ein Router?

### Physical Layer

1. Welche Übertragungsmedien gibt es?
2. Was ist Latenz?
3. Was ist Throughput?
4. Was ist Goodput?
5. Was ist EMI?
6. Was ist Crosstalk?

### Ethernet und Switching

1. Was ist eine MAC-Adresse?
2. Was ist der OUI?
3. Was macht ein Switch?
4. Was steht in einer MAC-Adresstabelle?
5. Was ist Flooding?
6. Was ist Store-and-Forward?
7. Was ist Cut-Through?

### ARP

1. Was macht ARP?
2. Wie läuft ARP ab?
3. Warum nutzt ARP Broadcast?
4. Was steht in der ARP-Tabelle?

### PDU

1. Was bedeutet PDU?
2. Wie heißt die PDU auf Layer 4?
3. Wie heißt die PDU auf Layer 3?
4. Wie heißt die PDU auf Layer 2?
5. Wie heißt die PDU auf Layer 1?

### Network Layer

1. Was macht der Network Layer?
2. Was bedeutet Routing?
3. Was macht ein Router?
4. Was bedeutet Best Effort?
5. Warum ist IP unzuverlässig?
6. Was bedeutet medienunabhängig?

### IP-Header

1. Was ist TTL?
2. Was passiert bei TTL = 0?
3. Was ist MTU?
4. Wie viele Bit hat IPv4?
5. Wie viele Bit hat IPv6?

### IPv4 und Subnetting

1. Was bedeutet `/24`?
2. Was ist eine Subnetzmaske?
3. Was ist eine Netzwerkadresse?
4. Was ist eine Broadcastadresse?
5. Wie berechnet man nutzbare Hosts?
6. Was ist logisches UND?
7. Was bedeutet VLSM?
8. Welche privaten IPv4-Bereiche gibt es?

### Dienste

1. Was macht DNS?
2. Was macht DHCP?
3. Was bedeutet DORA?
4. Was ist APIPA?
5. Welche Adresse zeigt oft ein DHCP-Problem?

---

## 27. Testaufgaben mit Lösungen

### Aufgabe 1

Ein PC hat:

```text
192.168.1.50/24
```

Fragen:

1. Subnetzmaske?
2. Netzwerkadresse?
3. Broadcastadresse?
4. Hostbereich?

Lösung:

| Wert | Ergebnis |
|---|---|
| Subnetzmaske | 255.255.255.0 |
| Netzwerkadresse | 192.168.1.0 |
| erste Hostadresse | 192.168.1.1 |
| letzte Hostadresse | 192.168.1.254 |
| Broadcastadresse | 192.168.1.255 |

---

### Aufgabe 2

Ein PC hat:

```text
169.254.12.44
```

Was bedeutet das wahrscheinlich?

Lösung:

> Der PC hat vermutlich keinen DHCP-Server erreicht und nutzt APIPA.

---

### Aufgabe 3

Ein Switch bekommt einen Frame mit unbekannter Ziel-MAC.

Was macht er?

Lösung:

> Er sendet den Frame an alle Ports außer dem Eingangsport. Das nennt man Flooding.

---

### Aufgabe 4

Berechne:

```text
192.168.20.130/25
```

Lösung:

```text
/25 = 255.255.255.128
Blockgröße = 256 - 128 = 128
```

Subnetze:

```text
192.168.20.0   - 192.168.20.127
192.168.20.128 - 192.168.20.255
```

Die IP liegt im zweiten Subnetz.

| Wert | Ergebnis |
|---|---|
| Netzwerkadresse | 192.168.20.128 |
| erste Hostadresse | 192.168.20.129 |
| letzte Hostadresse | 192.168.20.254 |
| Broadcastadresse | 192.168.20.255 |
| nutzbare Hosts | 126 |

---

### Aufgabe 5

Ein Client kann `8.8.8.8` anpingen, aber `google.de` nicht.

Was ist vermutlich das Problem?

Lösung:

> Die Internetverbindung funktioniert grundsätzlich, aber DNS funktioniert wahrscheinlich nicht.

---

## 28. Prüfungsfokus

Diese Themen solltest du besonders sicher können:

1. Switch und Router unterscheiden
2. MAC-Adresse und IP-Adresse unterscheiden
3. ARP erklären
4. DNS, DHCP und APIPA erklären
5. OSI-Schichten 1 bis 3 erklären
6. PDU-Reihenfolge können
7. IPv4-Subnetting rechnen
8. Netzwerkadresse und Broadcastadresse bestimmen
9. private IP-Adressbereiche kennen
10. Unicast, Broadcast und Multicast unterscheiden
11. TTL und MTU erklären
12. Kapselung und Entkapselung erklären
13. Physical Layer mit Medien, Störungen und Kennzahlen erklären
14. Ethernet Switching mit MAC-Tabelle und Flooding erklären
15. Topologie auf Fehler prüfen können

---

### Empfehlung für deinen Freund beim Abfragen

Dein Freund soll nicht nur fragen:

> „Was ist DNS?“

Sondern auch nachhaken:

> „Kannst du ein Beispiel nennen?“  
> „Auf welcher Ebene passiert das?“  
> „Was wäre ein typischer Fehler?“  
> „Woran würdest du das erkennen?“  
> „Wie würdest du es testen?“

Wenn du ein Thema wirklich kannst, solltest du es einfach erklären können, als würdest du es einem Anfänger beibringen.
