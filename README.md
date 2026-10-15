# Chiamate: log of support calls and interventions

*Registro delle chiamate di assistenza e degli interventi*

**db** · 2001 · version 1.0  
Author: **Massimo Sbarbaro** ([ORCID 0009-0006-8965-9013](https://orcid.org/0009-0006-8965-9013))

## Overview

Chiamate is a small help-desk log used by an IT service company: each call records who called, date, type and description of the problem, intervention date, resolution date and solution, with notes.

I designed and programmed this application in 2001. It is published here in 2026 as part of the documented record of my software work, with a permanent DOI on Zenodo.

## Main functions

- Entry and browsing of the calls (`sMain`).
- Intervention and resolution dates and description of the solution.

## Data

Table `Generale` (calls).

## Technology

db, 97 format (.mdb), forms.

## Repository contents

| Path | Content |
|---|---|
| `database/` | The database application, emptied of all data. |
| `source/queries/` | SQL of the saved queries. |
| `docs/schema.md` | Tables and fields. |

## What is not included

The database is published **empty**: every table has been emptied, the file compacted and the unused space inside its pages overwritten with zeros, so no record of the original data survives. Logos of the organisations for which the program was built have been blanked inside the forms, and the names of organisations, people and places in captions and code have been replaced with neutral text of the same length; the application is otherwise the original file. The file is in the 1997 db format: it opens with the 1997–2010 versions of the database software; later versions must first convert it with an intermediate version.

## How to cite

Use the citation metadata in [`CITATION.cff`](CITATION.cff) (GitHub: *Cite this repository*).

> Sbarbaro, Massimo. 2001. *Chiamate: log of support calls and interventions*. Software (db, 2001), version 1.0. GitHub. https://github.com/massimosbarbaro/support-calls-log-db.

## License

Released under the [MIT License](LICENSE). © 2001 Massimo Sbarbaro.
