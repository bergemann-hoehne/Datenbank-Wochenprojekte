# 8 SQL und MySQL vs. MariaDB

Die Teilnehmenden erstellen eine Datenbank für ein Soziales-Netzwerk.  
Dabei ist ausschließlich die Datenbank Teil des Projektes.  
Diese kann von besonders motivierten und leistungsstarken Teilnehmenden um eine entsprechende Anwendung erweitert werden.  
Die Datenbank soll im Wesentlichen Benutzer und Postings enthalten.  
Erweiternd kann die Datenbank erweitert werden um Kommentare/Bewertungen.  
  
Dabei sollen folgende Sachverhalte abbilden:  

1. Benutzer haben einen Namen und ein Profil, in dem sie weitere Informationen über sich teilen können.
- [ ] Benutzername
- [ ] E-Mail
- [ ] Profiltext
- [ ] Geburtstag
- [ ] Links zu Profilen auf anderen Plattformen, z.B. Facebook, Instagram, etc.
- [ ] Arbeitgeber
- [ ] Hobbys
- [ ] etc.
2. Benutzer haben die Möglichkeit Postings auf der Plattform anzulegen. Dabei können neben einem Text auch Links oder Dateien wie Bilder angehangen werden.
- [ ] PostingText
- [ ] File(s)
- [ ] Ref.Link(s)
- [ ] Hashtags (als Tagging Mechanik)
- [ ] Andere Nutzer können als Tag hinzugefügt werden
3. Benutzer können zu einzelnen Postings Kommentare abgeben.
- [ ] Kommentartext
- [ ] Benutzer
- [ ] Zeitpunkt
4. Gruppen können angelegt werden, in denen sich Benutzer Organisieren können
- [ ] Gruppenname
- [ ] Gruppenbeschreibung
- [ ] Gruppenbild
- [ ] Gruppentags
5. Benutzer können sich in Gruppen organisieren
- [ ] Gruppe
- [ ] Benutzer
6. Benutzer können einzelne Postings Bewerten (gut/schlecht | Daumen hoch/Daumen runter)
- [ ] Wertung
- [ ] Benutzer
- [ ] Zeitpunkt  
  
Es ist den Teilnehmenden dabei freigestellt, wie diese Inhalte im Einzelnen modelliert werden, jedoch sollen die vermittelten Grundsätze der Datenmodellierung eingehalten werden. Bewertungen können als Kommentare betrachtet werden. Ein mögliches Datenmodell könnte folgende Tabellen mindestens enthalten:
- [ ] User
- [ ] Posts
- [ ] Comment
- [ ] Gruppen
