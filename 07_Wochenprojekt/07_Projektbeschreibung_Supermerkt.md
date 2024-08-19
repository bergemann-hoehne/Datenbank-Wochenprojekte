### �bungsprojekt: Datenbankdesign Supermarkt / Sp�ti

#### Ziel:
Erstellung eines logischen und physischen Datenmodells, das die Gesch�ftsprozesse eines Supermarkts abbildet.
Das Modell soll die Struktur der Daten und deren Beziehungen darstellen, um eine effiziente Datenverwaltung und -analyse zu erm�glichen.

### Use-Case: Einkauf im Supermarkt / Sp�ti

#### Akteure:
- **Kunde**: Die Person, die im Supermarkt einkauft.
- **Kassierer**: Der Mitarbeiter, der die Produkte scannt und den Bezahlvorgang abwickelt.
- **Lagerist**: Der Mitarbeiter, der f�r das Auff�llen der Regale und die Lagerverwaltung zust�ndig ist.
- **Lieferant**: Die Person oder das Unternehmen, das Waren an den Supermarkt liefert.

#### Ablauf:
1. **Produktauswahl**:
   - Der Kunde betritt den Supermarkt und w�hlt Produkte aus den Regalen aus.
   - Der Kunde legt die ausgew�hlten Produkte in seinen Einkaufswagen.

2. **Preispr�fung**:
   - Der Kunde kann an speziellen Scannern im Supermarkt den Preis der Produkte �berpr�fen.

3. **Bezahlung**:
   - Der Kunde begibt sich zur Kasse.
   - Der Kassierer scannt die Produkte und erstellt eine Rechnung.
   - Der Kunde bezahlt die Rechnung entweder bar, mit Karte oder �ber eine mobile Zahlungsapp.
   - Der Kassierer gibt dem Kunden den Kassenbon und die gekauften Produkte.

4. **Lagerverwaltung**:
   - Der Lagerist �berpr�ft regelm��ig den Lagerbestand und f�llt die Regale bei Bedarf auf.
   - Der Lagerist nimmt Lieferungen von Lieferanten entgegen und lagert die Produkte im Lager ein.

5. **Bestandsverwaltung**:
   - Das System aktualisiert den Lagerbestand automatisch nach jedem Verkauf.
   - Bei niedrigem Lagerbestand wird automatisch eine Nachbestellung beim Lieferanten ausgel�st.

6. **Kundenbindung**:
   - Der Supermarkt bietet Treueprogramme an, bei denen Kunden Punkte sammeln k�nnen.
   - Kunden k�nnen ihre Treuepunkte bei zuk�nftigen Eink�ufen einl�sen.

Dieser Use-Case beschreibt die grundlegenden Abl�ufe und Interaktionen in einem Supermarkt. 
Darauf aufbauend soll im Laufe dieses Wochenprojektes eine Datenmodellierung erfolgen.

#### Anforderungen:
1. **Kundenverwaltung**:

2. **Produktverwaltung**:

3. **Lieferantenverwaltung**:

4. **Bestellungen / Einkauf**:

5. **Bestellpositionen**:

6. **Mitarbeiterverwaltung**:

#### Beziehungen:
- Ein Kunde kann mehrere Bestellungen aufgeben.
- Eine Bestellung kann mehrere Bestellpositionen enthalten.
- Ein Produkt kann von mehreren Lieferanten geliefert werden.
- Ein Mitarbeiter kann mehreren Abteilungen zugeordnet sein.

#### Schritte zur Umsetzung:
1. **Anforderungsanalyse**: Sammeln und Dokumentieren der Anforderungen.
2. **Erstellung des ER-Diagramms**: Visualisierung der Entit�ten und ihrer Beziehungen.
3. **Normalisierung**: Sicherstellen, dass das Datenmodell normalisiert ist, um Redundanzen zu vermeiden.
4. **Implementierung**: Umsetzung des logischen Modells in ein physisches Datenbankschema.
5. **Testen und Validieren**: �berpr�fen, ob das Modell die Anforderungen erf�llt und korrekt funktioniert.
