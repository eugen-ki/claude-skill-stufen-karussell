---
name: stufen-karussell
description: Use when the member wants a step-by-step Instagram carousel with finished slide images (Stufen-Karussell, Schritt-für-Schritt-Karussell, Anleitung als Karussell, "mach ein Karussell mit 6 Schritten zu X", Karussell mit Video-Cover), or wants a carousel that keeps people swiping to the end.
---

# Stufen-Karussell

Thema rein, 10 fertige Folien als Bilder raus, optional mit einem bewegten Cover als 6-Sekunden-Video. Das Thema wird in 6 Stufen zerlegt, und jede Folie hat eine feste Aufgabe, damit Leute bis zum Ende wischen.

Brauchst du nur Text ohne Bilder, nimm den Skill **karussell-texter**.

## Die 6 Stufen der Aufmerksamkeit

Wer bis zum Ende dranbleibt, durchläuft sechs Stufen. Jede Folie bedient eine davon.

| Stufe | Was im Kopf passiert | Wo im Karussell |
|---|---|---|
| 1 **Reiz** | Das Auge bleibt hängen: Farbe, Kontrast, Bewegung. Dauert 1 bis 2 Sekunden, noch ohne Verstehen. | Cover-Bild, bewegtes Cover |
| 2 **Frage** | Eine offene Frage entsteht im Kopf. Sie muss die Zielgruppe betreffen, sonst wischt sie weiter. | Cover-Text |
| 3 **Spannung** | Der Leser rät mit. Klare Fakten helfen beim Raten. Kurz vor der Antwort eine Wendung, dann geht die Spannung neu los. | Übersicht mit verschwommenen Stufen, Wende-Folie |
| 4 **Auflösung** | Die Frage wird beantwortet, am besten nicht so, wie man es erwartet hätte. | Stufe 6, der Höhepunkt |
| 5 **Sympathie** | Der Leser mag die Person hinter dem Post: Gesicht, Lächeln, echte Hilfe. | Ein eigenes Foto oder ein persönlicher Satz |
| 6 **Verlässlichkeit** | "Von dieser Person kommt immer etwas, das mir hilft." Daraus wird Wiedererkennung. | Abschluss-Folie, gleicher Look bei jedem Karussell |

Stufe 1 bis 4 macht jedes gute Karussell. Stufe 5 und 6 entstehen über viele Posts. Deshalb bleibt der Look immer gleich.

## Schritt 1: Eingaben

Lies `~/.claude/mein-profil.md` (Zielgruppe, Stimme, Gratis-Hilfe, Standard-Aufruf, Handle). Fehlt sie, frag kurz nach Zielgruppe und Instagram-Namen oder biete **mein-profil** an.

Frag in **einer** Nachricht nur, was fehlt:
- Das Thema und was der Leser danach kann.
- Woher kommen die Bilder? (siehe Schritt 4: A ohne Fotos, B eigene Fotos, C KI-Bilder, D Gratis-Fotos). Keine Antwort heißt **A**.
- Soll das Cover ein bewegtes Video werden? Keine Antwort heißt nein.

## Schritt 2: Die 6 Stufen finden

- Genau 6 Stufen, in der Reihenfolge, in der man sie macht. Jeder Name 1 bis 2 einfache Wörter ("Füße", "Prompt").
- Stufe 1 bis 4 und Stufe 5 bis 6 bilden zwei Gruppen mit je einer Idee. Die Wende-Folie sagt sie: "Stufe 1 bis 4 machen es SICHER. Stufe 5 und 6 machen es STARK."
- Stufe 6 ist der Höhepunkt, die Auflösung. Hier kommt das, womit keiner rechnet.
- Die Wende-Folie darf andere Wörter nehmen als SICHER und STARK, Hauptsache zwei kurze Gegensätze, die zum Thema passen.
- Ein Kommentar-Wort in Großbuchstaben, nur wenn es wirklich etwas zu schicken gibt und jemand antwortet (von Hand oder mit Automatisierung). Sonst wird die Abschluss-Folie ein "Folgen" oder "Speichern".
- Cover-Text: ein Fehler oder ein Versprechen, das die Frage im Kopf auslöst ("du machst es VERMUTLICH FALSCH").

Lässt sich das Thema nicht ehrlich in 6 Stufen zerlegen, sag das und schlag einen Blickwinkel vor, der passt.

## Schritt 3: Folienplan (genau diese Reihenfolge)

| Folie | Art | Aufgabe |
|---|---|---|
| 1 | Cover | Reiz und Frage. Zeile + großes Wort + leise Zeile. Kein Handle, kein Pfeil. |
| 2 | Übersicht | "6 Stufen zum / GROSSES ERGEBNIS". Treppe mit verschwommenen Namen, damit man weiterwischt. |
| 3 bis 6 | Stufe 1 bis 4 | Zeile "Stufe eins" + großes Wort (Stufen-Name) + leise Zeile (wie es geht). |
| 7 | Wende | Zwei Gruppen benennen + Kommentar-Wort (oder Hinweis auf die letzte Folie). |
| 8 bis 9 | Stufe 5 und 6 | Stufe 6 ist der Höhepunkt. |
| 10 | Abschluss | Treppe klar lesbar + eine Bitte + was man bekommt. |

Textregeln:
- Jede Folie hat denselben Aufbau: kleine Zeile, großes Wort, leise Zeile. Mittig. Sonst nichts.
- Großes Wort: 1 bis 2 Wörter, Großbuchstaben. Zweite Zeile mit `<br>`. Die Vorlage verkleinert zu lange Wörter selbst.
- Kleine Zeile oben: höchstens 5 Wörter, eine Zeile.
- Leise Zeile: klein und locker, höchstens 8 Wörter. Genau eine kurze Stelle (1 bis 3 Wörter) mit `<u>` unterstreichen.
- Untere Zeile der Wende-Folie: höchstens 10 Wörter.
- Keine Absätze, kein Fettdruck, keine erfundenen Fachwörter. "Stufe eins", nicht "Level eins".
- Keine Gedankenstriche als Satzzeichen. Keine erfundenen Zahlen.
- Sympathie (Stufe 5 der Aufmerksamkeit): Mindestens eine Folie zeigt das Mitglied selbst (eigenes Foto) oder sagt einen persönlichen Satz. Nur Echtes: Weißt du nichts Persönliches, frag einmal nach ("Was hast du selbst dabei falsch gemacht?") oder lass es weg.
- Im Abschluss nur versprechen, was es wirklich gibt.

## Schritt 4: Bilder

Jede Folie mit Foto zeigt **eine ruhige Szene**, das Motiv klein in der unteren Hälfte. Die obere Hälfte bleibt frei für den Text. Wechsle die Szenen ab: Gegenstand auf Wiese, Gegenstand von oben auf Farbfläche, Himmel, Nahaufnahme vor glatter Wand. Zeigt ein Bild eine Person bei einer Übung oder Handlung, muss die Haltung richtig und sicher sein.

| Quelle | Wann | Was du tust |
|---|---|---|
| **A ohne Fotos** | Schnell, kostenlos, immer möglich | Alle Folien `class="folie ohne-foto"` (dunkel, Text mittig), die Abschluss-Folie `class="folie flaeche"`. So ist die Vorlage schon eingestellt. |
| **B eigene Fotos** | Am besten für Sympathie | Das Mitglied legt Handy-Fotos in `bilder/` ab (`01.jpg`, `03.jpg` ...). Sag, welche Folie welches Motiv braucht. |
| **C KI-Bilder** | Mit ChatGPT, Gemini oder einem anderen Bild-Programm, das das Mitglied schon hat | Schreib `bild-prompts.md`: pro Folie ein Prompt, Format 4:5, mit dem Zusatz unten. Das Mitglied erzeugt die Bilder im Chat und speichert sie als `bilder/01.jpg` usw. |
| **D Gratis-Fotos** | Ohne eigene Bilder, ohne KI | Suchbegriffe pro Folie für Pexels oder Unsplash nennen. Nur Fotos mit freier Lizenz. |

Zusatz für jeden KI-Bild-Prompt (C):
> Analoges Filmfoto, weiches Tageslicht, leicht entsättigte Farben, sichtbares Filmkorn, ruhige minimalistische Komposition, Motiv klein in der unteren Hälfte, obere Hälfte leer für eine Überschrift, keine Schrift, keine Buchstaben, keine Logos. Hochformat 4:5.

Bei KI-Bildern mit echt wirkenden Personen: Instagram verlangt eine KI-Kennzeichnung. Weise darauf hin.

## Schritt 5: Folien bauen

1. Ordner `karussell-<thema>/` im aktuellen Ordner anlegen, darin `bilder/` und `folien/`.
2. `assets/vorlage.html` aus diesem Skill-Ordner nach `karussell-<thema>/karussell.html` kopieren.
3. In `karussell.html`:
   - Farben in `:root` an die Marke anpassen, falls das Profil Farben nennt. Sonst die Farben der Vorlage lassen. Danach bei jedem Karussell gleich lassen.
   - `@deinname` durch den Instagram-Namen ersetzen.
   - Texte der 10 Folien eintragen, `STUFEN` im Skript unten mit den 6 Stufen-Namen füllen.
   - Fotos (B, C, D): bei der Folie `ohne-foto` aus der Klasse nehmen und `style="background-image:url(bilder/01.jpg)"` an die `section` setzen. Heller Fotohintergrund: `class="folie hell"`.
4. Prüfe, welcher Browser da ist (Datei unter dem Pfad unten vorhanden). Dann jede Folie als Bild speichern, im Kopfmodus. Pro Folie `#f1` bis `#f10`. Pfade überall mit Schrägstrichen `/` schreiben:

```
"<BROWSER>" --headless=new --disable-gpu --hide-scrollbars --allow-file-access-from-files --force-device-scale-factor=1 --virtual-time-budget=8000 --window-size=1080,1350 --screenshot="<ABSOLUTER-PFAD>/folien/folie-01.png" "file:///<ABSOLUTER-PFAD>/karussell.html#f1"
```

`<BROWSER>` ist:
- Windows Chrome: `C:\Program Files\Google\Chrome\Application\chrome.exe`
- Windows Edge (immer vorhanden): `C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe`
- Mac: `/Applications/Google Chrome.app/Contents/MacOS/Google Chrome`

Unter Windows: `file:///C:/Users/...`, mit Laufwerksbuchstaben. Leerzeichen und Umlaute im Pfad sind in Ordnung.

Gut zu wissen: Die Schriften kommen aus dem Internet, beim Rendern braucht der PC also Internet. Der Browser schreibt "bytes written" als Meldung. In PowerShell erscheint das rot, ist aber kein Fehler. Entscheidend ist, dass die PNG-Datei da ist.

## Schritt 6: Cover-Video (optional, kostenlos)

Braucht ffmpeg (Windows: `winget install Gyan.FFmpeg`, Mac: `brew install ffmpeg`). Das Foto von Folie 1 zoomt langsam rein und wieder raus, der Text steht still. Ende und Anfang sind gleich, deshalb läuft das Video als nahtlose Schleife.

1. Nur den Text von Folie 1 ohne Hintergrund speichern: wie oben, aber mit `--default-background-color=00000000`, Ausgabe `folien/cover-text.png` und Adresse `karussell.html?nur-text#f1`.
2. Video bauen:

```
ffmpeg -y -loop 1 -i bilder/01.jpg -i folien/cover-text.png -filter_complex "[0:v]scale=1080:1350:force_original_aspect_ratio=increase,crop=1080:1350,scale=2160:2700,zoompan=z='1.06+0.04*sin(2*PI*on/144)':x='iw/2-(iw/zoom/2)':y='ih/2-(ih/zoom/2)':d=1:s=1080x1350:fps=24,trim=end_frame=144,noise=alls=6:allf=t,format=yuv420p[bg];[bg][1:v]overlay=0:0,format=yuv420p" -frames:v 144 -c:v libx264 -crf 18 -movflags +faststart -an folien/cover-loop.mp4
```

3. Prüfen: `ffprobe -v error -show_entries format=duration -of csv=p=0 folien/cover-loop.mp4` muss `6.000000` zeigen.

Ohne Foto auf Folie 1 (Quelle A) gibt es kein Cover-Video, nur das Bild.

## Schritt 7: Selbst prüfen

Sieh dir jede PNG-Datei an:
- Verdeckt Text das Motiv? Dann Motiv tiefer (neues Bild) oder `class="hell"` / anderer Hintergrund.
- Ist der Text überall lesbar?
- Bricht ein Wort ungewollt um?
- Stimmt Haltung und Körperbau von Personen? Eine falsche Haltung in einer Anleitung ist ein Fehler.

## Schritt 8: Übergeben

Sag dem Mitglied:
- Reihenfolge zum Posten: `folien/cover-loop.mp4` (oder `folie-01.png`), dann `folie-02.png` bis `folie-10.png`.
- Welche Bilder noch fehlen oder ersetzt werden sollten.
- Das Versprechen im Abschluss, damit es bestätigt, dass es das wirklich verschickt.
- Bei KI-Bildern: KI-Kennzeichnung beim Posten einschalten.

## Häufige Fehler

| Fehler | Besser |
|---|---|
| Cover beschreibt das Thema ("Tipps zum Kniebeugen") | Cover löst eine Frage aus ("du machst es VERMUTLICH FALSCH") |
| Stufen-Namen auf Folie 2 lesbar | Verschwommen lassen, sie sind der Grund zum Wischen |
| Stufe 6 ist die schwächste | Den überraschendsten Punkt ans Ende |
| Jedes Karussell sieht anders aus | Gleiche Farben und Schriften, damit man dich wiedererkennt |
| Abschluss verspricht etwas, das es nicht gibt | Nur echte Gratis-Hilfe, sonst "folgen" oder "speichern" |
