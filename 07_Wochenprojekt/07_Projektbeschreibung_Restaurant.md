### Übungsprojekt: Datenbankdesign Restaurant

#### Ziel:
Erstellung eines logischen und physischen Datenmodells, das die Abläufe in einem Restauran, sowei die entsprechenden Buchungen abbildet.
Das Modell soll die Struktur der Daten und deren Beziehungen darstellen, um eine effiziente Datenverwaltung und -analyse zu ermöglichen.

### Use-Case: Restaurantbesuch

#### Akteure:
- **Kunde**: Die Person, die das Restaurant besucht.
- **Kellner**: Der Mitarbeiter, der die Bestellungen aufnimmt und das Essen serviert.
- **Küchenpersonal**: Die Mitarbeiter, die die Bestellungen zubereiten.
- **Manager**: Die Person, die das Restaurant verwaltet und den Betrieb überwacht.

#### Ablauf:
1. **Reservierung**:
   - Der Kunde ruft im Restaurant an oder nutzt eine Online-Plattform, um einen Tisch zu reservieren.
   - Der Kunde gibt die Anzahl der Personen, das Datum und die Uhrzeit der Reservierung an.
   - Das System bestätigt die Reservierung und speichert die Details.

2. **Ankunft und Platzierung**:
   - Der Kunde kommt zum Restaurant und gibt seinen Namen an.
   - Der Kellner überprüft die Reservierung und führt den Kunden zu seinem Tisch.

3. **Bestellung**:
   - Der Kunde erhält die Speisekarte und wählt die gewünschten Gerichte und Getränke aus.
   - Der Kellner nimmt die Bestellung auf und gibt sie an das Küchenpersonal weiter.

4. **Zubereitung und Servieren**:
   - Das Küchenpersonal bereitet die bestellten Gerichte zu.
   - Der Kellner serviert die Gerichte und Getränke am Tisch des Kunden.

5. **Verzehr und Service**:
   - Der Kunde genießt sein Essen und kann bei Bedarf weitere Bestellungen aufgeben.
   - Der Kellner steht für Fragen und Wünsche des Kunden zur Verfügung.

6. **Bezahlung**:
   - Nach dem Essen fordert der Kunde die Rechnung an.
   - Der Kellner bringt die Rechnung und der Kunde bezahlt entweder bar, mit Karte oder über eine mobile Zahlungsapp.
   - Der Kellner bedankt sich und gibt dem Kunden eine Quittung.

7. **Feedback und Verabschiedung**:
   - Der Kunde hat die Möglichkeit, Feedback zum Essen und Service zu geben.
   - Der Kellner verabschiedet den Kunden und bedankt sich für den Besuch.

#### Ziele:
- **Kundenzufriedenheit**: Sicherstellen, dass der Kunde ein angenehmes und zufriedenstellendes Erlebnis hat.
- **Effiziente Abwicklung**: Gewährleisten, dass der Bestell- und Bezahlvorgang reibungslos und effizient abläuft.
- **Qualität der Speisen**: Sicherstellen, dass die Gerichte frisch und nach den Wünschen des Kunden zubereitet werden.
- **Servicequalität**: Bereitstellen eines freundlichen und aufmerksamen Service, um die Kundenzufriedenheit zu erhöhen.

Dieser Use-Case beschreibt die grundlegenden Abläufe und Interaktionen in einem Restaurant. 

---

### Übungsprojekt: Logisches Datenmodell für ein Restaurant

#### Ziel:
Erstellung eines logischen Datenmodells, das die Geschäftsprozesse und Interaktionen eines Restaurants abbildet.
Das Modell soll die Struktur der Daten und deren Beziehungen darstellen, um eine effiziente Datenverwaltung und -analyse zu ermöglichen.

#### Anforderungen:
1. **Kundenverwaltung**:

2. **Tischreservierungen**:

3. **Speisekarte**:

4. **Bestellungen**:

5. **Bestellpositionen**:

6. **Mitarbeiterverwaltung**:

7. **Lieferantenverwaltung**:

#### Beziehungen:
- Ein Kunde kann mehrere Reservierungen haben (1:n Beziehung zwischen Kunden und Reservierungen).
- Eine Reservierung ist einem bestimmten Tisch zugeordnet (1:1 Beziehung zwischen Reservierungen und Tischen).
- Eine Bestellung kann mehrere Bestellpositionen enthalten (1:n Beziehung zwischen Bestellungen und Bestellpositionen).
- Ein Gericht kann von mehreren Lieferanten geliefert werden (n:m Beziehung zwischen Gerichten und Lieferanten).
- Ein Mitarbeiter kann mehreren Schichten zugeordnet sein (1:n Beziehung zwischen Mitarbeitern und Schichten).

#### Schritte zur Umsetzung:
1. **Anforderungsanalyse**: Sammeln und Dokumentieren der Anforderungen.
2. **Erstellung des ER-Diagramms**: Visualisierung der Entitäten und ihrer Beziehungen.
3. **Normalisierung**: Sicherstellen, dass das Datenmodell normalisiert ist, um Redundanzen zu vermeiden.
4. **Implementierung**: Umsetzung des logischen Modells in ein physisches Datenbankschema.
5. **Testen und Validieren**: Überprüfen, ob das Modell die Anforderungen erfüllt und korrekt funktioniert.
