# 9 PostgreSQL

### **Aufgabe: Entwicklung einer PostgreSQL-Datenbank f�r einen Onlineshop**

#### **Einleitung:**
In dieser Aufgabe entwickeln Sie eine relationale Datenbank mit PostgreSQL f�r einen Onlineshop. Das Ziel ist es, eine funktionale Datenbank zu erstellen, die alle notwendigen Daten f�r den Betrieb eines einfachen Onlineshops verwaltet. Dies ist ein zentraler Bestandteil jedes modernen E-Commerce-Systems, da die Datenbank die Grundlage f�r die Verwaltung von Produkten, Kunden, Bestellungen und Zahlungen bildet.

#### **Aufgabenbeschreibung:**

1. **Verstehen des Konzepts:**
   - Sie erstellen eine Datenbank, die alle relevanten Informationen f�r den Onlineshop speichert. Dies umfasst das Anlegen und Verwalten von Benutzerkonten, Bestellungen, Produkten, Zahlungen und weiteren Aspekten des Shop-Betriebs.

2. **Erstellung der Datenbank:**
   - Nutzen Sie PostgreSQL, um die Datenbank zu entwickeln. Dabei sollten Sie die Tabellen, die in der beigef�gten Grafikdatei dargestellt sind, als Grundlage verwenden.
   - Die notwendigen Tabellen umfassen:
     1. **Benutzerkonto**: Speicherung von Kundendaten wie Name, E-Mail-Adresse, Passwort und weitere pers�nliche Informationen.
     2. **Bestellung**: Verwaltung von Bestellungen, die Kunden im Shop aufgeben.
     3. **Bestellhistorie**: Aufzeichnung aller Bestellungen, um eine Historie zu erstellen.
     4. **Zahlung**: Speicherung von Zahlungsinformationen, die f�r die Bestellungen get�tigt wurden.
     5. **Lager**: Verwaltung des Lagerbestands, um die Verf�gbarkeit von Produkten sicherzustellen.
     6. **Produkt**: Informationen zu den im Shop angebotenen Artikeln, einschlie�lich Name, Preis, und Beschreibung.
     7. **Bestellposition**: Details zu den einzelnen Produkten innerhalb einer Bestellung.

3. **Optionale Erweiterungen:**
   - F�r besonders motivierte Teilnehmer besteht die M�glichkeit, die Datenbank um zus�tzliche Tabellen zu erweitern:
     8. **Retouren**: Verwaltung von zur�ckgesendeten Artikeln und den dazugeh�rigen Prozessen.
     9. **Retourenprodukte**: Detaillierte Auflistung der Produkte, die in den Retouren enthalten sind.

4. **Kreative Mitgestaltung:**
   - Obwohl Sie sich an der vorgegebenen Struktur orientieren sollen, ermutigen wir Sie, Ihre eigenen Ideen einzubringen. �berlegen Sie, welche zus�tzlichen Informationen in einem Onlineshop n�tzlich sein k�nnten und wie Sie diese in Ihrer Datenbank abbilden k�nnen.

#### **Ziel:**
Am Ende dieser Aufgabe haben Sie eine funktionierende PostgreSQL-Datenbank entwickelt, die als Basis f�r einen Onlineshop dient. Diese Datenbank kann sp�ter als Grundlage f�r die Entwicklung einer vollst�ndigen Anwendung verwendet werden.

#### **Erweiterung f�r Fortgeschrittene:**
Teilnehmer, die die Aufgabe erfolgreich abgeschlossen haben und zus�tzliche Herausforderungen suchen, k�nnen versuchen, eine einfache Anwendung zu entwickeln, die auf dieser Datenbank aufbaut. Dies k�nnte eine Webanwendung sein, die mit der Datenbank interagiert.