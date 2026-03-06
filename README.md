# nemlig-jenr

Eksempelprojekt til undervisning i webteknologier.
2. semester – Økonomi & IT
Erhvervsakademi København

Formålet med projektet er at vise en trinvis udvikling fra en statisk webside til en simpel webapplikation med klar adskillelse mellem præsentation, logik og data.

## Versioner

| version | indhold                   |
| ------- | ------------------------- |
| v0302a  | statisk HTML              |
| v0302b  | Python webserver          |
| v0302c  | template-struktur (Flask) |

Senere versioner udvider projektet med database og fuld trelagsarkitektur.

## Struktur

Projektet udvikler sig gradvist efter følgende model:

```
HTML
→ Python webserver
→ templates
→ database
```

Dette svarer til en klassisk trelagsstruktur:

```
UI (HTML/CSS)
↓
Logik (Python / Flask)
↓
Data (database)
```

## Anvendelse i undervisning

Projektet bruges i undervisningen på 2. semester til at demonstrere:

* grundlæggende webteknologier
* simpel serverlogik i Python
* separation mellem præsentation og logik
* introduktion til databaseintegration

Studerende kan hente specifikke versioner via **GitHub Releases** for at afprøve hvert trin i udviklingen.
