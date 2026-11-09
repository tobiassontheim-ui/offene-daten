# Offene Daten aus amtlichen Quellen

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24093574.svg)](https://doi.org/10.5281/zenodo.24093574)

8 Tabellen mit zusammen 1.623 Zeilen, aufbereitet aus Gesetzen, Verordnungen und amtlichen Verzeichnissen.
Die Spalte „Amtliche Quelle“ nennt die Originalquellen; die Erläuterungsseite zeigt Rechenweg und Kontext. Datenwörterbuch, Versionen und Änderungsprotokoll: https://tobiassontheim.de/daten/.

| Datei | Inhalt | Zeilen | Stand | Amtliche Quelle | Erläuterung |
|---|---|---|---|---|---|
| `daten/got-gebuehrenverzeichnis.csv` | GOT-Gebührenverzeichnis mit Preisen (alle Positionen) | 1005 | 2026-11-08 | [GOT 2022, Anlage (Gebührenverzeichnis)](https://www.gesetze-im-internet.de/got_2022/anlage.html) | https://tierarztrechner.de/got/ |
| `daten/goz-gebuehrenverzeichnis.csv` | GOZ-Gebührenverzeichnis mit Euro-Beträgen | 209 | 2026-11-08 | [GOZ, Anlage 1 (Gebührenverzeichnis)](https://www.gesetze-im-internet.de/goz_1987/anlage_1.html) | https://zahnarztkostenrechner.de/goz/ |
| `daten/festzuschuesse-zahnersatz.csv` | Festzuschüsse Zahnersatz ab 01.01.2026 (alle Befunde) | 45 | 2026-11-08 | [GKV-Spitzenverband: Festzuschuss-Beträge](https://www.gkv-spitzenverband.de/media/dokumente/krankenversicherung_1/zahnaerztliche_versorgung/rili_g_ba/2026-01-01-FZ-Betraege.pdf) | https://zahnarztkostenrechner.de/festzuschuss/ |
| `daten/landesfoerderung-barrierefreier-umbau.csv` | Landesförderung für Treppenlift und barrierefreien Umbau (alle 16 Länder) | 16 | 2026-11-08 | [Baden-Württemberg: L-Bank](https://www.l-bank.de/produkte/wohnimmobilien/eigentumsfinanzierung-bw-z-15-darlehen-schwerbehinderte.html); [Bayern: Freistaat Bayern (Bayerisches Wohnungsbauprogramm)](https://www.stmb.bayern.de/wohnen/wohnraum_nutzen/barrierefreieswohnen/index.php); [Berlin: Investitionsbank Berlin (IBB)](https://www.ibb.de/de/foerderprogramme/ibb-wohnraum-modernisieren.html) u. a. | https://liftrechner.de/foerderung/ |
| `daten/verfahrensfreie-vorhaben.csv` | Verfahrensfreie Garten- und Anbauvorhaben je Bundesland | 208 | 2026-11-08 | [Landesbauordnung für Baden-Württemberg (LBO)](https://dejure.org/gesetze/LBO/Anhang_1.html); [Bayerische Bauordnung (BayBO)](https://www.gesetze-bayern.de/Content/Document/BayBO-57); [Bauordnung für Berlin (BauO Bln)](https://gesetze.berlin.de/perma?j=BauO_BE_!_61) u. a. | https://baugenehmigungsrechner.de/ |
| `daten/grenzbebauung.csv` | Grenzbebauung und Abstandsflächen je Bundesland | 16 | 2026-11-08 | [Landesbauordnung für Baden-Württemberg (LBO)](https://dejure.org/gesetze/LBO/Anhang_1.html); [Bayerische Bauordnung (BayBO)](https://www.gesetze-bayern.de/Content/Document/BayBO-57); [Bauordnung für Berlin (BauO Bln)](https://gesetze.berlin.de/perma?j=BauO_BE_!_61) u. a. | https://baugenehmigungsrechner.de/grenzbebauung/ |
| `daten/waermepumpe-grenzabstand.csv` | Wärmepumpe: Verfahrensfreiheit und Grenzabstand je Bundesland | 16 | 2026-11-09 | [LBO](https://www.landesrecht-bw.de/bsbw/document/jlr-NNLBW00007BCC); [BayBO](https://www.gesetze-bayern.de/Content/Document/BayBO-6); [BauO Bln](https://gesetze.berlin.de/perma?j=BauO_BE_!_6) u. a. | https://baugenehmigungsrechner.de/waermepumpe-abstand/ |
| `daten/grenzabstand-pflanzen.csv` | Grenzabstände für Hecken, Bäume und Sträucher je Bundesland | 108 | 2026-11-08 | [Nachbarrechtsgesetz für Baden-Württemberg (NRG)](https://dejure.org/gesetze/NRG/16.html); [Gesetz zur Ausführung des Bürgerlichen Gesetzbuchs (AGBGB)](https://www.gesetze-bayern.de/Content/Document/BayAGBGB-47); [Berliner Nachbarrechtsgesetz (NachbG Bln)](https://gesetze.berlin.de/bsbe/document/jlr-NNLBE0000495CNN00000000043) u. a. | https://baugenehmigungsrechner.de/grenzabstand-hecke-baum/ |

Hinweis Landesförderung: Status und Bedingungen der Programme können sich jederzeit ändern; maßgeblich ist die jeweilige Programmseite.

## Lizenz
Gesetze, Verordnungen und amtliche Bekanntmachungen sind gemeinfrei (§ 5 UrhG). Für die eigene Aufbereitung (Zusammenstellung, berechnete Spalten)
gilt [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de). Rechte Dritter an Ausgangsdaten bleiben unberührt.

## Zitieren
Siehe `CITATION.cff`. Kurzform: Sontheim, T. (2026). *Offene Daten aus amtlichen Quellen* [Data set]. https://tobiassontheim.de/daten/

## Keine Beratung
Die Tabellen informieren allgemein und ersetzen keine Rechts-, Steuer- oder Fachberatung. Verbindlich sind allein die amtlichen Texte.
