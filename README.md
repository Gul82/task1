# task1

my first task to complete

- Lege ein Verzeichnis für das neue Projekt an (z.B. 'florafauna')
- Initialisiere ein lokales git Repository in dem Verzeichnis
- Füge eine Datei `index.html` mit initialer HTML-Boilerplate hinzu
- Mache einen ersten Commit mit der Commit-Message 'initial commit'
- Füge die Überschrift 'Tiere' hinzu
- Erstelle eine Liste mit den Tieren 'Hund', 'Katze' und 'Kanarienvogel'
- Verlinke die Tiernamen mit passenden Wikipedia-Artikeln
- Mache einen neuen Commit mit der Commit-Message 'added animal list'

Dein Chefredakteur ist zufrieden und Du kannst die Seite online stellen!
Als nächstes bittet er Dich, die Seite zu erweitern: Die Überschrift soll nun 'Tiere und Pflanzen' heißen und der Liste sollen die Pflanzen 'Eiche', 'Sonnenblume' und 'Löwenzahn' hinzugefügt werden.

Du machst folgendes:

- Erzeuge eine neue Branch `plants`
- Ändere die Überschrift in 'Tiere und Pflanzen'
- Füge die Pflanzen 'Eiche', 'Sonnenblume' und Löwenzahn der Liste hinzu
- Committe Deine Änderungen mit der Message 'added plants'

Dein Chefredakteur ist noch nicht zufrieden: Er möchte die neue Seite erst online stellen, wenn Du auch die Pflanzen mit Wikipedia-Artikeln verlinkt hast. Zuerst sollst Du aber eine wichtige Änderung an der Live-Version der Seite vornehmen: Die Überschrift _Tiere_ soll in _Haustiere_ geändert werden!

Du machst folgendes:

- Wechsel zurück in Deine Branch `main` (oder `master`)
- Ändere die Überschrift in 'Haustiere' und committe Deine Änderung mit der Message 'hotfix! changed main heading'

Danach arbeitest Du an Deiner Pflanzenliste weiter:

- Wechsel zur Branch `plants`
- Füge den drei Pflanzen Wikipedia-Links hinzu
- Committe Deine Änderung mit der Message 'added links to plants'

Der Chefredakteur findet Deine Pflanzenliste toll und bittet Dich, sie in `main` (oder `master`) zu mergen und dann live zu schalten.

Du machst folgendes:

- Wechsel zur Branch `main` (oder `master`)
- Versuche Deine Änderungen aus der Branch `plants` in `main` (oder `master`) zu mergen
- Es wird ein Konflikt bzgl. Deiner Überschriften auftreten: Löse ihn, indem Du die Überschrift 'Haustiere und Pflanzen' verwendest.
- Schaue Dir die Historie **aller** Commits als _Graph_ an und versuche, die Darstellung nachzuvollziehen.

**Bonus**

- Dein Chefredakteur würde gerne noch einmal die Liste mit den Pflanzen, aber **ohne** die Wikipedia-Links sehen. Was tust Du?
- Lade Dein Repo in Deinen Github-Account hoch.
