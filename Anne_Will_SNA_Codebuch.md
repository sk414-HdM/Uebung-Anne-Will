# Datensatz Gäste Anne Will Thema Ukraine

Codebuch Stand 2026-11 erstellt von Sylvia Kopplow (sk414\@hdm-stuttgart.de)

## Inhalt

- [Anne_Will_SNA_Edgelist.csv](https://github.com/sk414-HdM/Uebung-Anne-Will/blob/main/Anne_Will_SNA_Edgelist.csv) (Edgelist)
- [Anne_Will_SNA_Nodelist.csv](https://github.com/sk414-HdM/Uebung-Anne-Will/blob/main/Anne_Will_SNA_Nodelist.csv) (Nodelist)
- [Anne_Will_SNA_Codebuch.md](https://github.com/sk414-HdM/Uebung-Anne-Will/blob/main/Anne_Will_SNA_Codebuch.md) (Codierung der Datensätze)

## Ursprung und Datenerhebung

Ich habe den Datensatz der Teilnehmer\*innen aus den Folgen 500 - 503 von Anne Will. Die Informationen stammen von: <https://www.fernsehserien.de/anne-will/episodenguide>.

Das Netzwerk ist ein *gerichtetes bimodales Akteursnetzwerk*. Es wurden zwei getrennte Fragen erhoben:

# EDGE-Attribute

**id**\
(eindeutige Codierung des Knoten) codiert mit Initialien, bestehend aus Anfangsbuchstaben von Vor- und Nachnamen, sowie gängige Abkürzungen der Parteien und Nummern der Folgen.

**relation** Beziehungsart zwischen den Personen, Folgen und Parteien\
1 = *Gast/Teilnehmer\*in* Bei einem gerichteten Netzwerk präferiert der Sender (erste Spalte) die Zusammenarbeit mit der genannten Zielperson (zweite Spalte).\
2 = *Parteizugehörigkeit* Bei einem gerichteten Netzwerk gehört der Sender (erste Spalte) der genannten Partei (zweite Spalte) an.

# NODE-Attribute

**id**\
Identische ID wie aus der edgelist zur Identifikation der Knoten.

**Teilnehmer*in \***
Name von Teilnehmerinnen, Folgen und Parteien

**Type**\
1 = Teilnehmer\*in\
2 = Folge\
3 = Partei

**Sector**\
Welchen Bereich vertreten Teilnehmer\*innen?\
Freie Eingabe

**Country**\
Welche Länder vertreten die Teilnehmer\*innen? \
Freie Eingabe.
