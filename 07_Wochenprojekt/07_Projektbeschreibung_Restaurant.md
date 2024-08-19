### �bungsprojekt: Datenbankdesign Restaurant

#### Ziel:
Erstellung eines logischen und physischen Datenmodells, das die Abl�ufe in einem Restauran, sowei die entsprechenden Buchungen abbildet.
Das Modell soll die Struktur der Daten und deren Beziehungen darstellen, um eine effiziente Datenverwaltung und -analyse zu erm�glichen.

### Use-Case: Restaurantbesuch

#### Akteure:
- **Kunde**: Die Person, die das Restaurant besucht.
- **Kellner**: Der Mitarbeiter, der die Bestellungen aufnimmt und das Essen serviert.
- **K�chenpersonal**: Die Mitarbeiter, die die Bestellungen zubereiten.
- **Manager**: Die Person, die das Restaurant verwaltet und den Betrieb �berwacht.

#### Ablauf:
1. **Reservierung**:
   - Der Kunde ruft im Restaurant an oder nutzt eine Online-Plattform, um einen Tisch zu reservieren.
   - Der Kunde gibt die Anzahl der Personen, das Datum und die Uhrzeit der Reservierung an.
   - Das System best�tigt die Reservierung und speichert die Details.

2. **Ankunft und Platzierung**:
   - Der Kunde kommt zum Restaurant und gibt seinen Namen an.
   - Der Kellner �berpr�ft die Reservierung und f�hrt den Kunden zu seinem Tisch.

3. **Bestellung**:
   - Der Kunde erh�lt die Speisekarte und w�hlt die gew�nschten Gerichte und Getr�nke aus.
   - Der Kellner nimmt die Bestellung auf und gibt sie an das K�chenpersonal weiter.

4. **Zubereitung und Servieren**:
   - Das K�chenpersonal bereitet die bestellten Gerichte zu.
   - Der Kellner serviert die Gerichte und Getr�nke am Tisch des Kunden.

5. **Verzehr und Service**:
   - Der Kunde genie�t sein Essen und kann bei Bedarf weitere Bestellungen aufgeben.
   - Der Kellner steht f�r Fragen und W�nsche des Kunden zur Verf�gung.

6. **Bezahlung**:
   - Nach dem Essen fordert der Kunde die Rechnung an.
   - Der Kellner bringt die Rechnung und der Kunde bezahlt entweder bar, mit Karte oder �ber eine mobile Zahlungsapp.
   - Der Kellner bedankt sich und gibt dem Kunden eine Quittung.

7. **Feedback und Verabschiedung**:
   - Der Kunde hat die M�glichkeit, Feedback zum Essen und Service zu geben.
   - Der Kellner verabschiedet den Kunden und bedankt sich f�r den Besuch.

#### Ziele:
- **Kundenzufriedenheit**: Sicherstellen, dass der Kunde ein angenehmes und zufriedenstellendes Erlebnis hat.
- **Effiziente Abwicklung**: Gew�hrleisten, dass der Bestell- und Bezahlvorgang reibungslos und effizient abl�uft.
- **Qualit�t der Speisen**: Sicherstellen, dass die Gerichte frisch und nach den W�nschen des Kunden zubereitet werden.
- **Servicequalit�t**: Bereitstellen eines freundlichen und aufmerksamen Service, um die Kundenzufriedenheit zu erh�hen.

Dieser Use-Case beschreibt die grundlegenden Abl�ufe und Interaktionen in einem Restaurant. 

---

### �bungsprojekt: Logisches Datenmodell f�r ein Restaurant

#### Ziel:
Erstellung eines logischen Datenmodells, das die Gesch�ftsprozesse und Interaktionen eines Restaurants abbildet.
Das Modell soll die Struktur der Daten und deren Beziehungen darstellen, um eine effiziente Datenverwaltung und -analyse zu erm�glichen.

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
2. **Erstellung des ER-Diagramms**: Visualisierung der Entit�ten und ihrer Beziehungen.
3. **Normalisierung**: Sicherstellen, dass das Datenmodell normalisiert ist, um Redundanzen zu vermeiden.
4. **Implementierung**: Umsetzung des logischen Modells in ein physisches Datenbankschema.
5. **Testen und Validieren**: �berpr�fen, ob das Modell die Anforderungen erf�llt und korrekt funktioniert.
