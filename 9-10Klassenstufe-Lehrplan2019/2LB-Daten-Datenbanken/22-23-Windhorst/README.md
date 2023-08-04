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
- Einführung in Modellieren von Datenbanken mit Hilfe des Entity Relationship Modells
- Warum nicht nur einfach alles in eine Tabelle, sondern in viele Tabellen?
	- weniger Redundanz, redundanz = viel Speicherplatz, mehr Fehlerpotential
- Einführung der Begriffe:
	- Entität
	- Attribut
	- Schlüssel
- ER-Modell wird vorne von der Lehrkraft anhand eines Beispiels erläutert und eingeführt
	- ggf. InstaHub als Beispiel nehmen
	
## 5 Grundlagen Datenbanken 3/4
- Entity Relationship Diagramm
- SuS sollen auf Basis von dem gelernten Wissen zu Entity Relationship Modelle eigenständig ein ER Modell zu einer Ausgangssituation erstellen
## 6 Grundlagen Datenbanken 4/4
- Einführung von Relationalen Datenbanken
- Überführung von Entity Relationship Modellen in ein Relationales Datenbankmodell
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

## 8 Grundlagen SQL-Abfragen 2/3

## 9 Grundlagen SQL-Abfragen 3/3

## 10 SQL - Daten Verändern

## 11 SQL - Datenbanken modellieren

## 12 SQL - Komplexere SQL Abfragen LK - SQL

## 13 Abschlussdiskussion und Feedbackrunde

# Material-Übersicht