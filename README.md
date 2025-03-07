# Wahl ICT

Demo Repository um allen Git zeigen zu können.

## Notizen

Wir können hiet mit Markdown ganz einfache Notizen schreiben. Es ist auch
möglich auf andere [Dokumente](link.md) zu verlinken.

## Verschlüsselung

Wir können auch verschlüsselte Teile haben. Zum Beispiel [hier](secret.md).

## Mathe

Wir können auch Formeln einfügen:

$$x_{1,2} = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

## Code

Auch Code kann sehr einfach angezeigt werden:

```javascript
let name = "Wahl ICT";
console.log(`Willkommen zur ${name} Veranstaltung!`);
```

## Bilder

Wir können auch Bilder einfügen:

![Wahl ICT Logo](logo.jpg)

## Präsentationen

Wir können auch [Präsentationen](pres/intro.md) erstellen.

## Animationen

Markdown wird eigentlich einfach zu einem HTML-Dokument umgebaut, wir können
also HTML oder SVG darin verwenden.

<svg width="300" height="300" viewBox="0 0 100 100">
    <circle cx="50" cy="50" r="10" stroke="green" stroke-width="4" fill="yellow">
        <animate values="10;90;10" dur="1s" repeatCount="indefinite" attributeName="cx">
    </circle>
</svg>

## Links auf Kapitel

Überschriften werden zu Links, und wir können direkt darauf verlinken:
[Link auf Kapitel](#notizen)

## PDF mit Pandoc

Markdown kann nicht nur in eine HTML-Datei umgewandelt werden, sondern auch in
PDF oder DOCX, je nachdem was gerade gebraucht wird. Teilweise braucht es aber
noch Zusatzprogramme dafür, wie zum Beispiel Pandoc.

```bash
pandoc -s -i README.md -o README.pdf
```

Nicht alle teile können in PDF umgewandelt werden. Animierte SVG zum Beispiel
funktionieren nicht. Trotzdem kann die Markdown-Datei als einzige Quelle der
Wahrheit betrachtet werden, von dieser können dann die anderen Formate erzeugt
werden.

## Offline arbeiten dank Git

Git ermöglicht es ganz einfach lokal und offline zu arbeiten. Sobald man wieder
am Netz ist, kann man seine Arbeit mit den anderen synchronisieren. Das macht
die direkte zusammenarbeit ein wenig schwieriger, denn wenn an den gleichen
Stellen Änderungen passieren, müssen diese manuell synchronisiert werden.

Es gibt Features wie Liveshare, mit denen man das Problem umgehen kann. Das geht
jedoch nur wenn zur gleichen Zeit gearbeitet wird, was zwar im Unterricht der
Fall ist, sobald aber ausserhalb des Unterrichts gearbeitet wird, ist dies oft
nicht mehr gegeben.

Ein riesen Vorteil von Git ist, das ich mir die Änderungen von anderen Personen
anschauen kann. Ich sehe also auf einen Blick was seit dem letzten mal verändert
wurde.

## Mehrere Versionen

Die Zusammenarbeit über Git erfolgt immer über verschiedene `branches`. Genau
diese können auch verwendet werden, um verschiedene Versionen der Projekte zu
erstellen. Diese können dann wenn nötig zusammengeführt werden, oder einfach
verworfen werden wenn sie nicht mehr gebraucht werden.

## Excalidraw

Wir können auch viele unnötige Extensions installieren, wie zum Beispiel
Excalidraw. Das Resultat könnnen wir dann einfach einbinden.

![Excalidraw](board.excalidraw.png)

## Mermaid

Eine weitere unnötige Extension ist `Mermaid`. Hier können wir einfach Diagramme
beschreiben, diese werden dann gleich gezeichnet.

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
