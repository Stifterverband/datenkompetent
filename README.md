# datenkompetent - Beispielhafte Lehrformate und -strategien für die Data Literacy Education an deutschen Hochschulen
## Eine Publikation der Working Group: Data Literacy

### Intro

In dieser Publikation stellen verschiedene Mitglieder der Working Group unterschiedliche Tools und Strategien für die Lehre an Hochschulen vor. Dieses Repository dient der gemeinsamen Arbeit an der Publikation.  
Die Publikation wird als **Quarto Website** (genauer als Quarto Blog) umgesetzt. Weitere Informationen und eine sehr hilfreiche Anleitung findet ihr hier: <https://quarto.org/>. 

### Struktur

#### index.qmd
Dieses File ist die Startseite, auf die man kommt, wenn man die Seite besucht. 
Im Header werden Titel, Untertitel, Logo, Icon, Layout angegeben, außerdem wird die Struktur vorgegeben. 
unter "listing:" findet man die ordner "einleitung" und "posts", der erste Ordner enthält Grußworte und einen kleinen Text über die Working Group, der "posts"-Ordner enthält weitere Unterordner mit den Posts. 
Mit fields und type wird festgelegt, wie die Artikel auf der Startseite angezeigt werden. Wir haben uns für den "type" grid entschieden und lassen für die Einleitung und die Posts unterschiedliche Felder anzeigen. 

#### _quarto.yml
Hier können verschiedene globale Einstellungen vorgenommen werden. Besonders relevant hier: wir haben ein Cookie-Consent Feld eingefügt, außerdem einen Footer in dem die .qmd-Files aus dem Ordner "recht" verlinkt sind. 
Wichtig: unter format: theme: theme.scss wird das scss-File angegeben, das für den gesamten Style der Seite verwendet wird.

#### theme.scss
Hier wird die Seite gestylt. Farben, Schriftgrößen, Abstände. Wir folgen hier dem SV-CD soweit es geht. 

#### einleitung
In diesem Ordner liegen die Grußworte und die dazugehörigen Bilder. 

#### posts
Im Ordner "posts" finden sich Ordner zu den jeweiligen Artikeln. Diese enthalten (mindestens) folgende Dokumente:

    1. ein qmd-File, das einen YAML-Header mit Metadaten und euren Artikel im Markdown-Format enthält,
    2. citations.bib, das die Literatur im BibTeX-Format enthält,
    3. die Datei apa.csl, die den Zitationsstil (APA) festlegt,
    4. und ein png-File, das das "Coverbild" enthält. Dabei handelt es sich um Bilder, die mit dem aRtsy-Package generiert wurden.

Optional gibt es noch weitere Bilddateien, die dann eingebunden wurden. 

#### recht

Hier sind Impressum und Datenschutz.



