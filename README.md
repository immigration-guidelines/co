# Immigration guidance: Colombia

Published guidance that Colombia's migration authority issues to the officials who decide migration cases, collected in November 2026.

- **Guidance:** 66 documents. Migración Colombia publishes the working documents of its quality-management system for its three case-handling processes (border control, foreigners' registration and permits, verification and sanctions): a process manual, procedures as flow charts, and about 35 current guides (guías) and instructions (instructivos) written for migration officers, in `sig/` and `guias/`.
- **Procedural acts:** 24 resolutions and directives that officers work from, in `actos/` and `cancilleria/`. `index.tsv` marks each file as guidance or procedural act, with its title, date, issuing body, source address and an English gloss of the title.
- **Not published:** the Foreign Ministry, which decides visas and refugee status, publishes no officer guidance, only resolutions and information for applicants. Its website also refuses automated access.
- **One file is stored in three parts:** the Excel workbook of norms for the border-control process is 115 MB, over GitHub's 100 MB file limit, and does not shrink when compressed because the acts embedded in it are already compressed. It is in `sig/control-migratorio/` as `….xlsx.part0`, `.part1` and `.part2`. To get the workbook back, download all three and join them in order: `cat *.xlsx.part0 *.xlsx.part1 *.xlsx.part2 > workbook.xlsx` on Linux or macOS, or `copy /b a.part0+a.part1+a.part2 workbook.xlsx` on Windows. The `.sha256` file beside them holds the checksum of the joined file.
- `NOTES.txt` records what was checked; `not-obtained.tsv` lists what is known to exist but could not be fetched. For all jurisdictions see [MISSING.md](https://github.com/immigration-guidelines/.github/blob/main/MISSING.md) and the [organisation page](https://github.com/immigration-guidelines).

The files are unmodified copies of what the source published. The documents remain the work of the authorities that published them.
