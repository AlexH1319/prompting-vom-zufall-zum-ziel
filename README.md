# Workshop: Prompting – vom Zufall zum Ziel

Interaktives Workshop-Handout für die **Nacht der Technik** (Microsoft, Köln · 3. Juli 2026):
Wie wird aus einer vagen Frage ein präziser Auftrag an die KI? Der Workshop zeigt die
**ZIEL-Formel** (Ziel, Informationen, Erwartungen, Leitplanken) und das Prinzip
*„80 % behalten – 20 % ändern"* – und mündet in die Challenge **„Toy Yourself"**:
eine hochwertige Vinyl-Toy-Figur, die dich repräsentiert, erstellt mit **Microsoft Copilot**.

Auf der Seite findest du den kompletten **Bild-Prompt** mit einem **Kopieren-Button**.
Die farbig markierten Platzhalter `[ … ]` füllst du mit deinen eigenen Angaben.

Die Seite ist eine einzelne, eigenständige HTML-Datei (kein Backend, keine Datenerfassung)
und auf maximale Kompatibilität ausgelegt – inkl. eingebetteter Browser (z. B. Microsoft Teams).

## Veröffentlichen (GitHub Pages) & QR-Code

1. `site/index.html` in ein GitHub-Repo pushen und **GitHub Pages** aktivieren
   (Settings → Pages → Branch `main`, Ordner `/site` oder Root).
2. Aus der Live-URL einen **QR-Code** erzeugen (z. B. <https://www.qrcode-monkey.com> oder ein SVG-QR-Generator).
3. Im `index.html` den vorbereiteten `<div class="qr-badge" … hidden>` im Header nutzen:
   das Attribut `hidden` entfernen und das QR-`<svg>` an der markierten Stelle einfügen.

## Inhalt / Quelle

Inhaltliche Grundlage ist die Workshop-Präsentation `Prompting-Nacht-der-Technik.pptx`
und der Bild-Prompt `Prompt.txt` (beide im übergeordneten Ordner).
