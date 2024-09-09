# 9 PostgreSQL

### **Aufgabe: Entwicklung einer PostgreSQL-Datenbank für einen Onlineshop**

#### **Einleitung:**
In dieser Aufgabe entwickeln Sie eine relationale Datenbank mit PostgreSQL für einen Onlineshop. Das Ziel ist es, eine funktionale Datenbank zu erstellen, die alle notwendigen Daten für den Betrieb eines einfachen Onlineshops verwaltet. Dies ist ein zentraler Bestandteil jedes modernen E-Commerce-Systems, da die Datenbank die Grundlage für die Verwaltung von Produkten, Kunden, Bestellungen und Zahlungen bildet.

#### **Aufgabenbeschreibung:**

1. **Verstehen des Konzepts:**
   - Sie erstellen eine Datenbank, die alle relevanten Informationen für den Onlineshop speichert. Dies umfasst das Anlegen und Verwalten von Benutzerkonten, Bestellungen, Produkten, Zahlungen und weiteren Aspekten des Shop-Betriebs.

2. **Erstellung der Datenbank:**
   - Nutzen Sie PostgreSQL, um die Datenbank zu entwickeln. Dabei sollten Sie die Tabellen, die in der beigefügten Grafikdatei dargestellt sind, als Grundlage verwenden.
   - Die notwendigen Tabellen umfassen:
     1. **Benutzerkonto**: Speicherung von Kundendaten wie Name, E-Mail-Adresse, Passwort und weitere persönliche Informationen.
     2. **Bestellung**: Verwaltung von Bestellungen, die Kunden im Shop aufgeben.
     3. **Bestellhistorie**: Aufzeichnung aller Bestellungen, um eine Historie zu erstellen.
     4. **Zahlung**: Speicherung von Zahlungsinformationen, die für die Bestellungen getätigt wurden.
     5. **Lager**: Verwaltung des Lagerbestands, um die Verfügbarkeit von Produkten sicherzustellen.
     6. **Produkt**: Informationen zu den im Shop angebotenen Artikeln, einschließlich Name, Preis, und Beschreibung.
     7. **Bestellposition**: Details zu den einzelnen Produkten innerhalb einer Bestellung.

3. **Optionale Erweiterungen:**
   - Für besonders motivierte Teilnehmer besteht die Möglichkeit, die Datenbank um zusätzliche Tabellen zu erweitern:
     8. **Retouren**: Verwaltung von zurückgesendeten Artikeln und den dazugehörigen Prozessen.
     9. **Retourenprodukte**: Detaillierte Auflistung der Produkte, die in den Retouren enthalten sind.

4. **Kreative Mitgestaltung:**
   - Obwohl Sie sich an der vorgegebenen Struktur orientieren sollen, ermutigen wir Sie, Ihre eigenen Ideen einzubringen. Überlegen Sie, welche zusätzlichen Informationen in einem Onlineshop nützlich sein könnten und wie Sie diese in Ihrer Datenbank abbilden können.

#### **Ziel:**
Am Ende dieser Aufgabe haben Sie eine funktionierende PostgreSQL-Datenbank entwickelt, die als Basis für einen Onlineshop dient. Diese Datenbank kann später als Grundlage für die Entwicklung einer vollständigen Anwendung verwendet werden.

#### **Erweiterung für Fortgeschrittene:**
Teilnehmer, die die Aufgabe erfolgreich abgeschlossen haben und zusätzliche Herausforderungen suchen, können versuchen, eine einfache Anwendung zu entwickeln, die auf dieser Datenbank aufbaut. Dies könnte eine Webanwendung sein, die mit der Datenbank interagiert.