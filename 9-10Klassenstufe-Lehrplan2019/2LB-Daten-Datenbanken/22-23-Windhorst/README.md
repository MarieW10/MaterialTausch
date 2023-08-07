# Verlaufsplan 9. Klasse Datenbanken 2022/2023
# Überblick Verlaufsplan
| Stunde | Thema                                                             | Kurzbeschreibung/Lernziel                                                                                                                                               |
|--------|-------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1      | Einführung Thema Datenbanken                                      | Bewusstsein für die Allgegenwärtigkeit von Daten und die Notwendigkeit von Datenbanken Erste Definition von Datenbank                                                   |
| 2      | Einführung InstaHub                                               | SuS erstellen ein InstaHub Account und lernen die Umgebung von Instahub kennen                                                                                          |
| 3      | Grundlagen Datenbanken 1/4                                        | Definitionen: Datenbank, Datenbanksystem, Datenbankmanagementsystem, Datenbasis, Relationale Datenbanken, Aufbau vers. Datenbanken (objekt, hierarchisch, Graphen, ...) |
| 4      | Grundlagen Datenbanken 2/4                                        | Entity Relationship Modell - Datenbanken Modellieren                                                                                                                                                 |
| 5      | Grundlagen Datenbanken 3/4                                        | Entity Relationship Diagramm                                                                                                                                             |
| 6      | Grundlagen Datenbanken 4/4                                        | Entity Relationship - Relationales Datenbankmodell                                                                                                                                            |
| 7      | Grundlagen SQL-Abfragen 1/3 LK - Theorie Grundlagen Datenbanken   | LK - Theorie Grundlagen Datenbanken Einführung in SQL mit SQL-Island: SuS versuchen ohne Vorwissen sich das Prinzip von SQL mit SQL-Island anzueignen                   |
| 8      | Grundlagen SQL-Abfragen 2/3                                       | Geleitete Einführung in SQL Aufbau (select, from, where), Funktion                                                                                                      |
| 9      | Grundlagen SQL-Abfragen 3/3                                       | SuS lernen weitere Signalwörter für SQL kennen                                                                                                                          |
| 10     | SQL - Daten Verändern                                             | SuS lernen, wie mit Hilfe von SQL Daten verändert werden können (insrt, delete, update)                                                                                 |
| 11     | SQL - Datenbanken modellieren                                     | SuS lernen, wie mit Hilfe von SQL eine Datenbank erstellt werden kann (                                                                                                 |
| 12     | SQL - Komplexere SQL Abfragen LK - SQL                            | SuS lernen, wie mit Hilfe von SQL Abfragen über mehrere Tabellen gemacht werden können SQL-LK                                                                           |
| 13     | Abschlussdiskussion und Feedbackrunde                             |                                                                                                                                                                         |

# Unterrichtsbeschreibung
To-Do
- Präsentationsfolien updaten
- überlegen, wie viel von InstaHub bereits für die SuS am Anfang freigeschaltet werden soll 

## 1 Einführung Thema Datenbanken
- Wissensaktivierung mit Menti
	- SuS sollen drei Beispiele für Situationen nennen, in denen große Datenmengen anfallen
	- Die Ergebnisse werden gesichtet und es wird überlegt um was für Daten genau in den jeweiligen Situationen gesammelt werden
- Der Begriff BigData wird eingeführt mit den drei v's
	- Variety - hohe Vielfalt der Daten
	- Velocity - hohe Geschwindigkeit, in der Daten generiert werden
	- Volume - hohes Volumen an Daten, das ankommt
- Beispiele für Big Data
	- Es werden Visualisierungen von (Big) Data gezeigt
	- Die SuS sollen sich in Partnerarbeit zu den Visualisierungen Gedanken machen, was für Daten/Informationen für die Visualisierungen notwengig ist
	- weiterhin sollen die SuS sich Gedanken machen, wie die Visualisierungen erstellt wurden
	- Beispiel-Quelle
		- [Information is Beautiful](https://informationisbeautiful.net/)
	- Diese Überlegungen soll dazu hinleiten, das Daten nicht einfach in der Luft sind, sondern in einer bestimmten Form vorliegen müssen
		- Überleitung Datenbank
- Definition Datenbank 
### Material 
Präsentationsfolien: 1-\
Arbeitsblätter:
Weitere Medien: 
- [Information is Beautiful](https://informationisbeautiful.net/)


## 2 Einführung Instahub
- Wiederholung: Kahoot
- vorstellen von InstaHub als die Basis-Datenbank für die weitere Unterrichtseinheit
	- SuS sind Datenbankadministratoren und sollen das Soziale Netzwerk InstaHub mit aufbauen
- Geleitet von der Lehrkraft erstellen die SuS je einen eigenen Account bei InstaHub
	- **WICHTIG** Lehrkraft muss einige Tage vorher sich bereits einen Lehrer Account erstellen, da dieser vorher freigeschaltet werden muss 
- Weitere Hinweise zu InstaHub
	- SuS sollen sich nach der Aktivierung ihres Accounts durch die Lehrkraft eigensändig bei InstaHub anmelden, und schauen das sie folgende Information zur Anmeldung angeben und sich notiert haben:
		- Benutzername: Admin (nicht den Namen, den sie bei der Anmeldung angegeben haben, der ist nur für die Lehrkraft wichtig, um die SuS auseinanderzuhalten)
		- als Website: azurblau27.instahub.org
		- Passwort: Das von den SuS selbst gewählte Passwort

### Material
Präsentationsfolien: /
Arbeitsblätter:
Weitere Medien: 
- [InstaHub-Website](https://instahub.org/#)

## 3 Grundlagen Datenbanken 1/4
- Wiederholung: Kahoot
- Kennenlernen der Bestandteile eines Datenbanksystems
- Datenbanksystem = Datenbasis + Datenbankmanagement-System
- SuS recherchieren, was die Aufgabe eine DBMS ist 
- Übergang Datenbankmodelle
	- Datenbanksysteme können je nach Anwendungsbereich unterschiedlich aufgebaut sein
	- Da je nach Bereich unterschiedliche Modelle sich mehr oder weniger für den Bereich eignen
	- Vorstellen einiger Datenbankmodelle, ihr Modellierungs-Prinzip und Anwendungsgebiet
		- Objektorientiertes Datenbankmodell
		- Graphen Datenbank
		- Relationales Datenbankmodell -> Hinweis darauf, das dies weiter der Fokus der Unterrichtseinheit
	- **HINWEIS:** Bewusst auf den Begriff **Modell** eingehen
		- ggf. auf Parallelen aus der Biologie, Chemie, Physik eingehen, was da ein Modell ist 

### Material 
Präsentationsfolien: \
Arbeitsblätter: \
weitere Medien: \

## 4 Grundlagen Datenbanken 2/4
- Wiederholung: Kahoot
- Einführung in Modellieren von Datenbanken mit Hilfe des Entity Relationship Modells
- Warum müssen Datenbanken modelliert werden? was ist der Sinn von Modellen in der Informatik?
	- weniger Redundanz, redundanz = viel Speicherplatz, mehr Fehlerpotential
- Auf Modellierungsschritte eine Datenbank eingehen und so die ER Modelle erstellen
	1. Anforderungsanalyse
	2. Konzeptuelle Modellierung
	3. Logische Modellierung
	4. Implementierung
	5. Testen und Feinabstimmung
	6. Betrieb und Wartung
- Einführung der Begriffe:
	- Entität
	- Attribut
	- Schlüssel
- ER-Modell wird vorne von der Lehrkraft anhand eines Beispiels erläutert und eingeführt
	- ggf. InstaHub als Beispiel nehmen
	- D.h. hier die Schritte Anforderungsanalyse und konzeptuelle Modellierung besprechen
### Material 
Präsentationsfolien: \
Arbeitsblätter: \
weitere Medien: \	

## 5 Grundlagen Datenbanken 3/4
- Wiederholung: Kahoot
- Entity Relationship Diagramm
- SuS sollen auf Basis von dem gelernten Wissen zu Entity Relationship Modelle eigenständig ein ER Modell zu einer Ausgangssituation erstellen
### Material 
Präsentationsfolien: \
Arbeitsblätter: \
weitere Medien: \

## 6 Grundlagen Datenbanken 4/4
- Wiederholung: Kahoot
- Einführung von Relationalen Datenbanken
- Überführung von Entity Relationship Modellen in ein Relationales Datenbankmodell
	- D.h. hier der Schritt logische Modellierung
- Besonders auf die Rolle von Fremdschlüsseln eingehen
- SuS eine Übersicht bereitstellen mit allen wichtigen Grundlagen für die Theorie LK 

### Material
Präsentationsfolien: \
Arbeitsblätter:
- Lernübersicht Grundlagen Datenbanken 
Weitere Medien: \ 

## 7 Grundlagen SQL-Abfragen 1/3 LK - Theorie Grundlagen Datenbanken
- ersten 10-15min Theorie LK zu den Grundlagen von Datenbanken
- Danach sollen die Schüler sich eigenständig in SQL mit Hilfe von SQL-Island einarbeiten.
- Dafür den SuS Seiten und/oder Material zur Verfügung stellen, womit sie gezielt recherhieren können, wie sie die nötige Informationen für die Aufgaben bekommen können 
### Material
Präsentationsfolien: \
Arbeitsblätter:
- Lernübersicht Grundlagen Datenbanken 
Weitere Medien: \ 

## 8 Grundlagen SQL-Abfragen 2/3
- Wiederholung: Kahoot
- Einführung in die Grundalgen von SQL
- SuS fragen, was Ihnen bei dem Bearbeiten der SQL-Island Aufgaben aufgefallen ist, irgendein Muster, womit sie die Struktur von SQL-Abfragen ableiten können
- CRUD Prinzip von Datenbanken einführen
	- Create
	- Read
	- Update
	- Delete
- als erstes wird sich mit Read auseinandergesetzt
- Grundstruktur:
	- SELECT
	- FROM
	- WHERE
		- distinct
		- Vergleichsoperatoren
- SuS eigene einfache Abfragen in InstaHub ausführen lassen
### Material
Präsentationsfolien: \
Arbeitsblätter:
Weitere Medien: \

## 9 Grundlagen SQL-Abfragen 3/3
- Wiederholung: Kahoot
- SuS weitere Abfragen in SQL zeigen
- Logische Operatoren + Wahrheittafel
	- AND
	- OR
	- NOT
- count
- **noch weitere SQL Befehle raussuchen**
- SuS die SQL Befehle bei InstaHub ausprobieren lassen

### Material
Präsentationsfolien: \
Arbeitsblätter:
Weitere Medien: 

## 10 SQL - Daten Verändern
- Wiederholung: Kahoot
- nochmal aud CRUD eingehen
	- Update wird nun betrachtet
- SuS die SQL Befehle zeigen:
	- INSERT
	- DELETE
	- UPDATE
- SuS die Befehle eigenständig bei InstaHub 

### Material
Präsentationsfolien: \
Arbeitsblätter:
Weitere Medien: 

## 11 SQL - Datenbanken modellieren
- Wiederholung: Kahoot
- nochmal aud CRUD eingehen
	- Create wird nun betrachtet
- CREATE Befehl zeigen
- SuS führen Create Befehle eigenständig aus 

### Material
Präsentationsfolien: \
Arbeitsblätter:
Weitere Medien: 

## 12 SQL - Komplexere SQL Abfragen LK - SQL
- SQL-LK
	- SuS bekommen eine einfache Datenbank gegeben mit den entsprechenden Informationen, was für Daten darin stehen
	- SuS bekommen Fragen der Datenbank, zu denen sie die entsprechenden SQL Befehle schreiben sollen 
	- Eingeplante Zeit: 15-20min
- Einührung von Verbund-Abfragen in SQL-Abfragen
	- von Interesse bei DB-Abfragen nicht nur die Information einer Tabelle zu erfahren, sondern auch komplexere Abfragen zu stellen, die über mehrere Tabellen geht
	- Dafür sind JOIN-Abfragen in SQL notwendig
- zur **Vorbereitung der Abschlussdiskussion** am besten schon die Diskussionfragen austeilen und als HA die Aufgabe geben, sich Notizen zu der Diskussionsfrage zu machen
	- Alternativ: Die Gruppe halbieren und die eine Gruppe ist ist Pro und die andere Contra der Diskussionsfrage und bekommen die HA sich Notizen zu ihrer Position zu machen, die dann in der nächsten Stunde ausgetauscht werden.

### Material
Präsentationsfolien: \
Arbeitsblätter:
Weitere Medien: 

## 13 Abschlussdiskussion und Feedbackrunde
- Online Fragebogen für die SuS bereitstellen, in denen gefragt wird, wie den SuS die Datenbankeinheit allg. gefallen hat und was ggf. noch verbessert werden könnte
- Abschlussdiskussion: Je nach Interesse, das aus den SuS abgeleitet wird, könnte über eins der folgenden Themen diskutiert werden, das in der Stunde zuvor bereits als HA gegeben wird, sich darüber Gedanken zu machen	    Datenschutz: Welche Bedenken haben Sie bezüglich der Sicherheit und des Datenschutzes in Bezug auf Datenbanken und die darin gespeicherten persönlichen Informationen?
	- Big Data: Was sind einige der positiven Auswirkungen von Big Data auf unsere Gesellschaft? Gibt es auch Bedenken hinsichtlich der Massensammlung und -nutzung von Daten?
	- Datenmissbrauch: In welchen Situationen könnte der Missbrauch von Datenbanken auftreten? Wie können wir uns vor Datenmissbrauch schützen?
	- Datenanalyse und Personalisierung: Wie beeinflusst die Analyse großer Datenmengen (Big Data) unsere Erfahrungen als Nutzer von Online-Diensten und sozialen Medien? Gibt es Vor- oder Nachteile dieser Personalisierung?
	- Ethik und Entscheidungsfindung: Welche ethischen Überlegungen sollten bei der Verwendung von Datenbanken in automatisierten Entscheidungsprozessen, wie zum Beispiel bei Kreditbewertungen oder Einstellungsverfahren, berücksichtigt werden?
	- Redundanz und Datenintegrität: Wie kann die Redundanz von Daten in Datenbanken vermieden werden, um die Datenintegrität sicherzustellen? Welche Probleme könnten auftreten, wenn redundante Daten nicht korrekt verwaltet werden?
	-Datenzugriff und Rechte: Wer sollte Zugriff auf Datenbanken haben und welche Rechte sollten den Benutzern gewährt werden? Wie können wir sicherstellen, dass der Datenzugriff angemessen kontrolliert und geschützt wird?
	- Zukunft der Datenbanktechnologie: Wie wird sich die Datenbanktechnologie in Zukunft weiterentwickeln? Welche Möglichkeiten und Herausforderungen sehen Sie in Bezug auf die Verwaltung und Nutzung von Daten?

### Material
Präsentationsfolien: \
Arbeitsblätter:
Weitere Medien: 

# Material-Übersicht