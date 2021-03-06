# Markdown Tutorial

Markdown ist eine vereinfachte Auszeichnungssprache. Markdown-Dateien sind einfache Text-Dateien, die zur Darstellung in HTML-Seiten umgewandelt werden. Das Markdown-Markup hat zum Ziel als Textdatei und als HTML-Seite leserlich zu bleiben.

## Basis

Die [Basissyntax](https://www.markdownguide.org/basic-syntax/) umfasst eine übersichliche Anzahl Befehle. Dazu eine Auswahl der wichtigsten:

## Text

Alle Text-Formatierungen.

### Überschriften

Markup:
```
# Überschrift 1
## Überschrift 2
### Überschrift 3
Normal
```

Output:

# Überschrift 1
## Überschrift 2
### Überschrift 3
Normal

### Fett

Markup:
```
**Lorem** ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.
```

Output:

**Lorem** ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.

### Kursiv

Markup:
```
*Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.
```

Output:

*Lorem* ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.

## Erweiterungen

Zur Basissyntax von Markdown gibt es verschiedene [Erweiterungen](https://www.markdownguide.org/extended-syntax/).

### Docsify

Das Set an Markdown-Befehlen wurde von Dritten erweitert. Mit [Docsify](https://docsify.js.org/) können umfassende Dokumentationen erstellt werden.

#### Wichtig

Markup:
```
!> Wichtige Notiz
```

Output:

!> Wichtige Notiz

#### Tabs

Markup:
```
<!-- tabs:start -->
#### **Schritt 1**
Schritt 1
#### **Schritt 2**
Schritt 2
<!-- tabs:end -->
```

Output:
<!-- tabs:start -->
#### **Schritt 1**
Schritt 1
#### **Schritt 2**
Schritt 2
<!-- tabs:end -->

### GitHub

GitHub ist eine Kollaborationsplattform zur Entwicklung von Software. Es erweitert Markdown um einige Funktionen.

#### Aufgaben

Aufgaben können auf GitHub direkt bearbeitet werden.

Markup:
```
- [ ] foo
- bar
- [x] baz
- [] bam <~ not working
  - [ ] bim
  - [ ] lim
````

Output:
- [ ] foo
- bar
- [x] baz
- [] bam <~ not working
  - [ ] bim
  - [ ] lim

### Mermaid

Mit [mermaid](https://mermaid-js.github.io/mermaid/) erstellt man  Diagramme basierend auf Markdown-inspierten Textdefinitionen.

#### Flowchart

Markup:
~~~
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
~~~

Output:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```