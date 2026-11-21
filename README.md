# Stufen-Karussell: fertige Karussell-Bilder mit Claude Code

Ein Claude-Code-Skill, der aus einem Thema ein Instagram-Karussell mit 10 fertigen Folien als Bilder macht. Das Thema wird in 6 Stufen zerlegt, und jede Folie hat eine feste Aufgabe, damit Leute bis zum Ende wischen. Auf Wunsch bekommst du ein bewegtes Cover als nahtlose 6-Sekunden-Schleife, kostenlos erzeugt auf deinem Rechner.

## Was du bekommst

- 10 Folien als PNG (1080 × 1350): Cover, Übersicht mit verschwommenen Stufen, 6 Stufen mit Fortschrittsanzeige, eine Wende-Folie und einen Abschluss.
- Texte nach den 6 Stufen der Aufmerksamkeit: Reiz, Frage, Spannung, Auflösung, Sympathie, Verlässlichkeit.
- Bilder nach deiner Wahl: ohne Fotos, eigene Fotos, KI-Bilder aus deinem ChatGPT- oder Gemini-Abo (der Skill schreibt dir die Prompts) oder Gratis-Fotos.
- Optional ein Cover-Video, das langsam zoomt, während der Text stillsteht.

## Installieren

1. Oben rechts auf **Code** und dann **Download ZIP** klicken. ZIP entpacken.
2. Im entpackten Ordner liegt der Ordner `stufen-karussell`. Kopiere genau diesen Ordner in deinen Skills-Ordner:
   - Windows: `C:\Users\<dein-name>\.claude\skills\`
   - Mac: `~/.claude/skills/`

   Gibt es den Ordner `skills` noch nicht, leg ihn an. Danach liegt die Datei unter `.claude/skills/stufen-karussell/SKILL.md`.
3. Claude Code neu starten.

## So benutzt du ihn

Tippe `/stufen-karussell` oder sag es einfach in deinen Worten, zum Beispiel:

> Mach mir ein Stufen-Karussell: wie du deine erste Kundenmail mit ChatGPT schreibst. Ohne Fotos.

## Tipp: zuerst dein Profil

Der Skill klingt nach dir, wenn du vorher einmal [mein-profil](https://github.com/eugen-ki/claude-skill-mein-profil) installierst und `/mein-profil` startest. Ohne Profil funktioniert er auch, er stellt dir dann ein paar kurze Fragen.

Nur Texte ohne Bilder? Dann passt [karussell-texter](https://github.com/eugen-ki/claude-skill-karussell-texter).

## Was du brauchst

- [Claude Code](https://claude.com/claude-code).
- Google Chrome oder Microsoft Edge (unter Windows ist Edge immer da). Damit werden die Folien zu Bildern.
- Internet beim Bauen (für die Schriften).
- Nur für das Cover-Video: ffmpeg (Windows: `winget install Gyan.FFmpeg`, Mac: `brew install ffmpeg`).

## Gut zu wissen

- Der Skill erfindet keine Zahlen oder Ergebnisse und verspricht im Abschluss nur, was es wirklich gibt.
- Farben und Schriften stellst du einmal ein. Danach sieht jedes Karussell gleich aus, damit man dich wiedererkennt.
- Bei KI-Bildern mit echt wirkenden Personen: KI-Kennzeichnung beim Posten einschalten.

## Lizenz

MIT, frei nutzbar und veränderbar. Siehe [LICENSE](LICENSE).
