# Prompt: YouTube-Wissensbasis aufbauen

Eigene Version der „Level 4“-Idee (nicht Hassids Original-Prompt, der ist kostenpflichtig).

> Hinweis: In der Claude-Cloud-Umgebung ist YouTube standardmäßig gesperrt. Entweder
> youtube.com in den Umgebungseinstellungen freigeben, Claude Code auf dem eigenen Rechner
> nutzen, oder Transkripte selbst kopieren (YouTube → „…mehr“ → „Transkript anzeigen“).

## Zum Kopieren

```
Lies zuerst marketing/CLAUDE.md.

Baue eine Wissensbasis zu [NAME] zum Thema [THEMA]:
1. Finde die 10 neuesten und längsten YouTube-Videos/Podcasts, in denen [NAME] selbst spricht
   (keine Videos anderer Leute über [NAME], keine Shorts).
2. Zeig mir die Liste mit Titel, Datum, Länge und Link, bevor du weitermachst.
3. Lade danach die Transkripte (z. B. mit yt-dlp oder youtube-transcript-api) und speichere
   jedes nach dem Schema aus CLAUDE.md unter marketing/quellen/.
4. Schreib eine Übersicht nach marketing/quellen/[name]/_uebersicht.md:
   die 10 wichtigsten Kernaussagen, jeweils mit Datei als Quelle.
5. Committe alles mit einer kurzen Nachricht.
```

## Danach fragen, zum Beispiel

```
Was würde [NAME] laut den Quellen einer kleinen Hobby-Astrologie-Website raten,
um mehr Leser zu bekommen? Gib 20 Ideen von üblich (1) bis originell (20), mit Quellen.
```
