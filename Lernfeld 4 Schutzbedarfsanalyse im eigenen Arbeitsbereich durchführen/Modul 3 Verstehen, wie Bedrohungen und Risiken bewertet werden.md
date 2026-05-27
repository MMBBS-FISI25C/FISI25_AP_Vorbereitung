# Lernzettel Modul 3: Verstehen, wie Bedrohungen und Risiken bewertet werden

## Überblick

In Modul 3 geht es darum, Bedrohungen und Risiken für die Informationssicherheit zu erkennen, voneinander zu unterscheiden und grundlegend zu bewerten.

Unternehmen arbeiten heute mit vielen verschiedenen IT-Ressourcen:

- Server
- PCs und Laptops
- Smartphones und Tablets
- Netzwerkgeräte
- Cloud-Dienste
- Software-Anwendungen
- Datenbanken
- Benutzerkonten
- Schnittstellen
- externe Dienstleister
- Homeoffice- und Telearbeitsplätze

Je größer und komplexer ein Unternehmen ist, desto schwieriger wird es, den Überblick über alle Hardware- und Softwarebestände zu behalten. Ohne regelmäßige Erfassung und Bewertung der IT-Ressourcen können Sicherheitslücken entstehen, die von Angreifern ausgenutzt werden oder durch Fehler zu Schäden führen.

---

# 1. Warum Bedrohungen und Risiken bewertet werden müssen

Informationssicherheit bedeutet nicht nur, technische Schutzmaßnahmen einzusetzen. Ein Unternehmen muss auch verstehen:

- Welche Werte müssen geschützt werden?
- Welche Bedrohungen gibt es?
- Welche Schwachstellen existieren?
- Welche Schäden könnten entstehen?
- Wie wahrscheinlich ist ein Vorfall?
- Welche Maßnahmen sind angemessen?

Das Ziel einer Risikoanalyse ist:

> Risiken für Informationen, Systeme und Geschäftsprozesse erkennen, bewerten und geeignete Schutzmaßnahmen ableiten.

---

## 1.1 Moderne Unternehmensumgebungen sind komplex

Früher befanden sich viele IT-Systeme direkt im Unternehmen. Heute sind IT-Landschaften deutlich verteilter.

Typische Bestandteile moderner IT-Umgebungen:

| Bereich | Beispiele |
|---|---|
| Lokale IT | PCs, Server, Drucker, Netzwerke |
| Mobile Geräte | Laptops, Tablets, Smartphones |
| Cloud-Dienste | Microsoft 365, Google Workspace, AWS, Azure |
| Homeoffice | VPN, private Netzwerke, mobile Arbeitsplätze |
| Externe Dienstleister | IT-Support, Hosting, Softwareanbieter |
| Anwendungen | ERP, CRM, E-Mail, Datenbanken |
| Kommunikation | Videokonferenzen, Chats, E-Mail |
| IoT / Spezialgeräte | Sensoren, Kameras, Produktionssysteme |

Je mehr Systeme, Geräte und Standorte es gibt, desto größer ist die Angriffsfläche.

---

## 1.2 Warum Asset-Management wichtig ist

Ein **Asset** ist ein Wert oder eine Ressource, die für ein Unternehmen wichtig ist.

Im IT- und Informationssicherheitsbereich können Assets zum Beispiel sein:

- Hardware
- Software
- Daten
- Benutzerkonten
- Netzwerke
- Räume
- Cloud-Dienste
- Geschäftsprozesse
- Dokumentationen
- Lizenzen
- Wissen von Mitarbeitenden

**Asset-Management** bedeutet:

> Ein Unternehmen erfasst und verwaltet seine wichtigen Ressourcen systematisch.

Ohne Asset-Management weiß ein Unternehmen oft nicht:

- Welche Geräte existieren?
- Welche Software ist installiert?
- Welche Systeme sind veraltet?
- Welche Daten liegen wo?
- Wer hat Zugriff worauf?
- Welche Systeme sind besonders kritisch?
- Welche Geräte befinden sich im Homeoffice?
- Welche Cloud-Dienste werden genutzt?

---

## 1.3 Risiken durch fehlenden Überblick

Wenn Hardware und Software nicht regelmäßig erfasst werden, entstehen Sicherheitsrisiken.

Beispiele:

- Ein alter Server erhält keine Sicherheitsupdates mehr.
- Ein unbekanntes Gerät ist im Netzwerk angeschlossen.
- Ein ehemaliger Mitarbeiter hat noch Zugriff auf ein System.
- Eine nicht freigegebene Cloud-App wird für Kundendaten genutzt.
- Ein Laptop mit sensiblen Daten ist nicht verschlüsselt.
- Eine Softwarelizenz läuft ab und wird nicht aktualisiert.
- Eine Anwendung enthält bekannte Sicherheitslücken.

Merksatz:

> Was man nicht kennt, kann man nicht schützen.

---

# 2. Aufgabenbereich 1: Definition von Bedrohungen und Risiken

## 2.1 Was ist eine Bedrohung?

Eine **Bedrohung** ist ein mögliches Ereignis oder eine mögliche Handlung, die Informationen, Systeme oder Prozesse schädigen kann.

Eine Bedrohung kann absichtlich oder unbeabsichtigt entstehen.

Beispiele für Bedrohungen:

- Hackerangriff
- Schadsoftware
- Phishing
- Feuer
- Wasserschaden
- Stromausfall
- menschlicher Fehler
- Diebstahl eines Laptops
- fehlerhaftes Software-Update
- Sabotage
- Ausfall eines Cloud-Dienstes

Definition:

> Eine Bedrohung ist eine mögliche Ursache für einen Schaden.

---

## 2.2 Was ist ein Risiko?

Ein **Risiko** beschreibt die Möglichkeit, dass eine Bedrohung eine Schwachstelle ausnutzt und dadurch ein Schaden entsteht.

Risiko besteht meist aus zwei Faktoren:

1. **Eintrittswahrscheinlichkeit**
2. **Schadenshöhe / Auswirkung**

Vereinfachte Formel:

> Risiko = Eintrittswahrscheinlichkeit × Schadensauswirkung

Beispiel:

> Bedrohung: Phishing-Mail  
> Schwachstelle: Mitarbeitende sind nicht geschult  
> Risiko: Ein Mitarbeiter gibt Zugangsdaten preis und ein Angreifer erhält Zugriff auf interne Systeme.

---

## 2.3 Was ist eine Schwachstelle?

Eine **Schwachstelle** ist eine Sicherheitslücke oder ein Mangel, der von einer Bedrohung ausgenutzt werden kann.

Beispiele:

- veraltete Software
- schwache Passwörter
- fehlende Verschlüsselung
- fehlende Backups
- falsch konfigurierte Cloud-Speicher
- ungeschulte Mitarbeitende
- fehlende Zutrittskontrolle
- zu viele Berechtigungen
- offene Netzwerkschnittstellen
- fehlende Sicherheitsupdates

Definition:

> Eine Schwachstelle ist ein vorhandener Mangel, der einen Schaden ermöglichen oder begünstigen kann.

---

## 2.4 Zusammenhang zwischen Bedrohung, Schwachstelle und Risiko

Diese drei Begriffe hängen eng zusammen.

| Begriff | Bedeutung | Beispiel |
|---|---|---|
| Bedrohung | Mögliche Ursache eines Schadens | Ransomware-Angriff |
| Schwachstelle | Ausnutzbarer Mangel | Kein aktuelles Backup |
| Risiko | Möglicher Schaden durch Bedrohung + Schwachstelle | Daten werden verschlüsselt und können nicht wiederhergestellt werden |

Merksatz:

> Eine Bedrohung wird erst dann zum konkreten Risiko, wenn sie auf eine Schwachstelle trifft.

---

## 2.5 Einfaches Beispiel

### Situation

Ein Unternehmen nutzt einen alten Server, der keine Sicherheitsupdates mehr erhält.

### Bedrohung

Ein Angreifer sucht im Internet nach verwundbaren Servern.

### Schwachstelle

Der Server ist veraltet und hat bekannte Sicherheitslücken.

### Risiko

Der Angreifer kann in das System eindringen, Daten stehlen oder Schadsoftware installieren.

### Mögliche Auswirkungen

- Verlust vertraulicher Daten
- Betriebsunterbrechung
- Datenschutzverletzung
- Imageschaden
- finanzielle Schäden

---

# 3. Unterschied zwischen Gefahr, Bedrohung, Schwachstelle und Risiko

Diese Begriffe werden oft verwechselt.

---

## 3.1 Gefahr

Eine Gefahr ist eine allgemein mögliche schädliche Situation.

Beispiel:

> Feuer ist eine Gefahr für Gebäude, Akten und Serverräume.

---

## 3.2 Bedrohung

Eine Bedrohung ist konkreter als eine allgemeine Gefahr. Sie kann ein bestimmtes Asset beeinträchtigen.

Beispiel:

> Ein Brand im Serverraum bedroht die Verfügbarkeit der IT-Systeme.

---

## 3.3 Schwachstelle

Eine Schwachstelle ist ein Mangel, der die Wirkung einer Bedrohung ermöglicht oder verstärkt.

Beispiel:

> Im Serverraum gibt es keine Brandmeldeanlage.

---

## 3.4 Risiko

Risiko ist die Kombination aus Wahrscheinlichkeit und Schaden.

Beispiel:

> Wenn ein Brand entsteht, werden Server zerstört und Systeme fallen mehrere Tage aus. Da es keine Brandmeldeanlage gibt, ist das Risiko hoch.

---

# 4. Schutzziele als Bewertungsgrundlage

Bedrohungen und Risiken werden oft danach bewertet, welche Schutzziele betroffen sind:

1. **Vertraulichkeit**
2. **Integrität**
3. **Verfügbarkeit**

---

## 4.1 Vertraulichkeit

Vertraulichkeit ist gefährdet, wenn Unbefugte Informationen sehen oder erhalten.

Beispiele:

- Kundendaten werden gestohlen.
- E-Mails werden an falsche Empfänger gesendet.
- Ein Cloud-Speicher ist öffentlich zugänglich.
- Zugangsdaten werden durch Phishing abgegriffen.

---

## 4.2 Integrität

Integrität ist gefährdet, wenn Daten unbemerkt verändert, manipuliert oder beschädigt werden.

Beispiele:

- Rechnungsdaten werden verändert.
- Lagerbestände sind falsch.
- Schadsoftware manipuliert Dateien.
- Ein Softwarefehler verändert Datenbankeinträge.

---

## 4.3 Verfügbarkeit

Verfügbarkeit ist gefährdet, wenn Informationen, Systeme oder Dienste nicht nutzbar sind.

Beispiele:

- Serverausfall
- DDoS-Angriff
- Stromausfall
- Ransomware verschlüsselt Daten
- Cloud-Dienst ist nicht erreichbar

---

## 4.4 Beispiel mit Schutzzielen

### Bedrohung: Ransomware

Ransomware ist Schadsoftware, die Daten verschlüsselt und Lösegeld fordert.

| Schutzziel | Auswirkung |
|---|---|
| Vertraulichkeit | Daten können zusätzlich gestohlen werden |
| Integrität | Dateien werden verändert oder verschlüsselt |
| Verfügbarkeit | Systeme und Daten sind nicht mehr nutzbar |

Ransomware kann also alle drei Schutzziele gleichzeitig gefährden.

---

# 5. Wie werden Risiken bewertet?

Risiken werden normalerweise nicht nur beschrieben, sondern auch bewertet.

Dabei werden meist zwei Fragen gestellt:

1. **Wie wahrscheinlich ist das Ereignis?**
2. **Wie groß wäre der Schaden?**

---

## 5.1 Eintrittswahrscheinlichkeit

Die Eintrittswahrscheinlichkeit beschreibt, wie wahrscheinlich ein Sicherheitsvorfall ist.

Mögliche Einstufung:

| Stufe | Bedeutung |
|---|---|
| niedrig | tritt selten auf |
| mittel | kann gelegentlich auftreten |
| hoch | tritt wahrscheinlich oder regelmäßig auf |

Beispiel:

> Phishing-Mails treten in vielen Unternehmen sehr häufig auf. Die Eintrittswahrscheinlichkeit ist daher oft hoch.

---

## 5.2 Schadensauswirkung

Die Schadensauswirkung beschreibt, wie stark ein Vorfall das Unternehmen beeinträchtigen würde.

Mögliche Einstufung:

| Stufe | Bedeutung |
|---|---|
| niedrig | geringer Schaden, schnell behebbar |
| mittel | spürbarer Schaden, aber beherrschbar |
| hoch | erheblicher Schaden, Betriebsstörung oder rechtliche Folgen |
| sehr hoch | existenzbedrohend oder massive Auswirkungen |

Beispiel:

> Der Ausfall eines zentralen Produktionssystems kann eine hohe oder sehr hohe Schadensauswirkung haben.

---

## 5.3 Risikomatrix

Eine einfache Risikomatrix kombiniert Eintrittswahrscheinlichkeit und Schadensauswirkung.

| Eintrittswahrscheinlichkeit / Schaden | niedrig | mittel | hoch |
|---|---|---|---|
| niedrig | niedriges Risiko | niedrig bis mittel | mittel |
| mittel | niedrig bis mittel | mittel | hoch |
| hoch | mittel | hoch | sehr hoch |

Beispiel:

> Eine Bedrohung mit hoher Wahrscheinlichkeit und hohem Schaden ergibt ein sehr hohes Risiko.

---

## 5.4 Beispiel Risikobewertung: Phishing

### Bedrohung

Mitarbeitende erhalten Phishing-Mails.

### Schwachstellen

- fehlende Schulung
- keine Zwei-Faktor-Authentifizierung
- schwache Passwörter
- keine E-Mail-Filter
- fehlende Meldeprozesse

### Eintrittswahrscheinlichkeit

hoch, weil Phishing sehr häufig vorkommt.

### Schadensauswirkung

hoch, wenn Angreifer Zugang zu internen Systemen erhalten.

### Risiko

hoch bis sehr hoch.

### Maßnahmen

- Schulungen
- Zwei-Faktor-Authentifizierung
- E-Mail-Filter
- Meldebutton für verdächtige E-Mails
- Passwortregeln
- Zugriffsbeschränkungen

---

## 5.5 Beispiel Risikobewertung: Wasserschaden im Serverraum

### Bedrohung

Wasserrohrbruch oder Überschwemmung.

### Schwachstellen

- Serverraum im Keller
- keine Wassersensoren
- keine Notfallpläne
- keine ausgelagerten Backups

### Eintrittswahrscheinlichkeit

niedrig bis mittel.

### Schadensauswirkung

hoch bis sehr hoch.

### Risiko

mittel bis hoch, je nach Standort und Schutzmaßnahmen.

### Maßnahmen

- Serverraum nicht in gefährdeten Bereichen
- Wassermelder
- Notfallplan
- regelmäßige Backups
- Ausweichrechenzentrum
- Cloud- oder Ersatzsysteme

---

# 6. Aufgabenbereich 2: Unterschied zwischen Bedrohungen und Schwachstellen

## 6.1 Kernaussage

Eine Bedrohung ist etwas, das Schaden verursachen kann.

Eine Schwachstelle ist ein Mangel, der diesen Schaden ermöglicht oder erleichtert.

---

## 6.2 Vergleich

| Bedrohung | Schwachstelle |
|---|---|
| kommt von außen oder innen | befindet sich im System, Prozess oder Verhalten |
| kann Schaden auslösen | ermöglicht oder erleichtert den Schaden |
| ist ein Ereignis oder Akteur | ist ein Mangel oder eine Lücke |
| Beispiel: Hackerangriff | Beispiel: veraltete Software |
| Beispiel: Feuer | Beispiel: fehlende Brandmeldeanlage |
| Beispiel: Phishing | Beispiel: ungeschulte Mitarbeitende |

---

## 6.3 Beispiele als Paare

| Bedrohung | Schwachstelle | Mögliches Risiko |
|---|---|---|
| Phishing-Mail | Mitarbeitende erkennen Phishing nicht | Zugangsdaten werden gestohlen |
| Ransomware | keine Backups | Datenverlust und Betriebsstillstand |
| Hackerangriff | ungepatchte Sicherheitslücke | unbefugter Zugriff |
| Diebstahl | Laptop unverschlüsselt | Daten werden offengelegt |
| Feuer | keine Brandmeldeanlage | Server werden zerstört |
| Stromausfall | keine USV | Systeme fallen sofort aus |
| Fehlbedienung | keine Schulung | Daten werden gelöscht |
| Cloud-Angriff | falsche Berechtigungen | Daten sind öffentlich zugänglich |
| Schadsoftware | fehlender Virenschutz | Systeme werden infiziert |
| Insider | zu weitreichende Rechte | Daten werden missbraucht |

---

## 6.4 Anschauliche Merkhilfe

Stell dir ein Haus vor:

- Bedrohung: Ein Einbrecher
- Schwachstelle: Offenes Fenster
- Risiko: Einbruch und Diebstahl

Übertragen auf IT:

- Bedrohung: Angreifer
- Schwachstelle: schwaches Passwort
- Risiko: unbefugter Zugriff auf das Benutzerkonto

---

# 7. Aufgabenbereich 3: Beispiele für verschiedene Bedrohungen in der digitalen Welt

Bedrohungen können sehr unterschiedlich sein. Man kann sie nach Ursachen einteilen.

---

# 8. Vorsätzliche Handlungen

Vorsätzliche Handlungen sind absichtliche Angriffe oder Sabotage.

---

## 8.1 Malware

Malware ist Schadsoftware.

Arten von Malware:

- Viren
- Würmer
- Trojaner
- Spyware
- Ransomware
- Keylogger
- Botnet-Software

Mögliche Folgen:

- Datenverlust
- Datendiebstahl
- Systemausfall
- Verschlüsselung von Dateien
- Ausspähen von Passwörtern
- Manipulation von Systemen

Schutzziele betroffen:

| Schutzziel | Wirkung |
|---|---|
| Vertraulichkeit | Daten werden ausgespäht |
| Integrität | Dateien werden verändert |
| Verfügbarkeit | Systeme fallen aus |

---

## 8.2 Ransomware

Ransomware ist eine besonders gefährliche Form von Malware.

Sie verschlüsselt Daten oder Systeme und fordert Lösegeld.

Moderne Ransomware-Angriffe enthalten oft zwei Schritte:

1. Daten werden gestohlen.
2. Daten werden verschlüsselt.

Das nennt man häufig **Double Extortion**, also doppelte Erpressung.

Mögliche Folgen:

- Geschäftsprozesse stehen still.
- Daten sind nicht verfügbar.
- vertrauliche Daten werden veröffentlicht.
- hohe Wiederherstellungskosten entstehen.
- Datenschutzverletzungen müssen gemeldet werden.
- Imageschäden entstehen.

Schutzmaßnahmen:

- regelmäßige Backups
- Offline-Backups
- Updates
- E-Mail-Schutz
- Schulungen
- Netzwerksegmentierung
- Zwei-Faktor-Authentifizierung
- Notfallplan

---

## 8.3 Phishing

Phishing ist der Versuch, Menschen zu täuschen, damit sie vertrauliche Informationen preisgeben oder Schadsoftware ausführen.

Beispiele:

- gefälschte Bank-E-Mail
- angebliche Paketbenachrichtigung
- gefälschte Microsoft-365-Anmeldung
- falscher Chef bittet um Überweisung
- gefälschte Support-Nachricht

Ziele von Phishing:

- Passwörter stehlen
- Zahlungsdaten erlangen
- Schadsoftware verbreiten
- Überweisungen auslösen
- Zugriff auf Unternehmenssysteme erhalten

Typische Merkmale:

- dringender Handlungsdruck
- Drohungen
- ungewöhnliche Absenderadresse
- Rechtschreibfehler
- verdächtige Links
- unerwartete Anhänge
- Aufforderung zur Passworteingabe

---

## 8.4 Spear-Phishing

Spear-Phishing ist gezieltes Phishing gegen bestimmte Personen oder Unternehmen.

Beispiel:

> Ein Angreifer recherchiert auf LinkedIn den Namen eines Abteilungsleiters und sendet eine täuschend echte E-Mail an die Buchhaltung.

Spear-Phishing ist gefährlicher als normales Phishing, weil es persönlicher und glaubwürdiger wirkt.

---

## 8.5 CEO-Fraud / Business E-Mail Compromise

Beim CEO-Fraud gibt sich ein Angreifer als Geschäftsführer oder Führungskraft aus.

Ziel:

> Mitarbeitende sollen eine Überweisung auslösen oder vertrauliche Informationen weitergeben.

Beispiel:

> „Bitte überweisen Sie dringend 45.000 Euro an diesen neuen Geschäftspartner. Ich bin gerade im Meeting und nicht erreichbar.“

Schutzmaßnahmen:

- Vier-Augen-Prinzip
- telefonische Rückbestätigung
- klare Zahlungsprozesse
- Schulungen
- Warnung vor Dringlichkeit und Geheimhaltung

---

## 8.6 Social Engineering

Social Engineering bedeutet, Menschen psychologisch zu manipulieren.

Angreifer nutzen zum Beispiel:

- Hilfsbereitschaft
- Angst
- Zeitdruck
- Autorität
- Neugier
- Vertrauen
- Unwissenheit

Beispiele:

- Angreifer gibt sich als IT-Support aus.
- Angreifer fragt telefonisch nach Zugangsdaten.
- Angreifer folgt Mitarbeitenden durch eine Tür ins Gebäude.
- Angreifer hinterlässt präparierte USB-Sticks.

Merksatz:

> Beim Social Engineering ist der Mensch das Angriffsziel.

---

## 8.7 Passwortangriffe

Angreifer versuchen, Passwörter zu erraten oder zu knacken.

Arten:

| Angriff | Erklärung |
|---|---|
| Brute Force | systematisches Ausprobieren vieler Kombinationen |
| Wörterbuchangriff | Ausprobieren bekannter Wörter und Passwortlisten |
| Credential Stuffing | Nutzung geleakter Passwörter von anderen Diensten |
| Passwort-Spraying | wenige häufige Passwörter gegen viele Konten |
| Keylogging | Mitschneiden von Tastatureingaben |

Schutzmaßnahmen:

- starke Passwörter
- Passwortmanager
- Zwei-Faktor-Authentifizierung
- Sperrung nach Fehlversuchen
- keine Passwortwiederverwendung
- Sicherheitsüberwachung

---

## 8.8 DDoS-Angriffe

DDoS steht für **Distributed Denial of Service**.

Dabei wird ein Dienst mit sehr vielen Anfragen überlastet.

Ziel:

> Systeme oder Webseiten sollen nicht mehr erreichbar sein.

Mögliche Folgen:

- Website-Ausfall
- Onlineshop nicht erreichbar
- Kunden können Dienste nicht nutzen
- Umsatzverlust
- Imageschaden

Betroffenes Schutzziel:

> Verfügbarkeit

---

## 8.9 Man-in-the-Middle-Angriffe

Bei einem Man-in-the-Middle-Angriff schaltet sich ein Angreifer zwischen zwei Kommunikationspartner.

Ziel:

- Daten mitlesen
- Daten verändern
- Zugangsdaten abfangen
- Kommunikation manipulieren

Beispiel:

> Ein Nutzer verbindet sich mit einem unsicheren öffentlichen WLAN. Ein Angreifer liest unverschlüsselte Verbindungen mit.

Schutzmaßnahmen:

- HTTPS
- VPN
- Zertifikatsprüfung
- keine sensiblen Aktionen in unsicheren WLANs
- sichere WLAN-Konfiguration

---

## 8.10 Insider-Bedrohungen

Insider sind Personen innerhalb der Organisation.

Das können sein:

- Mitarbeitende
- ehemalige Mitarbeitende
- Dienstleister
- Administratoren
- Praktikanten

Insider können absichtlich oder versehentlich Schäden verursachen.

Beispiele:

- Mitarbeiter kopiert Kundendaten.
- Administrator missbraucht hohe Rechte.
- ehemaliger Mitarbeiter hat noch Zugriff.
- Mitarbeiter löscht versehentlich Dateien.
- Dienstleister greift auf mehr Daten zu als nötig.

Schutzmaßnahmen:

- Berechtigungskonzept
- Need-to-know-Prinzip
- Protokollierung
- Offboarding-Prozess
- Vier-Augen-Prinzip
- Schulungen
- Trennung kritischer Aufgaben

---

# 9. Menschliche Fehler

Nicht alle Sicherheitsvorfälle entstehen durch böse Absicht. Viele entstehen durch Versehen.

---

## 9.1 Typische menschliche Fehler

Beispiele:

- E-Mail an falschen Empfänger
- vertraulicher Anhang vergessen zu verschlüsseln
- Datei versehentlich gelöscht
- falsche Berechtigungen gesetzt
- Passwort notiert oder geteilt
- auf Phishing-Link geklickt
- USB-Stick verloren
- Laptop im Zug vergessen
- Update falsch durchgeführt
- Cloud-Ordner öffentlich freigegeben

---

## 9.2 Auswirkungen menschlicher Fehler

Menschliche Fehler können alle Schutzziele beeinträchtigen.

| Fehler | Betroffenes Schutzziel |
|---|---|
| E-Mail an falschen Empfänger | Vertraulichkeit |
| falsche Daten eingegeben | Integrität |
| System falsch konfiguriert | Verfügbarkeit / Vertraulichkeit |
| Datei gelöscht | Verfügbarkeit |
| falsche Berechtigungen | Vertraulichkeit |
| falsches Update | Verfügbarkeit / Integrität |

---

## 9.3 Schutzmaßnahmen gegen menschliche Fehler

- klare Arbeitsanweisungen
- Schulungen
- Vier-Augen-Prinzip
- technische Prüfungen
- Berechtigungskonzepte
- Warnhinweise
- automatische Backups
- einfache Meldewege
- Fehlerkultur statt Schuldzuweisung

Wichtig:

> Menschen machen Fehler. Gute Informationssicherheit plant das ein.

---

# 10. Technische Fehler und Systemausfälle

Technische Fehler entstehen durch Hardware, Software oder Infrastruktur.

---

## 10.1 Hardwareausfall

Beispiele:

- Festplatte defekt
- Netzteil fällt aus
- Server überhitzt
- Router geht kaputt
- Smartphone beschädigt
- Akku versagt

Mögliche Folgen:

- Datenverlust
- Arbeitsunterbrechung
- Systemausfall
- Produktionsstörung

Schutzmaßnahmen:

- redundante Systeme
- Ersatzgeräte
- Backups
- Monitoring
- Wartung
- Garantie- und Austauschprozesse

---

## 10.2 Softwarefehler

Beispiele:

- Programm stürzt ab
- Datenbankfehler
- fehlerhafte Berechnung
- Kompatibilitätsproblem
- Sicherheitslücke in Software
- Speicherfehler
- Fehlfunktion nach Update

Mögliche Folgen:

- falsche Daten
- Ausfall von Anwendungen
- Sicherheitslücken
- fehlerhafte Geschäftsentscheidungen

---

## 10.3 Missglückte Software-Updates

Software-Updates sind wichtig, können aber selbst Probleme verursachen.

Beispiele:

- Update macht Anwendung unbrauchbar.
- Datenbankstruktur wird beschädigt.
- neue Version ist nicht kompatibel.
- Sicherheitsupdate verursacht Systemabsturz.
- Konfiguration wird überschrieben.

Betroffene Schutzziele:

| Schutzziel | Mögliche Auswirkung |
|---|---|
| Verfügbarkeit | System funktioniert nicht mehr |
| Integrität | Daten werden falsch verändert |
| Vertraulichkeit | Sicherheitskonfiguration wird fehlerhaft |

Schutzmaßnahmen:

- Updates zuerst testen
- Wartungsfenster planen
- Backup vor Update
- Rollback-Plan
- Dokumentation
- Freigabeprozess
- Monitoring nach Update

---

## 10.4 Fehlkonfigurationen

Fehlkonfigurationen sind eine häufige Ursache für Sicherheitsvorfälle.

Beispiele:

- Cloud-Speicher ist öffentlich erreichbar.
- Firewall-Regeln sind zu offen.
- Standardpasswörter wurden nicht geändert.
- Testsysteme sind aus dem Internet erreichbar.
- Benutzer haben zu viele Rechte.
- Datenbank ist ohne Passwort erreichbar.

Schutzmaßnahmen:

- Konfigurationsprüfung
- Sicherheitsstandards
- Vier-Augen-Prinzip
- automatisierte Scans
- regelmäßige Audits
- Dokumentation

---

# 11. Naturkatastrophen und physische Bedrohungen

Bedrohungen müssen nicht digital sein. Auch physische Ereignisse können Informationssicherheit gefährden.

---

## 11.1 Naturkatastrophen

Beispiele:

- Feuer
- Überschwemmung
- Sturm
- Erdbeben
- Blitzschlag
- extreme Hitze
- Schneelast

Mögliche Folgen:

- Server werden zerstört.
- Papierakten gehen verloren.
- Gebäude ist nicht zugänglich.
- Stromversorgung fällt aus.
- Mitarbeitende können nicht arbeiten.
- Netzwerkinfrastruktur wird beschädigt.

Schutzmaßnahmen:

- Brandschutz
- Wasserschutz
- Notfallpläne
- Ausweichstandorte
- Cloud-Backups
- redundante Rechenzentren
- Versicherungen
- regelmäßige Übungen

---

## 11.2 Stromausfall

Ein Stromausfall kann viele Systeme sofort beeinträchtigen.

Mögliche Folgen:

- Server fahren abrupt herunter.
- Daten werden beschädigt.
- Netzwerk ist nicht erreichbar.
- Telefonanlagen fallen aus.
- Produktionsanlagen stoppen.

Schutzmaßnahmen:

- USV
- Notstromaggregat
- geordnetes Herunterfahren
- redundante Stromversorgung
- Notfallkonzept

USV bedeutet:

> Unterbrechungsfreie Stromversorgung.

---

## 11.3 Diebstahl und Verlust

Beispiele:

- Laptop wird gestohlen.
- Smartphone geht verloren.
- USB-Stick bleibt im Zug liegen.
- Aktenordner wird entwendet.
- Serverhardware wird gestohlen.

Risiken:

- Offenlegung vertraulicher Daten
- Identitätsmissbrauch
- Verlust wichtiger Informationen
- Datenschutzverletzung

Schutzmaßnahmen:

- Geräteverschlüsselung
- Bildschirmsperre
- starke Passwörter
- Mobile Device Management
- Fernlöschung
- sichere Aufbewahrung
- keine sensiblen Daten lokal speichern

---

# 12. Bedrohungen durch Cloud und externe Dienstleister

Viele Unternehmen nutzen Cloud-Dienste. Das bringt Vorteile, aber auch Risiken.

---

## 12.1 Typische Cloud-Risiken

Beispiele:

- falsche Zugriffsrechte
- öffentliche Freigaben
- unsichere Passwörter
- fehlende Zwei-Faktor-Authentifizierung
- Datenübertragung in unsichere Drittstaaten
- Ausfall des Cloud-Anbieters
- Abhängigkeit von einem Anbieter
- unklare Verantwortlichkeiten
- fehlende Backups
- Schatten-IT

---

## 12.2 Schatten-IT

Schatten-IT bezeichnet IT-Lösungen, die ohne Freigabe der IT-Abteilung genutzt werden.

Beispiele:

- private Dropbox für Firmendaten
- nicht genehmigte KI-Tools
- private E-Mail-Konten für Arbeitsdateien
- selbst eingerichtete Projektmanagement-Tools
- kostenlose Online-Konverter für vertrauliche Dokumente

Risiken:

- Datenschutzverletzungen
- fehlende Sicherheitskontrolle
- Datenverlust
- Urheberrechtsprobleme
- unklare Speicherung
- keine Löschkonzepte
- kein Zugriff durch Unternehmen

Merksatz:

> Schatten-IT entsteht oft aus Bequemlichkeit, schafft aber große Sicherheitsrisiken.

---

## 12.3 Lieferkettenangriffe

Bei einem Lieferkettenangriff wird nicht direkt das Unternehmen angegriffen, sondern ein Dienstleister oder Softwareanbieter.

Beispiele:

- kompromittiertes Software-Update
- gehackter IT-Dienstleister
- manipulierte Open-Source-Bibliothek
- Angriff über Fernwartungszugang

Mögliche Folgen:

- Angreifer gelangen über vertrauenswürdige Wege ins Unternehmen.
- Schadsoftware wird über Updates verteilt.
- Kundendaten werden bei Dienstleistern kompromittiert.

Schutzmaßnahmen:

- Dienstleister prüfen
- Verträge und Sicherheitsanforderungen
- Zugriff begrenzen
- Monitoring
- Softwarequellen prüfen
- Updates validieren
- Notfallpläne

---

# 13. Bedrohungen durch mobile Arbeit und Homeoffice

Homeoffice und mobile Arbeit erweitern die Unternehmensumgebung.

---

## 13.1 Typische Risiken im Homeoffice

Beispiele:

- unsicheres WLAN
- private Geräte
- Familienmitglieder sehen vertrauliche Informationen
- Ausdrucke liegen offen herum
- fehlender Sichtschutz
- Verlust von Geräten
- Nutzung privater Cloud-Dienste
- schwache Router-Passwörter
- keine sichere VPN-Verbindung

---

## 13.2 Risiken bei mobilen Geräten

Mobile Geräte sind besonders gefährdet, weil sie leicht verloren gehen oder gestohlen werden.

Beispiele:

- Laptop im Zug vergessen
- Smartphone gestohlen
- Tablet ohne Bildschirmsperre
- unverschlüsselte Festplatte
- unsichere Apps
- Verbindung mit öffentlichem WLAN

Schutzmaßnahmen:

- Geräteverschlüsselung
- starke PINs / Passwörter
- biometrische Sperre
- VPN
- Mobile Device Management
- Fernlöschung
- automatische Sperre
- keine sensiblen Daten lokal speichern
- Updates installieren

---

# 14. Bedrohungen durch fehlende Updates und veraltete Systeme

Veraltete Systeme sind ein häufiges Sicherheitsproblem.

---

## 14.1 Warum Updates wichtig sind

Updates schließen Sicherheitslücken und verbessern Stabilität.

Ohne Updates können bekannte Schwachstellen ausgenutzt werden.

Beispiele:

- Betriebssystem ist veraltet.
- Browser hat bekannte Sicherheitslücken.
- Server-Software wird nicht mehr unterstützt.
- Smartphone erhält keine Sicherheitsupdates.
- Router-Firmware ist veraltet.

---

## 14.2 End of Life

End of Life bedeutet:

> Ein Hersteller stellt Unterstützung und Sicherheitsupdates für ein Produkt ein.

Risiken:

- neue Sicherheitslücken werden nicht mehr geschlossen
- Kompatibilitätsprobleme
- keine Herstellerunterstützung
- steigende Angriffsgefahr

Maßnahmen:

- rechtzeitig ersetzen
- Migration planen
- Risiko bewerten
- System isolieren, falls Ersatz nicht sofort möglich ist
- Zugriff beschränken

---

# 15. Bedrohungen durch fehlende oder schlechte Backups

Backups sind entscheidend für die Verfügbarkeit und Wiederherstellung.

---

## 15.1 Risiken ohne Backup

Ohne Backup können folgende Vorfälle kritisch sein:

- Ransomware
- versehentliches Löschen
- Hardwaredefekt
- Datenbankfehler
- Brand
- Diebstahl
- fehlerhaftes Update

Mögliche Folgen:

- dauerhafter Datenverlust
- lange Ausfallzeiten
- Betriebsstillstand
- hohe Wiederherstellungskosten

---

## 15.2 Eigenschaften guter Backups

Gute Backups sollten:

- regelmäßig erstellt werden
- verschlüsselt sein
- getrennt vom Hauptsystem gespeichert werden
- vor Ransomware geschützt sein
- getestet werden
- dokumentiert sein
- schnell wiederherstellbar sein

Wichtig:

> Ein Backup ist nur dann wirklich nützlich, wenn die Wiederherstellung getestet wurde.

---

## 15.3 3-2-1-Regel

Eine bekannte Backup-Regel lautet:

- 3 Kopien der Daten
- 2 unterschiedliche Speichermedien
- 1 Kopie außer Haus oder offline

Beispiel:

> Originaldaten auf dem Server, Backup auf Netzwerkspeicher, zusätzlich offline oder in einer sicheren Cloud.

---

# 16. Bedrohungen durch mangelnde Berechtigungsverwaltung

Berechtigungen bestimmen, wer auf welche Daten und Systeme zugreifen darf.

---

## 16.1 Typische Probleme

- Mitarbeitende haben zu viele Rechte.
- alte Benutzerkonten werden nicht gelöscht.
- geteilte Admin-Konten werden genutzt.
- Passwörter werden weitergegeben.
- externe Dienstleister haben dauerhaften Zugriff.
- Rechte werden nicht regelmäßig überprüft.

---

## 16.2 Least Privilege

Das Prinzip **Least Privilege** bedeutet:

> Jeder Benutzer erhält nur die Rechte, die er für seine Arbeit wirklich benötigt.

Beispiel:

> Ein Praktikant in der Marketingabteilung braucht keinen Zugriff auf Gehaltsdaten.

---

## 16.3 Need-to-know-Prinzip

Das Need-to-know-Prinzip bedeutet:

> Informationen werden nur Personen zugänglich gemacht, die sie wirklich benötigen.

Beispiel:

> Nicht jeder Mitarbeiter darf Kundendaten, Finanzdaten oder Personalakten sehen.

---

# 17. Bedrohungen durch unzureichende Protokollierung

Logs und Protokolle helfen, Sicherheitsvorfälle zu erkennen und nachzuvollziehen.

---

## 17.1 Was sind Logs?

Logs sind automatische Aufzeichnungen von Ereignissen in IT-Systemen.

Beispiele:

- Anmeldeversuche
- fehlgeschlagene Logins
- Änderungen an Berechtigungen
- Zugriff auf Dateien
- Systemfehler
- Netzwerkverbindungen
- Administratoraktionen

---

## 17.2 Risiken ohne Logs

Ohne Protokollierung ist oft unklar:

- wer auf Daten zugegriffen hat
- wann ein Angriff begonnen hat
- welche Systeme betroffen sind
- ob Daten abgeflossen sind
- welche Maßnahmen nötig sind

---

## 17.3 Datenschutz bei Logs

Logs können personenbezogene Daten enthalten, zum Beispiel Benutzernamen oder IP-Adressen.

Deshalb gilt:

- nur notwendige Logs erfassen
- Zweck klar festlegen
- Speicherfristen definieren
- Zugriff beschränken
- keine dauerhafte Mitarbeiterüberwachung ohne Rechtsgrundlage

---

# 18. Risikobehandlung: Was macht man mit erkannten Risiken?

Nachdem Risiken bewertet wurden, muss entschieden werden, wie damit umgegangen wird.

---

## 18.1 Risiko vermeiden

Das Risiko wird beseitigt, indem die riskante Tätigkeit nicht durchgeführt wird.

Beispiel:

> Ein unsicherer Cloud-Dienst wird nicht genutzt.

---

## 18.2 Risiko vermindern

Das Risiko wird durch Maßnahmen reduziert.

Beispiel:

> Phishing-Risiko wird durch Schulungen und Zwei-Faktor-Authentifizierung verringert.

---

## 18.3 Risiko übertragen

Das Risiko wird teilweise auf Dritte übertragen.

Beispiel:

> Abschluss einer Cyberversicherung oder Nutzung eines spezialisierten Dienstleisters.

Wichtig:

> Verantwortung kann nicht vollständig abgegeben werden.

---

## 18.4 Risiko akzeptieren

Ein Risiko wird bewusst akzeptiert, wenn es gering ist oder Maßnahmen unverhältnismäßig wären.

Beispiel:

> Ein kleines Restrisiko bleibt trotz Schutzmaßnahmen bestehen.

Wichtig:

> Risikoakzeptanz sollte bewusst entschieden und dokumentiert werden.

---

# 19. Schutzmaßnahmen gegen Bedrohungen

Schutzmaßnahmen können organisatorisch, technisch oder personell sein.

---

## 19.1 Technische Maßnahmen

Beispiele:

- Firewalls
- Antiviren-Software
- Verschlüsselung
- Backups
- Multi-Faktor-Authentifizierung
- Patch-Management
- Netzwerksegmentierung
- Monitoring
- Mobile Device Management
- Zugriffskontrollen

---

## 19.2 Organisatorische Maßnahmen

Beispiele:

- Sicherheitsrichtlinien
- Notfallpläne
- Berechtigungskonzepte
- Löschkonzepte
- Update-Prozesse
- Freigabeprozesse
- Incident-Response-Prozesse
- Dienstleistermanagement
- Asset-Management

---

## 19.3 Personelle Maßnahmen

Beispiele:

- Schulungen
- Sensibilisierung
- klare Zuständigkeiten
- sichere Onboarding- und Offboarding-Prozesse
- Vertraulichkeitsvereinbarungen
- Sicherheitskultur
- Meldewege für Vorfälle

---

# 20. Beispielhafte vollständige Risikoanalyse

## Beispiel: Mobiler Laptop mit Kundendaten

### Asset

Laptop eines Außendienstmitarbeiters mit Zugriff auf Kundendaten.

### Bedrohungen

- Diebstahl
- Verlust
- Malware
- unsicheres WLAN
- Phishing
- Hardwaredefekt

### Schwachstellen

- keine Festplattenverschlüsselung
- schwaches Passwort
- keine automatische Bildschirmsperre
- keine Fernlöschung
- lokale Speicherung sensibler Daten
- keine VPN-Nutzung

### Betroffene Schutzziele

| Schutzziel | Risiko |
|---|---|
| Vertraulichkeit | Kundendaten können offengelegt werden |
| Integrität | Daten können manipuliert werden |
| Verfügbarkeit | Gerät und Daten sind nicht mehr nutzbar |

### Eintrittswahrscheinlichkeit

mittel bis hoch, weil mobile Geräte leicht verloren gehen können.

### Schadensauswirkung

hoch, wenn Kundendaten betroffen sind.

### Gesamtrisiko

hoch.

### Maßnahmen

- Festplattenverschlüsselung
- starke Authentifizierung
- automatische Sperre
- VPN
- Mobile Device Management
- Fernlöschung
- keine lokale Speicherung sensibler Daten
- regelmäßige Backups
- Schulung des Mitarbeiters

---

# 21. Zweites Beispiel: Öffentlicher Cloud-Speicher

### Asset

Cloud-Speicher mit Projektdokumenten.

### Bedrohungen

- unbefugter Zugriff
- Fehlkonfiguration
- Phishing
- kompromittiertes Benutzerkonto
- Datenverlust beim Anbieter

### Schwachstellen

- öffentliche Freigabelinks
- keine Zwei-Faktor-Authentifizierung
- zu breite Berechtigungen
- keine regelmäßige Rechteprüfung
- keine Klassifizierung der Daten

### Risiken

- vertrauliche Dokumente werden öffentlich
- personenbezogene Daten werden offengelegt
- Geschäftsgeheimnisse gehen verloren
- Datenschutzverletzung
- Imageschaden

### Bewertung

| Kriterium | Einschätzung |
|---|---|
| Eintrittswahrscheinlichkeit | mittel bis hoch |
| Schadensauswirkung | hoch |
| Risiko | hoch |

### Maßnahmen

- MFA aktivieren
- Freigaben regelmäßig prüfen
- öffentliche Links vermeiden
- Berechtigungskonzept
- Datenklassifizierung
- Protokollierung
- Schulungen
- Zugriff nur nach Need-to-know

---

# 22. Typische Klausurfragen mit Antworten

## Frage 1: Was ist eine Bedrohung?

Eine Bedrohung ist ein mögliches Ereignis oder eine Handlung, die Informationen, Systeme oder Prozesse schädigen kann. Beispiele sind Malware, Feuer, Phishing, Stromausfall oder menschliche Fehler.

---

## Frage 2: Was ist ein Risiko?

Ein Risiko ist die Möglichkeit, dass eine Bedrohung eine Schwachstelle ausnutzt und dadurch ein Schaden entsteht. Es wird meist aus Eintrittswahrscheinlichkeit und Schadensauswirkung bewertet.

---

## Frage 3: Was ist eine Schwachstelle?

Eine Schwachstelle ist ein Mangel oder eine Sicherheitslücke, die von einer Bedrohung ausgenutzt werden kann. Beispiele sind veraltete Software, schwache Passwörter oder fehlende Backups.

---

## Frage 4: Was ist der Unterschied zwischen Bedrohung und Schwachstelle?

Eine Bedrohung ist die mögliche Ursache eines Schadens, zum Beispiel ein Hackerangriff. Eine Schwachstelle ist der ausnutzbare Mangel, zum Beispiel eine ungepatchte Sicherheitslücke.

---

## Frage 5: Wie kann man Risiko vereinfacht berechnen?

Vereinfacht gilt:

> Risiko = Eintrittswahrscheinlichkeit × Schadensauswirkung

---

## Frage 6: Nenne vier Bedrohungen für Informationssicherheit.

Beispiele:

- Ransomware
- Phishing
- Feuer
- menschliche Fehler
- Stromausfall
- Softwarefehler
- DDoS-Angriff
- Diebstahl eines Laptops

---

## Frage 7: Welche Schutzziele können durch Bedrohungen beeinträchtigt werden?

Die drei wichtigsten Schutzziele sind:

- Vertraulichkeit
- Integrität
- Verfügbarkeit

---

## Frage 8: Warum ist Asset-Management wichtig?

Asset-Management ist wichtig, weil ein Unternehmen nur schützen kann, was es kennt. Ohne Überblick über Hardware, Software, Daten und Zugriffsrechte bleiben Schwachstellen unentdeckt.

---

## Frage 9: Was ist Phishing?

Phishing ist eine Täuschungsmethode, bei der Angreifer versuchen, Zugangsdaten, Zahlungsinformationen oder andere vertrauliche Informationen zu erhalten oder Schadsoftware zu verbreiten.

---

## Frage 10: Was ist Ransomware?

Ransomware ist Schadsoftware, die Daten oder Systeme verschlüsselt und Lösegeld fordert. Sie gefährdet vor allem die Verfügbarkeit, häufig aber auch Vertraulichkeit und Integrität.

---

## Frage 11: Was ist eine Risikomatrix?

Eine Risikomatrix ist ein Werkzeug zur Bewertung von Risiken. Sie kombiniert Eintrittswahrscheinlichkeit und Schadensauswirkung, um das Risiko einzustufen.

---

## Frage 12: Nenne drei Maßnahmen gegen menschliche Fehler.

Mögliche Maßnahmen sind:

- Schulungen
- Vier-Augen-Prinzip
- klare Arbeitsanweisungen
- Backups
- technische Plausibilitätsprüfungen
- Berechtigungskonzepte

---

## Frage 13: Warum sind missglückte Software-Updates eine Bedrohung?

Missglückte Software-Updates können Systeme unbenutzbar machen, Daten beschädigen oder Sicherheitskonfigurationen verändern. Dadurch können Verfügbarkeit, Integrität und Vertraulichkeit betroffen sein.

---

## Frage 14: Was ist Schatten-IT?

Schatten-IT bezeichnet IT-Lösungen, die ohne Freigabe oder Kontrolle der IT-Abteilung genutzt werden, zum Beispiel private Cloudspeicher oder nicht genehmigte Online-Tools.

---

## Frage 15: Was bedeutet Restrisiko?

Restrisiko ist das Risiko, das trotz umgesetzter Schutzmaßnahmen verbleibt. Es kann akzeptiert werden, wenn es bewusst bewertet und dokumentiert wurde.

---

# 23. Kurze Merksätze

- **Was man nicht kennt, kann man nicht schützen.**
- **Eine Bedrohung kann Schaden verursachen.**
- **Eine Schwachstelle ermöglicht oder erleichtert den Schaden.**
- **Ein Risiko entsteht, wenn Bedrohung und Schwachstelle zusammenkommen.**
- **Risiko = Eintrittswahrscheinlichkeit × Schadensauswirkung.**
- **Phishing zielt auf Menschen.**
- **Ransomware gefährdet oft Verfügbarkeit, Integrität und Vertraulichkeit gleichzeitig.**
- **Backups helfen nur, wenn sie getestet wurden.**
- **Updates schließen Sicherheitslücken, müssen aber kontrolliert durchgeführt werden.**
- **Menschliche Fehler sind eine der häufigsten Ursachen für Sicherheitsvorfälle.**
- **Homeoffice und mobile Geräte erweitern die Angriffsfläche.**
- **Schatten-IT ist bequem, aber gefährlich.**
- **Least Privilege bedeutet: nur die Rechte, die wirklich nötig sind.**
- **Restrisiko bleibt fast immer bestehen.**

---

# 24. Mini-Zusammenfassung für direkt vor der Klausur

Bedrohungen sind mögliche Ereignisse oder Handlungen, die Informationen, Systeme oder Prozesse schädigen können. Beispiele sind Phishing, Ransomware, Naturkatastrophen, Stromausfälle, menschliche Fehler oder missglückte Software-Updates. Schwachstellen sind Mängel, die von Bedrohungen ausgenutzt werden können, zum Beispiel veraltete Software, schwache Passwörter, fehlende Backups oder falsche Berechtigungen. Ein Risiko entsteht, wenn eine Bedrohung auf eine Schwachstelle trifft und dadurch ein Schaden möglich wird. Risiken werden meist anhand von Eintrittswahrscheinlichkeit und Schadensauswirkung bewertet. Die wichtigsten Schutzziele sind Vertraulichkeit, Integrität und Verfügbarkeit. Unternehmen müssen ihre Hardware, Software, Daten und Zugriffsrechte kennen, um Bedrohungen richtig bewerten und geeignete Schutzmaßnahmen ableiten zu können.