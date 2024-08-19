### Übungsprojekt: Datenbankdesign Supermarkt / Späti

#### Ziel:
Erstellung eines logischen und physischen Datenmodells, das die Geschäftsprozesse eines Supermarkts abbildet.
Das Modell soll die Struktur der Daten und deren Beziehungen darstellen, um eine effiziente Datenverwaltung und -analyse zu ermöglichen.

### Use-Case: Einkauf im Supermarkt / Späti

#### Akteure:
- **Kunde**: Die Person, die im Supermarkt einkauft.
- **Kassierer**: Der Mitarbeiter, der die Produkte scannt und den Bezahlvorgang abwickelt.
- **Lagerist**: Der Mitarbeiter, der für das Auffüllen der Regale und die Lagerverwaltung zuständig ist.
- **Lieferant**: Die Person oder das Unternehmen, das Waren an den Supermarkt liefert.

#### Ablauf:
1. **Produktauswahl**:
   - Der Kunde betritt den Supermarkt und wählt Produkte aus den Regalen aus.
   - Der Kunde legt die ausgewählten Produkte in seinen Einkaufswagen.

2. **Preisprüfung**:
   - Der Kunde kann an speziellen Scannern im Supermarkt den Preis der Produkte überprüfen.

3. **Bezahlung**:
   - Der Kunde begibt sich zur Kasse.
   - Der Kassierer scannt die Produkte und erstellt eine Rechnung.
   - Der Kunde bezahlt die Rechnung entweder bar, mit Karte oder über eine mobile Zahlungsapp.
   - Der Kassierer gibt dem Kunden den Kassenbon und die gekauften Produkte.

4. **Lagerverwaltung**:
   - Der Lagerist überprüft regelmäßig den Lagerbestand und füllt die Regale bei Bedarf auf.
   - Der Lagerist nimmt Lieferungen von Lieferanten entgegen und lagert die Produkte im Lager ein.

5. **Bestandsverwaltung**:
   - Das System aktualisiert den Lagerbestand automatisch nach jedem Verkauf.
   - Bei niedrigem Lagerbestand wird automatisch eine Nachbestellung beim Lieferanten ausgelöst.

6. **Kundenbindung**:
   - Der Supermarkt bietet Treueprogramme an, bei denen Kunden Punkte sammeln können.
   - Kunden können ihre Treuepunkte bei zukünftigen Einkäufen einlösen.

Dieser Use-Case beschreibt die grundlegenden Abläufe und Interaktionen in einem Supermarkt. 
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
2. **Erstellung des ER-Diagramms**: Visualisierung der Entitäten und ihrer Beziehungen.
3. **Normalisierung**: Sicherstellen, dass das Datenmodell normalisiert ist, um Redundanzen zu vermeiden.
4. **Implementierung**: Umsetzung des logischen Modells in ein physisches Datenbankschema.
5. **Testen und Validieren**: Überprüfen, ob das Modell die Anforderungen erfüllt und korrekt funktioniert.
