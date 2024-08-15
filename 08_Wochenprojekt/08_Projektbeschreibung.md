# 8 SQL und MySQL vs. MariaDB

Die Teilnehmenden erstellen eine Datenbank f�r ein Soziales-Netzwerk.  
Dabei ist ausschlie�lich die Datenbank Teil des Projektes.  
Diese kann von besonders motivierten und leistungsstarken Teilnehmenden um eine entsprechende Anwendung erweitert werden.  
Die Datenbank soll im Wesentlichen Benutzer und Postings enthalten.  
Erweiternd kann die Datenbank erweitert werden um Kommentare/Bewertungen.  
  
Dabei sollen folgende Sachverhalte abbilden:  

1. Benutzer haben einen Namen und ein Profil, in dem sie weitere Informationen �ber sich teilen k�nnen.
- [ ] Benutzername
- [ ] E-Mail
- [ ] Profiltext
- [ ] Geburtstag
- [ ] Links zu Profilen auf anderen Plattformen, z.B. Facebook, Instagram, etc.
- [ ] Arbeitgeber
- [ ] Hobbys
- [ ] etc.
2. Benutzer haben die M�glichkeit Postings auf der Plattform anzulegen. Dabei k�nnen neben einem Text auch Links oder Dateien wie Bilder angehangen werden.
- [ ] PostingText
- [ ] File(s)
- [ ] Ref.Link(s)
- [ ] Hashtags (als Tagging Mechanik)
- [ ] Andere Nutzer k�nnen als Tag hinzugef�gt werden
3. Benutzer k�nnen zu einzelnen Postings Kommentare abgeben.
- [ ] Kommentartext
- [ ] Benutzer
- [ ] Zeitpunkt
4. Gruppen k�nnen angelegt werden, in denen sich Benutzer Organisieren k�nnen
- [ ] Gruppenname
- [ ] Gruppenbeschreibung
- [ ] Gruppenbild
- [ ] Gruppentags
5. Benutzer k�nnen sich in Gruppen organisieren
- [ ] Gruppe
- [ ] Benutzer
6. Benutzer k�nnen einzelne Postings Bewerten (gut/schlecht | Daumen hoch/Daumen runter)
- [ ] Wertung
- [ ] Benutzer
- [ ] Zeitpunkt  
  
Es ist den Teilnehmenden dabei freigestellt, wie diese Inhalte im Einzelnen modelliert werden, jedoch sollen die vermittelten Grunds�tze der Datenmodellierung eingehalten werden. Bewertungen k�nnen als Kommentare betrachtet werden. Ein m�gliches Datenmodell k�nnte folgende Tabellen mindestens enthalten:
- [ ] User
- [ ] Posts
- [ ] Comment
- [ ] Gruppen
