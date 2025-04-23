# Pages

## Landingpage

Der Anwender steigt über landingpage.html in die App ein.
Diese Seite hat direkte Abhängigkeiten im Frontend zu:

- services.js
- landingpage.js

## Overview

Auf der overview.html kann der Anwender zu folgenden Seiten navigieren:

- Archiv- und Gelöscht-Seite
- Fokusseite
- Todo

Diese Seite hat direkte Abhängigkeiten im Frontend zu:

- overview.js
- services.js

## Todo

Auf der todo.html können neue Todos angelegt oder vorhandene bearbeitet werden.

Über diese Seite hat der Anwender Zugriff auf task.html

Diese Seite hat direkte Abhängigkeiten im Frontend zu:

- todo.js
- services.js

### Task

Auf der task.html können neue Tasks an ein Todo angehängt werden oder bestehende bearbeitet werden.

Diese Seite kann ausschließlich über todo.html erreicht werden.
Für die spätere Entwicklung könnte eine "tasklist.html" entwickelt werden, welche lediglich alle Tasks eines Todos enthält und
besseren Überblick über alle vorhandene Tasks eines Todos bietet.

Diese Seite hat direkte Abhängigkeiten im Frontend zu:

- task.js
- services.js

## Archiv und Gelöscht

Auf der archiv.html findet der Anwender alle Todos mit dem Status 5 (= Beendet).

Von dieser Seite aus kann der Anwender ausserdem zu deleted.html (gelöschte Todos (Status = 1))  navigieren.

Diese Seite hat direkte Abhängigkeiten im Frontend zu:

- archiv.js
- deleted.js
- services.js

## Fokus

Auf der focus.html kann der Anwender das Limit für aktive (Status = 4) Todos und Tasks einstellen.
Diese Funktion ist elementarer Bestandteil der App, da sie für die Regulierung des Work-In-Progress des Anwenders verantwortlich ist.

Diese Seite hat direkte Abhängigkeiten im Frontend zu:

- focus.js
- services.js

# Wichtig
Die Seiten haben logischerweise Abhängigkeiten in das Backend.
Jeder "index"-Aufruf im Frontend steuert das Backend an.


