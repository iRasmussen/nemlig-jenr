# nemlig-jenr

Eksempelprojekt til undervisning i webteknologier på 2. semester
Professionsbachelor i Økonomi & IT
Erhvervsakademi København

Formålet med projektet er at vise en trinvis udvikling fra en statisk webside til en simpel webapplikation med klar adskillelse mellem præsentation, logik og data.

Projektet udvikler sig i små versioner, hvor hvert trin introducerer nye teknologier og arkitektoniske principper.

---

# Versioner

| version | indhold                   |
| ------- | ------------------------- |
| v0302a  | statisk HTML              |
| v0302b  | Python webserver          |
| v0302c  | template-struktur (Flask) |

Senere versioner udvider projektet med database og fuld trelagsarkitektur.

Alle versioner kan hentes via **GitHub Releases**, så hver fase i udviklingen kan afprøves separat.

---

# Udviklingsprogression

Projektet udvikler sig gradvist efter følgende model:

```
statisk HTML
→ Python webserver
→ templates
→ database
```

Dette svarer til en klassisk trelagsstruktur:

```
Præsentation
HTML + CSS

↓
Applikationslogik
Python / Flask

↓
Data
SQL-database
```

---

# Projektstruktur

Projektets struktur vil gradvist udvikle sig til noget i denne retning:

```
nemlig-jenr
│
index.html
webserver.py
│
templates/
static/
│
db/
schema.sql
demo_data.sql
```

Formålet er at tydeliggøre adskillelsen mellem:

```
UI
HTML / CSS

Logik
Python / Flask

Data
database
```

---

# Anvendelse i undervisning

Projektet bruges i undervisningen på 2. semester til at demonstrere:

* grundlæggende webteknologier
* simpel serverlogik i Python
* separation mellem præsentation og logik
* introduktion til databaseintegration

Studerende kan hente specifikke versioner via **GitHub Releases** og afprøve hvert trin i udviklingen lokalt.

---

# Om versionernes README

Hver version i *Releases* indeholder sin egen README, som forklarer:

* hvordan versionen startes
* hvilke krav der er til Python og pakker
* hvilke filer der indgår i versionen

Repository-README'en beskriver derimod projektets samlede idé og udviklingsforløb.
