![todo_landing_img](https://github.com/user-attachments/assets/f4f92929-d22d-40a3-88ea-770f0dc6a09d)

# Willkommen bei Optimizer

Bei diesem Repository handelt es sich um eine Prüfungsleistung im Rahmen eines Wirtschaftsinformatikstudiums (B.Sc) an der AKAD University.

## Was ist Optimizer?

Bei Optimizer handelt es sich um eine (mobile) WebApp mit XAMPP als Backend zur Selbstorganisation in Form einer To-Do-Liste.
Die Besonderheit an Optimizer ist die Möglichkeit Aufgabenpakete (Todos) in kleinere Pakete (Tasks) aufzuteilen. Ähnlich wie dies bspw. bei
Azure DefOps auch möglich ist.
Passend dazu hat die Applikation einen Fokusmodus, welcher den Anwender dazu zwingt sich auf eine gewisse Anzahl an begonnen Todos zu konzentrieren.

## Ist die Applikation abgeschlossen und voll einsatzbereit?

Ja und nein.

Die Applikation per se ist lauffähig, jedoch enthält der Code noch bekannte Bugs.
Ebenfalls fehlt die Responsivität der Applikation. Voraussetzungen wurden geschaffen, jedoch nicht umgesetzt.
Die Applikation ist zudem noch nicht vollständig umgesetzt.

## Welche Vorraussetzungen braucht die Applikation um lauffähig zu sein?

Optimizer benötigt [XAMPP](https://www.apachefriends.org/download.html) um ausgeführt zu werden.
Des Weiteren wird ein Browser benötigt.
Getestet wurde die App auf Google Chrome.

## Wie starte ich den Optimizer?

Zuerst sollte der Apache Server und die MySQL (MariaDB) in XAMPP gestartet werden.
Der Einstiegspunkt für die App ist die landingpage.html.

## Die Datenbank nach dem Starten ist leer.

Nachdem Starten der App über die landingpage.html (Klicken auf den Button oder das Bild), prüft die App ob auf dem Rechner bereits eine Datenbank existiert,
und sollte dies nicht der Fall sein, wird eine neue angelegt.

# Architektur

![Optimizer Architektur](https://github.com/user-attachments/assets/18e55f80-ab35-47f2-bc2a-50c47990cee1)
