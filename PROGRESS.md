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

## Done (2026-10-13): AST section + audit of modules 01–09 (CLSI M100-Ed36, EUCAST v16.1, IDSA 2026)
- Built `AST/` (README, 00_Principles 01–03, 01_Phenotypic_Methods 01–08, 02_Beta_Lactamases 01–06, 03_Other_Resistance 01–05,
  04_Biofilm, 05_Fastidious_Anaerobes, 06_Mycobacteria, 07_Molecular, 08_QC, 09_Breakpoints README/01/02, 10_Treatment_Link/IDSA 2026,
  11_Scenarios (20), 12_Answers, 13_References). All numbers checked against CLSI Ed36 text / EUCAST v16.1 xlsx / IDSA 2026 PDF.
- Audit fixes in 01–09: CSF warning list (FQs not on list; doripenem/ertapenem/imipenem/lefamulin added; H. influenzae CSF incl.
  chloramphenicol per Table 2E); GC ceftriaxone S≤0.12/I0.25/R≥0.5, cefixime S≤0.06/I0.12/R≥0.25, disk removed, azithromycin S≤1
  (clinical since 2019, not ECV); pefloxacin = CLSI surrogate too; β-strep TMP-SMX CLSI Ed36 (BMD, SSTI only); EUCAST colistin
  bracketed (2) not S; EUCAST aminoglycosides bracketed for systemic infection; every module 03_Antibiogram/01_Principles links to AST/.
- Notes: Sources (CLSI PDFs, IDSA PDF) are gitignored (*.pdf). M24/WHO TB critical concentrations written from published versions,
  not from provided docs — flagged in file for verification.

## Next steps
- User review of AST/ section; send any errors found for re-check.
- Possible: Methods library + organism profiles restructuring of 11–22 (agreed in concept; user's own proposal pending).
- Module 10 (QC) not touched.

## Bugs / open questions
- AST/06_Mycobacteria numbers (M24S, WHO CC) need verification against current M24S if available.
- Iran reference antibiogram sections (04_Iran_Reference) remain placeholder frameworks.
