# kafkas-ict-selector
ICT Selector

## Δεδομένα
Η σελίδα (`index.html`) δεν περιέχει δεδομένα. Διαβάζει 5 αρχεία Excel από τον ίδιο φάκελο
(μέσω `_files.json` που δημιουργεί η πλατφόρμα). Κάθε εβδομάδα ανεβαίνει νέο αρχείο με νέα ημερομηνία
`ηη-μ-εε` στο όνομα· χρησιμοποιείται το πιο πρόσφατο ανά πηγή.

| Αρχείο (prefix) | Φύλλα (sheets) |
|---|---|
| `ICT Copper ηη-μ-εε.xlsx` | panels, jacks, outlets, ojacks, misc |
| `ICT FO ηη-μ-εε.xlsx` | panels, faps, pigs, adaps, boxes, misc |
| `ICT Cables ηη-μ-εε.xlsx` | cabCu, cabFo |
| `ICT Racks ηη-μ-εε.xlsx` | racks, shelves, accs, wallBases |
| `ICT Telco ηη-μ-εε.xlsx` | telco, krone, tools |

Η 1η γραμμή κάθε φύλλου είναι οι επικεφαλίδες (ονόματα πεδίων). Λίστες χωρίζονται με κόμμα (`Cat6, Cat6A`),
τα boolean είναι `TRUE`/`FALSE`. Τοπικά (`file://`) εμφανίζεται περιοχή «Διάλεξε τα αρχεία σου».
