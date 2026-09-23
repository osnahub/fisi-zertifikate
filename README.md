# FiSi-Zertifikate

## Praxisguide für sinnvolle IT-Zertifizierungen in der Systemintegration

Herstellerzertifikate können eine Ausbildung oder Umschulung zum **Fachinformatiker für Systemintegration (FiSi)** sinnvoll ergänzen. Entscheidend ist allerdings nicht die Zahl der Badges im Lebenslauf, sondern ob ein Nachweis zum eigenen Tätigkeitsfeld passt und Kenntnisse bestätigt, die im späteren Berufsalltag tatsächlich gebraucht werden.

Dieser Guide ordnet verbreitete Zertifizierungen und Lernnachweise nach ihrem Nutzen für typische FiSi-Themen ein: **Netzwerke, Windows Server und Active Directory, Linux, Cloud, IT-Sicherheit, Endpoint-Management, Backup und IT-Service-Management**.

Die IHK-Abschlussprüfung bleibt dabei die zentrale Qualifikation. Herstellerzertifikate sind eine Ergänzung – kein Ersatz für praktische Erfahrung, Homelabs, Projekte und solides Grundlagenwissen.

> **Stand: 23. September 2026**  
> Prüfungsprogramme, Preise und Gültigkeitsregeln ändern sich. Vor einer Buchung sollte deshalb immer die verlinkte Herstellerseite geprüft werden.

---

## Inhaltsverzeichnis

- [1. Zertifikat ist nicht gleich Zertifikat](#1-zertifikat-ist-nicht-gleich-zertifikat)
- [2. Schnellübersicht](#2-schnellübersicht)
- [3. Kostenlose Nachweise](#3-kostenlose-nachweise)
- [4. Netzwerk](#4-netzwerk)
- [5. Windows Server, Microsoft 365 und Azure](#5-windows-server-microsoft-365-und-azure)
- [6. Linux und Open Source](#6-linux-und-open-source)
- [7. IT-Sicherheit und Firewalls](#7-it-sicherheit-und-firewalls)
- [8. AWS und Google Cloud](#8-aws-und-google-cloud)
- [9. Backup und Virtualisierung](#9-backup-und-virtualisierung)
- [10. IT-Service-Management](#10-it-service-management)
- [11. CompTIA](#11-comptia)
- [12. Welche Zertifikate lohnen sich wann?](#12-welche-zertifikate-lohnen-sich-wann)
- [13. Sinnvolle Zertifizierungspfade](#13-sinnvolle-zertifizierungspfade)
- [14. Was eher nicht sinnvoll ist](#14-was-eher-nicht-sinnvoll-ist)
- [15. Ein realistischer Kernpfad für FiSi](#15-ein-realistischer-kernpfad-für-fisi)
- [16. Quellen und Herstellerseiten](#16-quellen-und-herstellerseiten)

---

# 1. Zertifikat ist nicht gleich Zertifikat

Im IT-Umfeld werden sehr unterschiedliche Nachweise unter dem Begriff „Zertifikat“ zusammengefasst. Für die Einordnung im Lebenslauf sollte man unterscheiden.

### Herstellerzertifizierung

Eine Herstellerzertifizierung wird nach einer formalen Prüfung vergeben. Beispiele sind **Cisco CCNA**, **Microsoft AZ-104** oder **LPIC-1**. Die Prüfung findet je nach Anbieter beaufsichtigt in einem Testcenter, per Online-Proctoring oder als praktische Laborprüfung statt.

Solche Zertifizierungen haben in der Regel die höchste Aussagekraft.

### Praxisbasierter Leistungsnachweis

Ein Beispiel sind die **Microsoft Applied Skills**. Dabei wird eine konkrete Aufgabe in einer bereitgestellten Laborumgebung gelöst. Der Umfang ist kleiner als bei einer vollständigen rollenbasierten Zertifizierung, dafür wird praktisches Arbeiten geprüft.

Für angehende Systemadministratoren sind solche Nachweise interessant, weil sie konkrete Tätigkeiten dokumentieren und nicht nur theoretisches Wissen.

### Digital Badge oder Kursnachweis

Cisco Networking Academy, Microsoft Learn und andere Anbieter vergeben für erfolgreich abgeschlossene Lernpfade digitale Badges oder Kursnachweise.

Diese können im Lebenslauf oder auf LinkedIn sinnvoll sein. Sie sollten aber nicht mit einer beaufsichtigten Herstellerzertifizierung gleichgesetzt werden.

### Teilnahmebescheinigung

Eine Teilnahmebescheinigung bestätigt zunächst nur die Teilnahme an einer Schulung. Ob eine Prüfung stattgefunden hat und welches Niveau erreicht wurde, ist daraus nicht automatisch ersichtlich.

---

# 2. Schnellübersicht

Die folgende Tabelle ist bewusst auf Zertifikate beschränkt, die für typische Tätigkeiten in der Systemintegration einen nachvollziehbaren Bezug haben.

| Nachweis | Schwerpunkt | Kosten* | Gültigkeit | Einordnung |
|---|---|---:|---|---|
| Microsoft Applied Skills: AD DS | Windows Server / Active Directory | kostenlos | kein regulärer Ablauf | sehr sinnvoll |
| Microsoft Applied Skills: Entra | Identity / Cloud | kostenlos | kein regulärer Ablauf | sinnvoll |
| Cisco Networking Academy | Netzwerk / Security | kostenlos | Kurs-/Badge-Nachweis | sehr guter Einstieg |
| Fortinet NSE 1–3 | Security / Firewall | kostenloser Einstieg | 2 Jahre | sinnvoll |
| Cisco CCST Networking | Netzwerk | 125 USD | 5 Jahre | sehr sinnvoll |
| Microsoft AZ-900 | Azure / Cloud | 76 EUR | läuft nicht ab | sinnvoll |
| Microsoft SC-900 | Security / Identity | 76 EUR | läuft nicht ab | sinnvoll |
| LPI Linux Essentials | Linux | 110 EUR | lebenslang | sehr sinnvoll |
| LPI Security Essentials | Security | 110 EUR | lebenslang | sinnvoll |
| Microsoft AZ-802 | Windows Server | 126 EUR | 1 Jahr, kostenlos verlängerbar | sehr sinnvoll |
| Microsoft MD-102 | Endpoint / Intune | 126 EUR | 1 Jahr, kostenlos verlängerbar | sinnvoll bei Client-Fokus |
| Microsoft AZ-104 | Azure-Administration | 126 EUR | 1 Jahr, kostenlos verlängerbar | sinnvoll bei Cloud-Fokus |
| Microsoft SC-300 | Entra / Identity | 126 EUR | 1 Jahr, kostenlos verlängerbar | sinnvoll bei Identity-Fokus |
| LPIC-1 | Linux-Administration | 2 × 176 EUR | 5 Jahre | sehr sinnvoll bei Linux-Fokus |
| Cisco CCNA | Netzwerk | 300 USD | 3 Jahre | sehr wertvoll, anspruchsvoll |
| AWS Cloud Practitioner | AWS / Cloud | 100 USD | 3 Jahre | optional |
| AWS Solutions Architect – Associate | AWS / Cloud | 150 USD | 3 Jahre | sinnvoll bei AWS-Fokus |
| Google Associate Cloud Engineer | Google Cloud | 125 USD | 3 Jahre | optional |
| Linux Foundation LFCS | Linux-Administration | 445 USD | 2 Jahre | stark, aber teuer |
| Red Hat RHCSA | Enterprise Linux | regional | nach Red-Hat-Regeln | stark, praxisorientiert |
| Veeam VMCE+ | Backup / Recovery | Schulung + Prüfung | herstellerabhängig | später bei Veeam-Fokus |
| ITIL Foundation (Version 5) | IT-Service-Management | ab 690 USD im Direktbundle | 3 Jahre | optional |

\* Listenpreise laut Herstellerstand zum angegebenen Datum. Steuern, Wechselkurse, Bildungsrabatte, Voucher und regionale Preise können zu Abweichungen führen.

---

# 3. Kostenlose Nachweise

## Microsoft Applied Skills: Administer Active Directory Domain Services

**Bereich:** Windows Server, Active Directory  
**Kosten:** kostenlos  
**Prüfungsart:** interaktives Assessment-Lab

Dieser Nachweis gehört zu den interessantesten kostenlosen Credentials für angehende Fachinformatiker für Systemintegration.

Geprüft werden unter anderem:

- Bereitstellung und Verwaltung von Domain Controllern
- Active-Directory-Topologie
- Benutzer, Gruppen und weitere AD-Objekte
- Gruppenrichtlinien
- Sicherheitskonfiguration von AD DS

Die Bewertung erfolgt in einer interaktiven Laborumgebung und damit näher an realen Administrationsaufgaben als bei einem reinen Wissensquiz.

**Einordnung:** Klare Empfehlung, sobald grundlegende Kenntnisse in Windows Server, Netzwerken und PowerShell vorhanden sind.

Offizielle Seite:  
https://learn.microsoft.com/de-de/credentials/applied-skills/administer-active-directory-domain-services/

---

## Microsoft Applied Skills: Get started with identities and access using Microsoft Entra

**Bereich:** Microsoft Entra ID, Identity and Access Management  
**Kosten:** kostenlos  
**Prüfungsart:** interaktives Assessment-Lab  
**Prüfungssprache:** derzeit Englisch

Inhalte sind unter anderem:

- Benutzerverwaltung
- Gruppenverwaltung
- Kennwortschutz
- Self-Service Password Reset
- Multifaktor-Authentifizierung
- Conditional Access

Der Nachweis ergänzt klassisches Active Directory um moderne Cloud-Identitäten.

**Einordnung:** Gute Ergänzung zum AD-DS-Nachweis, insbesondere für Unternehmen mit Microsoft 365 und hybriden Identitätsumgebungen.

Offizielle Seite:  
https://learn.microsoft.com/de-de/credentials/applied-skills/get-started-with-identities-and-access-using-microsoft-entra/

---

## Cisco Networking Academy

Cisco bietet über die Networking Academy kostenlose Self-Paced-Kurse an.

Für FiSi besonders interessant sind:

- Networking Basics
- Networking Devices and Initial Configuration
- Network Addressing and Basic Troubleshooting
- Network Support and Security
- Introduction to Cybersecurity
- Ethical Hacker

Einige Kurse vergeben nach erfolgreichem Abschluss digitale Cisco-Badges. Dabei handelt es sich um Lernnachweise, nicht um eine CCST- oder CCNA-Zertifizierung.

Der große praktische Vorteil ist die Verbindung mit **Cisco Packet Tracer**. Netzwerke können aufgebaut, adressiert, konfiguriert und getestet werden, ohne physische Cisco-Hardware zu besitzen.

**Einordnung:** Sehr gute kostenlose Vorbereitung auf CCST Networking und später CCNA.

Offizielle Seite:  
https://www.cisco.com/site/us/en/learn/training-certifications/training/netacad/index.html

---

## Fortinet NSE 1, NSE 2 und NSE 3

Fortinet hat sein Zertifizierungsprogramm zum **15. Juli 2026** wieder auf die Bezeichnungen **NSE 1 bis NSE 8** umgestellt.

Für Einsteiger sind insbesondere relevant:

### NSE 1 in Cybersecurity

Grundlagen zu Cybersecurity und Cloud.

### NSE 2 in Cybersecurity

Einführung in Next Generation Firewalls.

### NSE 3 in Cybersecurity

FortiGate Operator. Hier geht es bereits stärker um die praktische Bedienung und Administration von FortiGate-Systemen.

Die Self-Paced-Kurse NSE 1 bis NSE 3 sind frei zugänglich. Fortinet führt für diese Stufen keine gesonderten Exam-Voucher-SKUs; die Onlineprüfungen werden über das Fortinet Training Institute abgelegt. Die Zertifizierungen dieser Stufen sind jeweils zwei Jahre aktiv.

**Einordnung:** Besonders interessant für FiSi, die sich mit Firewalls, Netzwerksecurity oder später mit FortiGate beschäftigen möchten.

Offizielle Seiten:

- https://www.fortinet.com/de/training-certification
- https://training.fortinet.com/local/staticpage/view.php?page=nse_1
- https://training.fortinet.com/local/staticpage/view.php?page=nse_2
- https://training.fortinet.com/local/staticpage/view.php?page=nse_3

---

# 4. Netzwerk

## Cisco Certified Support Technician Networking – CCST Networking

**Kosten:** 125 USD  
**Voraussetzungen:** keine  
**Gültigkeit:** 5 Jahre

CCST Networking ist die Einsteigerzertifizierung von Cisco und fachlich näher an der Systemintegration als viele allgemeine IT-Einstiegszertifikate.

Typische Themen:

- Netzwerkgrundlagen
- IPv4 und IPv6
- Switching- und Routing-Grundlagen
- WLAN
- Endgeräte
- Diagnose und Troubleshooting
- grundlegende Sicherheitskonzepte

Cisco positioniert CCST unterhalb des CCNA.

**Für wen geeignet?**  
Für Auszubildende, Umschüler und Berufseinsteiger, die einen ersten formalen Netzwerknachweis erwerben möchten.

**Einordnung:** Eines der sinnvollsten ersten kostenpflichtigen Zertifikate für FiSi.

Offizielle Seite:  
https://www.cisco.com/site/us/en/learn/training-certifications/certifications/support-technician/index.html

---

## Cisco Certified Network Associate – CCNA

**Prüfung:** 200-301 CCNA  
**Kosten:** 300 USD  
**Prüfungsdauer:** 120 Minuten  
**Gültigkeit:** 3 Jahre

Der CCNA geht deutlich über Einstiegswissen hinaus.

Geprüft werden unter anderem:

- Network Fundamentals
- Network Access
- IP Connectivity
- IP Services
- Security Fundamentals
- Automation and Programmability

Subnetting, VLANs, Routing, Switching und Fehleranalyse spielen entsprechend eine große Rolle.

**Für wen geeignet?**  
Für FiSi, die Netzwerkadministration ernsthaft vertiefen oder sich später in Richtung Network Administrator, Network Engineer oder Netzwerksicherheit entwickeln möchten.

**Einordnung:** Fachlich sehr wertvoll, aber kein Zertifikat für „nebenbei“. Ohne praktische Übungen mit Packet Tracer, GNS3, EVE-NG oder echter Hardware ist die Vorbereitung wenig sinnvoll.

Offizielle Seite:  
https://www.cisco.com/site/us/en/learn/training-certifications/exams/ccna.html

---

# 5. Windows Server, Microsoft 365 und Azure

## Microsoft Certified: Azure Fundamentals – AZ-900

**Kosten in Deutschland:** 76 EUR  
**Gültigkeit:** läuft nicht ab  
**Niveau:** Fundamentals

Themen:

- Cloud-Konzepte
- Azure-Architektur
- Compute
- Netzwerk
- Storage
- Sicherheit und Governance
- Azure-Verwaltung

AZ-900 ist keine Administratorprüfung. Sie bestätigt Grundlagenwissen über Azure.

**Einordnung:** Sinnvoll als Cloud-Einstieg, insbesondere weil Azure in Microsoft-geprägten Unternehmensumgebungen häufig eine Rolle spielt.

Offizielle Seite:  
https://learn.microsoft.com/de-de/credentials/certifications/azure-fundamentals/

---

## Microsoft Certified: Security, Compliance, and Identity Fundamentals – SC-900

**Kosten in Deutschland:** 76 EUR  
**Gültigkeit:** läuft nicht ab  
**Niveau:** Fundamentals

Themen:

- Sicherheitsgrundlagen
- Zero Trust
- Microsoft Entra
- Authentifizierung und Identitäten
- Microsoft-Sicherheitslösungen
- Compliance

**Einordnung:** Für FiSi häufig interessanter als ein weiteres allgemeines Cloud-Grundlagenzertifikat, wenn bereits erste Microsoft-365- oder Azure-Kenntnisse vorhanden sind.

Offizielle Seite:  
https://learn.microsoft.com/de-de/credentials/certifications/security-compliance-and-identity-fundamentals/

---

## Microsoft Certified: Windows Server Administrator Associate – AZ-802

**Kosten in Deutschland:** 126 EUR  
**Prüfungsdauer:** 120 Minuten  
**Prüfungssprache:** derzeit Englisch  
**Gültigkeit:** rollenbasierte Microsoft-Zertifizierung; jährlich kostenlos verlängerbar

Microsoft stellt die bisherigen Prüfungen **AZ-800 und AZ-801 am 30. September 2026 ein**. Der neue Prüfungsweg läuft über **AZ-802**.

Geprüft werden:

- Active Directory Domain Services
- Windows Server in hybriden Umgebungen
- virtuelle Maschinen
- lokale und hybride Netzwerkinfrastruktur
- Storage und File Services
- Absicherung von Windows Server
- Monitoring und Troubleshooting

**Einordnung:** Inhaltlich eine der passendsten Microsoft-Zertifizierungen für Fachinformatiker Systemintegration.

Für Anfänger ist sie allerdings nicht der erste Schritt. Sinnvoll ist zunächst praktische Erfahrung mit Windows Server, AD DS, DNS, DHCP, Gruppenrichtlinien, Dateidiensten und einer eigenen Lab-Umgebung.

Offizielle Seite:  
https://learn.microsoft.com/de-de/credentials/certifications/windows-server-administrator-associate/

---

## Microsoft 365 Certified: Endpoint Administrator Associate – MD-102

**Kosten in Deutschland:** 126 EUR  
**Gültigkeit:** 1 Jahr, kostenlos über Microsoft Learn verlängerbar  
**Prüfungssprachen:** unter anderem Deutsch und Englisch

MD-102 ist für moderne Client- und Endpoint-Verwaltung interessant.

Aktuelle Schwerpunkte sind unter anderem:

- Gerätebereitstellung
- Microsoft Intune
- Windows Autopilot
- Richtlinien und Updates
- Anwendungen
- Endpoint Security
- Microsoft Defender for Endpoint
- Entra ID
- PowerShell und Automatisierung

**Einordnung:** Sehr sinnvoll für FiSi mit Schwerpunkt Workplace, Client-Management, Intune oder Microsoft 365. Für klassische Netzwerk- oder Serveradministration ist AZ-802 meist näher am Kernprofil.

Offizielle Seite:  
https://learn.microsoft.com/de-de/credentials/certifications/modern-desktop/

---

## Microsoft Certified: Azure Administrator Associate – AZ-104

**Kosten in Deutschland:** 126 EUR  
**Gültigkeit:** 1 Jahr, kostenlos über Microsoft Learn verlängerbar

AZ-104 ist die eigentliche Administratorzertifizierung für Azure.

Themen sind unter anderem:

- Azure-Identitäten und Governance
- Storage
- Compute
- virtuelle Netzwerke
- Monitoring
- Verwaltung von Azure-Ressourcen

**Einordnung:** Deutlich technischer und aussagekräftiger als AZ-900. Sinnvoll, wenn Cloud-Administration tatsächlich Teil des gewünschten Berufsprofils werden soll.

Offizielle Seite:  
https://learn.microsoft.com/de-de/credentials/certifications/azure-administrator/

---

## Microsoft Certified: Identity and Access Administrator Associate – SC-300

**Kosten in Deutschland:** 126 EUR  
**Gültigkeit:** 1 Jahr, kostenlos verlängerbar

SC-300 konzentriert sich auf Identitäten und Zugriffssteuerung mit Microsoft Entra.

Dazu gehören beispielsweise:

- Identity Lifecycle
- Authentifizierung
- Conditional Access
- Identity Governance
- Zugriff auf Anwendungen und Ressourcen

**Einordnung:** Gute Spezialisierung für Microsoft-365-, Entra- und hybride AD-Umgebungen. Für einen allgemeinen FiSi-Weg kein Pflichtzertifikat.

Offizielle Seite:  
https://learn.microsoft.com/de-de/credentials/certifications/identity-and-access-administrator/

---

# 6. Linux und Open Source

## LPI Linux Essentials

**Prüfung:** 010  
**Kosten:** 110 EUR  
**Prüfung:** 40 Fragen / 60 Minuten  
**Sprachen:** unter anderem Deutsch  
**Gültigkeit:** lebenslang

Linux Essentials behandelt:

- Linux und Open Source
- Kommandozeile
- Dateien und Verzeichnisse
- Benutzer und Gruppen
- Berechtigungen
- Prozesse
- grundlegende Administration

**Einordnung:** Sehr guter erster formaler Linux-Nachweis während Ausbildung oder Umschulung.

Offizielle Seite:  
https://www.lpi.org/de/our-certifications/linux-essentials-overview/

---

## LPIC-1

**Prüfungen:** 101 und 102  
**Kosten:** jeweils 176 EUR, insgesamt 352 EUR  
**Gültigkeit:** 5 Jahre

LPIC-1 geht wesentlich weiter als Linux Essentials.

Inhalte sind unter anderem:

- Systemarchitektur
- Linux-Installation
- Paketverwaltung
- GNU- und Unix-Kommandos
- Dateisysteme
- Shells und Skripting
- Benutzerverwaltung
- grundlegendes Networking
- Systemdienste
- Sicherheit

**Einordnung:** Einer der sinnvollsten herstellerneutralen Linux-Nachweise für angehende Systemadministratoren.

Offizielle Seite:  
https://www.lpi.org/de/our-certifications/lpic-1-overview/

---

## Linux Foundation Certified System Administrator – LFCS

**Kosten:** 445 USD  
**Prüfungsart:** praktische, performancebasierte Prüfung  
**Prüfungsdauer:** 2 Stunden  
**Gültigkeit:** 2 Jahre

Der LFCS prüft nicht nur theoretisches Wissen. Aufgaben müssen direkt auf einem Linux-System gelöst werden. Im Prüfungspaket sind derzeit zwei Prüfungsversuche und ein Exam-Simulator enthalten.

**Einordnung:** Fachlich stark, aber für Auszubildende und Umschüler aufgrund des Preises meist erst nach soliden Linux-Grundlagen interessant.

Offizielle Seite:  
https://training.linuxfoundation.org/certification/linux-foundation-certified-sysadmin-lfcs/

---

## Red Hat Certified System Administrator – RHCSA

**Prüfung:** EX200  
**Basis:** Red Hat Enterprise Linux 10  
**Prüfungsart:** praktische Prüfung  
**Preis:** regional; bei Red Hat beziehungsweise einem Trainingspartner prüfen

Der RHCSA prüft reale Administrationsaufgaben. Dazu gehören unter anderem:

- Benutzer und Gruppen
- Storage und Dateisysteme
- Dienste und Prozesse
- SSH
- Firewall
- SELinux
- Pakete
- Berechtigungen
- grundlegende Containerverwaltung

**Einordnung:** Sehr guter Nachweis für Enterprise-Linux-Umgebungen. Für einen allgemeinen FiSi-Einstieg meist zu spezialisiert; bei Linux-Schwerpunkt dagegen sehr interessant.

Offizielle Seite:  
https://www.redhat.com/de/services/training/ex200-red-hat-certified-system-administrator-rhcsa-exam

---

# 7. IT-Sicherheit und Firewalls

## LPI Security Essentials

**Prüfung:** 020  
**Kosten:** 110 EUR  
**Prüfung:** 40 Fragen / 60 Minuten  
**Gültigkeit:** lebenslang

Themen:

- Security-Grundlagen
- Kryptografie
- Geräte- und Speichersicherheit
- Netzwerk- und Service-Sicherheit
- Identität und Datenschutz

**Einordnung:** Preislich überschaubarer Security-Einstieg. Technisch weniger tief als fortgeschrittene Security-Zertifizierungen, für Einsteiger aber gut strukturiert.

Offizielle Seite:  
https://www.lpi.org/de/our-certifications/security-essentials-overview/

---

## Fortinet NSE

Für Systemintegratoren mit Netzwerk- und Firewall-Fokus ist Fortinet besonders interessant, wenn FortiGate im Ausbildungs-, Praktikums- oder späteren Arbeitgeberumfeld eingesetzt wird.

Ein sinnvoller Aufbau kann sein:

**NSE 1 → NSE 2 → NSE 3 → später NSE 4**

Ab NSE 4 geht es deutlich stärker um technische Administration und beaufsichtigte Prüfungen.

**Einordnung:** Gute herstellerspezifische Ergänzung zu einem soliden Netzwerkfundament. Ohne Netzwerkgrundlagen sollte Fortinet nicht an die Stelle von TCP/IP, VLANs, Routing und Troubleshooting treten.

---

# 8. AWS und Google Cloud

Cloud-Zertifikate sind dann sinnvoll, wenn die jeweilige Plattform praktisch genutzt wird. Für Berufseinsteiger bringt es wenig, gleichzeitig Azure, AWS und Google Cloud nur auf Fundamentals-Niveau abzudecken.

## AWS Certified Cloud Practitioner

**Kosten:** 100 USD  
**Niveau:** Grundlagen  
**Gültigkeit:** 3 Jahre

Cloud Practitioner bestätigt ein grundlegendes Verständnis von AWS, Cloud-Konzepten, Services, Security und Abrechnung.

**Einordnung:** Sinnvoll bei AWS-Bezug. Ohne diesen Bezug ist eine Microsoft-Zertifizierung in vielen Windows-geprägten FiSi-Umgebungen häufig näher am späteren Alltag.

Offizielle Seite:  
https://aws.amazon.com/certification/certified-cloud-practitioner/

---

## AWS Certified Solutions Architect – Associate

**Kosten:** 150 USD  
**Prüfungsdauer:** 130 Minuten  
**Gültigkeit:** 3 Jahre

Die Prüfung beschäftigt sich mit dem Entwurf sicherer, zuverlässiger, leistungsfähiger und kostenoptimierter AWS-Lösungen.

**Einordnung:** Deutlich aussagekräftiger als Cloud Practitioner, aber eher nach erster praktischer AWS-Erfahrung.

Offizielle Seite:  
https://aws.amazon.com/de/certification/certified-solutions-architect-associate/

---

## Google Associate Cloud Engineer

**Kosten:** 125 USD zuzüglich gegebenenfalls anfallender Steuern  
**Prüfungsdauer:** 2 Stunden  
**Gültigkeit:** 3 Jahre  
**Herstellerempfehlung:** mindestens sechs Monate praktische Google-Cloud-Erfahrung

**Einordnung:** Gute technische Cloud-Zertifizierung, wenn Google Cloud tatsächlich eingesetzt wird. Für einen allgemeinen FiSi-Lernpfad kein Muss.

Offizielle Seite:  
https://cloud.google.com/learn/certification/cloud-engineer?hl=de

---

# 9. Backup und Virtualisierung

## Veeam University

Veeam stellt mit **Veeam University FREE** kostenfreie On-Demand-Inhalte für Anwender bereit.

Das ist kein Ersatz für eine formale Veeam-Zertifizierung, aber eine sinnvolle Möglichkeit, Backup- und Recovery-Themen herstellernah kennenzulernen.

Offizielle Seite:  
https://www.veeam.com/support/training.html

---

## Veeam Certified Engineer+ – VMCE+

Veeam hat sein Zertifizierungsprogramm 2026 umgestellt. Die aktuelle technische Engineer-Zertifizierung ist **VMCE+**.

Sie richtet sich an Administratoren und Engineers, die mit der Veeam Data Platform arbeiten. Zum Zertifizierungsweg gehören offizielle Trainings und eine beaufsichtigte Prüfung. Inhaltlich spielen unter anderem Backup & Replication, Monitoring und Orchestrierung eine Rolle.

**Einordnung:** Für einen Berufseinsteiger nur dann sinnvoll, wenn Veeam praktisch eingesetzt wird und der Arbeitgeber oder Bildungsträger die erforderlichen Trainings unterstützt. Als allgemeines Einstiegszertifikat ist VMCE+ zu spezialisiert.

Offizielle Seite:  
https://www.veeam.com/support/training/vmce-certification.html

---

## Virtualisierungszertifikate allgemein

Virtualisierung gehört zum FiSi-Alltag, aber ein allgemeingültiges „Pflichtzertifikat“ gibt es hier nicht.

Für den Einstieg ist praktische Erfahrung meist wertvoller:

- Hyper-V
- VMware vSphere
- Proxmox VE
- VirtualBox für Lernumgebungen
- virtuelle Netzwerke und Storage
- Snapshots, Templates und Backups

Eine herstellerspezifische Zertifizierung lohnt sich vor allem dann, wenn die jeweilige Plattform im Betrieb tatsächlich eingesetzt wird.

---

# 10. IT-Service-Management

## ITIL Foundation (Version 5)

**Prüfung:** 40 Multiple-Choice-Fragen  
**Prüfungsdauer:** 60 Minuten  
**Bestehensgrenze:** 65 Prozent  
**Sprachen:** unter anderem Deutsch  
**Gültigkeit:** 3 Jahre  
**Direktkauf bei PeopleCert:** derzeit ab 690 USD im Exam-Bundle

ITIL ist keine technische Administratorzertifizierung. Behandelt werden Strukturen und Grundbegriffe des IT-Service-Managements, beispielsweise Wertschöpfung, kontinuierliche Verbesserung und die Organisation digitaler Produkte und Services.

**Einordnung:** Optional. Sinnvoll, wenn der spätere Arbeitgeber stark nach ITIL arbeitet, wenn Service Desk, IT Operations oder Prozessmanagement eine größere Rolle spielen oder der Arbeitgeber die Kosten übernimmt. Für einen FiSi mit begrenztem Zertifizierungsbudget haben Netzwerk-, Server-, Linux- oder Cloud-Zertifikate zunächst meist einen höheren technischen Mehrwert.

Offizielle Seite:  
https://www.peoplecert.org/browse-certifications/it-governance-and-service-management/ITIL-1/itil-5-foundation-version-50-4154

---

# 11. CompTIA

CompTIA bietet herstellerneutrale Zertifizierungen, die insbesondere international und im US-amerikanischen Arbeitsmarkt verbreitet sind.

Für Systemintegration relevant sind vor allem:

- **CompTIA A+** – Hardware, Betriebssysteme und IT-Support
- **CompTIA Network+** – Netzwerke
- **CompTIA Security+** – IT-Sicherheit
- **CompTIA Server+** – Serveradministration
- **CompTIA Linux+** – Linux

In Deutschland sollte der Nutzen gegen die vergleichsweise hohen Prüfungskosten abgewogen werden.

Wer bereits eine IHK-Ausbildung oder -Umschulung zum Fachinformatiker absolviert, gewinnt mit einem spezialisierten Nachweis wie **CCST/CCNA, LPIC-1 oder einer Microsoft-Administratorzertifizierung** häufig mehr zusätzliche Aussagekraft als mit A+.

Network+ kann sinnvoll sein, wenn ausdrücklich ein herstellerneutraler Netzwerknachweis gesucht wird. Security+ ist international bekannt und kann bei einem späteren Security-Schwerpunkt interessant werden.

Da CompTIA Preise und Bundles regional vermarktet, sollten die aktuellen Kosten unmittelbar vor der Buchung im offiziellen Store geprüft werden.

Offizielle Übersicht:  
https://www.comptia.org/certifications

---

# 12. Welche Zertifikate lohnen sich wann?

## Zu Beginn der Ausbildung oder Umschulung

Zunächst sollten Grundlagen gefestigt und praktische Erfahrung aufgebaut werden.

Sinnvoll sind:

1. Cisco Networking Academy
2. Microsoft Applied Skills: Active Directory Domain Services
3. Fortinet NSE 1 und NSE 2
4. Linux Essentials
5. gegebenenfalls AZ-900 oder SC-900

Damit lässt sich mit überschaubaren Kosten ein nachvollziehbares Grundlagenprofil aufbauen.

---

## Nach soliden Netzwerkgrundlagen

Dann bietet sich **CCST Networking** an.

Der Schritt zum **CCNA** sollte erst erfolgen, wenn Subnetting, VLANs, Switching, Routing, IPv4/IPv6 und Troubleshooting nicht nur theoretisch bekannt sind, sondern regelmäßig praktisch geübt wurden.

---

## Nach soliden Windows-Server-Kenntnissen

Dann ist **AZ-802 Windows Server Administrator Associate** besonders interessant.

Vorher sollte man mindestens selbstständig mit folgenden Themen gearbeitet haben:

- Domain Controller
- AD DS
- DNS
- DHCP
- Gruppenrichtlinien
- Benutzer- und Gruppenverwaltung
- Dateifreigaben und NTFS-Berechtigungen
- PowerShell-Grundlagen
- Virtualisierung
- grundlegendes Troubleshooting

---

## Bei Client- und Workplace-Schwerpunkt

Dann passt **MD-102** besser als eine klassische Serverzertifizierung.

Praktische Vorkenntnisse in Intune, Entra ID, Windows Autopilot, Richtlinien, Softwareverteilung und Endpoint Security sind dafür deutlich nützlicher als reines Auswendiglernen.

---

## Bei Linux-Schwerpunkt

Ein sinnvoller Aufbau ist:

**Linux Essentials → LPIC-1 → LFCS oder RHCSA**

LPIC-1 ist herstellerneutral und breit angelegt. LFCS und RHCSA prüfen stärker das tatsächliche Arbeiten am System.

---

## Bei Cloud-Schwerpunkt

Nicht alle Plattformen parallel beginnen.

Ein sinnvoller Microsoft-Weg kann sein:

**AZ-900 → praktische Azure-Labs → AZ-104**

Bei AWS:

**Cloud Practitioner – optional → praktische AWS-Labs → Solutions Architect Associate**

Cloud-Grundlagenzertifikate sind dann am wertvollsten, wenn anschließend praktische Administration folgt.

---

# 13. Sinnvolle Zertifizierungspfade

Es ist nicht notwendig, jeden Pfad vollständig abzuarbeiten.

## FiSi-Generalist

1. Cisco Networking Academy
2. Microsoft Applied Skills: AD DS
3. CCST Networking
4. Linux Essentials
5. AZ-900 oder SC-900
6. AZ-802

Dieser Weg deckt Netzwerk, Windows, Linux, Cloud und Security ab, ohne früh zu stark zu spezialisieren.

---

## Netzwerk und Firewall

1. Cisco Networking Academy
2. CCST Networking
3. Fortinet NSE 1–3
4. CCNA
5. später Fortinet NSE 4 oder eine andere Firewall-Spezialisierung

---

## Windows Server und Microsoft Cloud

1. Microsoft Applied Skills: AD DS
2. Microsoft Applied Skills: Entra
3. AZ-900
4. SC-900
5. AZ-802
6. AZ-104
7. optional SC-300

---

## Modern Workplace und Endpoint Management

1. Microsoft Applied Skills: Entra
2. SC-900
3. praktische Intune-/Autopilot-Labs
4. MD-102
5. optional SC-300

---

## Linux-Systemadministration

1. Linux Essentials
2. LPIC-1
3. LFCS oder RHCSA

---

## Security

1. SC-900
2. LPI Security Essentials
3. Fortinet NSE 1–3
4. später Security+, Fortinet NSE 4 oder eine andere technische Spezialisierung

Security-Zertifikate ersetzen keine Netzwerk-, Betriebssystem- und Administrationsgrundlagen. Gerade in der Systemintegration ist Security ohne solides Verständnis der darunterliegenden Systeme nur begrenzt sinnvoll.

---

# 14. Was eher nicht sinnvoll ist

## Zertifikate nur sammeln

Zehn Fundamentals-Badges ersetzen keine praktische Erfahrung.

Im Bewerbungsgespräch ist es wesentlich überzeugender, eine kleine Umgebung erklären, konfigurieren und Fehler darin finden zu können, als eine lange Liste oberflächlicher Kursabschlüsse vorzuzeigen.

## Mehrere Cloud-Fundamentals ohne Praxis

AZ-900, AWS Cloud Practitioner und vergleichbare Einstiegszertifikate gleichzeitig zu absolvieren, bringt meist wenig zusätzlichen Nutzen.

Besser ist es, eine Plattform auszuwählen und nach den Grundlagen praktisch weiterzugehen.

## Zu früh teure Profi-Zertifikate buchen

CCNA, LPIC-1, LFCS, RHCSA oder fortgeschrittene Microsoft-Prüfungen sind sinnvoll, wenn das zugrunde liegende Wissen bereits vorhanden ist.

Ein Zertifikat sollte vorhandene Kompetenz nachweisen und nicht der Ersatz für den Kompetenzaufbau sein.

## Herstellerzertifikate ohne Bezug zum eigenen Umfeld

Ein Veeam-, Fortinet-, AWS- oder Red-Hat-Zertifikat kann fachlich stark sein. Ohne praktische Berührung mit dem jeweiligen Produkt entsteht aber schnell eine Lücke zwischen Papier und tatsächlicher Erfahrung.

## Kurszertifikate als Herstellerzertifizierung darstellen

Im Lebenslauf sollte erkennbar bleiben, ob etwas

- eine beaufsichtigte Zertifizierungsprüfung,
- ein praktisches Assessment,
- ein Kursabschluss oder
- ein digitales Badge

war.

Das erhöht die Glaubwürdigkeit des gesamten Profils.

---

# 15. Ein realistischer Kernpfad für FiSi

Wer parallel zu Ausbildung oder Umschulung ein überschaubares und schlüssiges Zertifizierungsprofil aufbauen möchte, kann sich zunächst auf sechs Schritte beschränken.

### 1. Microsoft Applied Skills: Active Directory Domain Services

Kostenlos und unmittelbar relevant für Windows-Systemadministration.

### 2. Cisco Networking Academy

Kostenlose praktische Netzwerkausbildung mit Packet Tracer.

### 3. Cisco CCST Networking

Erster formaler Netzwerknachweis mit überschaubaren Prüfungskosten.

### 4. Linux Essentials

Solider herstellerneutraler Linux-Grundlagennachweis.

### 5. SC-900 oder AZ-900

Ein Microsoft-Fundamentals-Zertifikat als Einstieg in Security, Identity oder Cloud.

### 6. AZ-802

Nach ausreichender Praxis ein sehr passender weiterführender Windows-Server-Nachweis.

Danach sollte die weitere Auswahl vom tatsächlichen beruflichen Schwerpunkt abhängen. Ein angehender Netzwerkadministrator profitiert eher vom CCNA, ein Linux-Administrator von LPIC-1 oder RHCSA, ein Endpoint-Administrator von MD-102 und ein Cloud-Administrator von AZ-104.

Der rote Faden ist wichtiger als die Menge der Zertifikate.

---

# 16. Quellen und Herstellerseiten

Für Preise, Prüfungsinhalte und Gültigkeitsregeln wurden vorrangig die offiziellen Herstellerinformationen verwendet.

## Microsoft

- Microsoft Credentials: https://learn.microsoft.com/de-de/credentials/
- AD DS Applied Skills: https://learn.microsoft.com/de-de/credentials/applied-skills/administer-active-directory-domain-services/
- Entra Applied Skills: https://learn.microsoft.com/de-de/credentials/applied-skills/get-started-with-identities-and-access-using-microsoft-entra/
- AZ-900: https://learn.microsoft.com/de-de/credentials/certifications/azure-fundamentals/
- SC-900: https://learn.microsoft.com/de-de/credentials/certifications/security-compliance-and-identity-fundamentals/
- AZ-802 / Windows Server Administrator: https://learn.microsoft.com/de-de/credentials/certifications/windows-server-administrator-associate/
- MD-102 / Endpoint Administrator: https://learn.microsoft.com/de-de/credentials/certifications/modern-desktop/
- AZ-104: https://learn.microsoft.com/de-de/credentials/certifications/azure-administrator/
- SC-300: https://learn.microsoft.com/de-de/credentials/certifications/identity-and-access-administrator/
- Gültigkeitsregeln: https://learn.microsoft.com/en-us/credentials/support/credential-expiration-policy

## Cisco

- Networking Academy: https://www.cisco.com/site/us/en/learn/training-certifications/training/netacad/index.html
- CCST: https://www.cisco.com/site/us/en/learn/training-certifications/certifications/support-technician/index.html
- CCST FAQ und Preis: https://www.cisco.com/site/us/en/learn/training-certifications/certifications/support-technician/faq.html
- CCNA: https://www.cisco.com/site/us/en/learn/training-certifications/exams/ccna.html
- Rezertifizierung: https://www.cisco.com/site/us/en/learn/training-certifications/certifications/recertification/index.html

## Linux Professional Institute

- Linux Essentials: https://www.lpi.org/de/our-certifications/linux-essentials-overview/
- Security Essentials: https://www.lpi.org/de/our-certifications/security-essentials-overview/
- LPIC-1: https://www.lpi.org/de/our-certifications/lpic-1-overview/
- Prüfungspreise: https://www.lpi.org/exam-pricing/

## Fortinet

- Training & Certification: https://www.fortinet.com/de/training-certification
- Änderungen des NSE-Programms 2026: https://helpdesk.training.fortinet.com/support/solutions/articles/73000665747-what-is-changing-in-the-nse-certification-program-in-2026-
- NSE 1: https://training.fortinet.com/local/staticpage/view.php?page=nse_1
- NSE 2: https://training.fortinet.com/local/staticpage/view.php?page=nse_2
- NSE 3: https://training.fortinet.com/local/staticpage/view.php?page=nse_3

## Linux Foundation

- LFCS: https://training.linuxfoundation.org/certification/linux-foundation-certified-sysadmin-lfcs/

## Red Hat

- RHCSA / EX200: https://www.redhat.com/de/services/training/ex200-red-hat-certified-system-administrator-rhcsa-exam

## AWS

- Cloud Practitioner: https://aws.amazon.com/certification/certified-cloud-practitioner/
- Solutions Architect – Associate: https://aws.amazon.com/de/certification/certified-solutions-architect-associate/

## Google Cloud

- Associate Cloud Engineer: https://cloud.google.com/learn/certification/cloud-engineer?hl=de

## Veeam

- Training und Zertifizierung: https://www.veeam.com/support/training.html
- VMCE+: https://www.veeam.com/support/training/vmce-certification.html

## PeopleCert / ITIL

- ITIL Foundation (Version 5): https://www.peoplecert.org/browse-certifications/it-governance-and-service-management/ITIL-1/itil-5-foundation-version-50-4154

## CompTIA

- Zertifizierungsübersicht: https://www.comptia.org/certifications

---

## Hinweise und Beiträge

Prüfungsprogramme, Preise und Zertifizierungsregeln ändern sich regelmäßig. Hinweise auf veraltete Angaben, Fehler oder sinnvolle Ergänzungen können über ein GitHub-Issue oder einen Pull Request eingebracht werden.
