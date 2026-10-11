# PROGRESS

## Done
- Folders 01–09 renamed to `NN_Name` style (01_Blood_Culture … 09_Sterile_Fluids_and_Other).
- `Shared/Templates/Specimen_Module_Template.md`, `Shared/Glossary_FA_EN.md`, `Shared/Figures/Image_Policy.md`, `.gitignore` added.
- Modules **01–09** fully built on the template (19 files each: README, Theory, 9 protocol files, 4 antibiogram files, tables, 20 scenarios, answers, references). One commit per module.
- Old files of 01, 02, 03 were read, merged and corrected, then removed.
- Internal links checked (0 broken). Pushed to origin/main.

## Next steps
- User review of modules 01–09.
- `03_Antibiogram/04_Iran_Reference.md` in every module is a placeholder framework; fill it when the user sends official national guidance.
- Modules 10–22: not touched (user instruction). Proposed later: 10 = shared QC reference; 11–22 = organism template (needs user approval first).

## Bugs / notes
- Old 01 files had errors that were corrected: vancomycin disk result for *S. aureus*, pip-tazo for ESBL, discarding the first blood draw from the catheter, "ceftaroline-avibactam", PBS/malaria content (out of scope).
- Numeric breakpoints in the antibiogram files are educational and must be checked yearly against current CLSI M100 / EUCAST tables.
- Root README.md, LICENSE, CITATION.cff, CONTRIBUTING.md are still empty.
