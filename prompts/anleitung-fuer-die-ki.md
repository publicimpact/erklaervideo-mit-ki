# Anleitung für die KI

Diesen Text als Ganzes an Claude Code oder einen ähnlichen Coding-Agenten geben, der auf deinem Rechner arbeiten darf. Dazu schreiben: „Bau mit mir ein Video nach dieser Anleitung zum Thema …“

---

Du baust mit mir ein kurzes Erklärvideo nach diesem Fundament. Übernimm das Prinzip, nicht das Beispiel: Thema, Figur, Farben, Takte und Texte entstehen für mein Thema neu. Arbeite in Phasen, zeig mir jedes Ergebnis und warte auf mein Go. Bevor etwas Geld oder Credits kostet, nennst du mir die Kosten.

## Frag mich zuerst

1. Welche Frage beantwortet das Video?
2. Welches echte Material gibt es und darf ich es zeigen?
3. Welche Stimme: mein Stimmklon oder eine Profistimme?
4. Welcher Look für die Figur und welche Akzentfarbe?
5. Wie lang, für welche Plattform?

## Prinzip

Eine Frage, ein echter Beweis, eine Erkenntnis. Echt stellt die Frage, eine Figur ohne Gesicht erklärt, echt beweist. Das echte Material läuft in einem Leuchtkasten im Bild; die Kamera fährt hinein, bis es den ganzen Screen füllt. Gibt es keine Aufnahmen, nimm echte Quellen: Dokumente, Screenshots, Messwerte. Jede Grafik sagt genau eine Sache und bleibt lange genug stehen, um sie zu lesen.

## Dramaturgie

| Anteil der Länge | Takt | Beispiel Iron Summit |
|---|---|---|
| 0 bis 7 % | **Frage.** Steht als Titel im Bild, die Figur stellt die Lage dar. | Figur mit Hantel auf dem Gipfel |
| 7 bis 19 % | **Echter Beweis.** Zeig, dass es wirklich passiert ist. | Leuchtkasten mit Poster, dann echte Szenen |
| 19 bis 30 % | **Aufbau.** Wie wurde getestet, womit gemessen? | Hantel in Teilen, echte Uhr am Handgelenk |
| 30 bis 46 % | **Mechanismus.** Was passiert im Körper, im System, in der Maschine? | Lunge: rund 40 % weniger Sauerstoff je Atemzug |
| 46 bis 74 % | **Messung.** Die eine Zahl, groß und mit Vergleich. | 98 gegen 67 % Sauerstoff im Blut |
| 74 bis 82 % | **Kipppunkt.** Der Moment, in dem es ernst wird. | 68 %, Abflug mit dem Hubschrauber |
| 82 bis 100 % | **Erkenntnis.** Antwort auf die Frage, mit Zahl. | „Macht Höhe fitter? Kaum.“ |

## Stimme

Schreib zuerst das Skript: 12 bis 14 kurze Sätze, je ein Gedanke, Zahlen ausgeschrieben; ich gebe es frei. Dann die Stimme mit ElevenLabs: das ganze Skript in einem Durchgang, mit Zeitstempeln (with-timestamps). Nie Satz für Satz erzeugen, nie schneiden, strecken oder beschleunigen. Das Bild richtet sich nach der Stimme. Für einen ruhigen Ton: eleven_v4, am Textanfang `[soft-spoken, calm, intimate narration, low energy, steady pace]`, Stabilität 0,9, Tempo 0,95.

## Bild

Startbilder mit GPT Image 2.5 über Higgsfield, in jeder Szene dieselbe Beschreibung der Figur, wortgleich. Daraus 5-Sekunden-Clips mit Wan 3.0 Prime in 720p; erst einen testen, dann den Rest. Prüf jeden Clip auf erfundene Personen, verformte Hände und Objekte, bevor du ihn mir zeigst. Grafiken, Zähler, Untertitel und Zooms baust du als HTML-Ebene und legst sie per Code über das Video (Chrome headless, ffmpeg). Echtes Material nur überlagern, nie neu rendern.

## Ton

Musik leise unter der Stimme, sie duckt, wenn gesprochen wird. Effekte nur auf Bildereignisse wie Zoom, Blitz oder Zähler. Am Ende −16 LUFS.

## Fakten

Jede Zahl braucht eine Quelle: Studie, offizielle Seite oder Originalaufnahme mit Zeitstempel. Was keine Quelle hat, kommt nicht ins Bild. Zahl in Stimme und Bild gleich gerundet. Ein Messwert im Bild steht immer mit dem, was gemessen wurde.

## Ablauf

1. Fragen klären.
2. Recherche mit Quellenliste.
3. Skript.
4. Stimme in einem Durchgang.
5. Wortzeiten messen, eine Zeitdatei für Bild, Schrift und Ton.
6. Startbilder und Clips.
7. Schnitt, Grafiken, Untertitel.
8. Musik, Effekte, Mischung.
9. Prüfen: Transkript gegen Skript, Einzelbild an jeder Zahl, auf dem Handy ansehen.

