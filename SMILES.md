### This document describes how to prepare SMILES strings for compounds in your in silico drug screen.

SMILES means Simplified Molecular Input Line Entry Specification is a Compact machine and human-readable chemical nomenclature.
Tutorials about how to write SMILES can be found in [Daylight](https://www.daylight.com/dayhtml_tutorials/languages/smiles/index.html), 
[UCI website](https://www.ics.uci.edu/~dock/manuals/DaylightTheoryManual/theory.smiles.html) and 
[Open SMILES](http://opensmiles.org/opensmiles.html).

To get a SMILES for a certain chemical compound, you need to know its name or structure.
With the name or ID, you can search it on databases such as [PubChem](https://pubchem.ncbi.nlm.nih.gov/), [GtoPDb](https://www.guidetopharmacology.org/), or [drugbank](https://go.drugbank.com/).
Or, you can draw the structures with online editor or desktop software such as ChemDraw.

To draw a decent and "legal" structure, here is a Nature-published guideline ([English](https://www.nature.com/authors/guides/ChemStructureGuide.pdf) and [Chinese](https://www.x-mol.com/news/10154) versions).

Take Digoxin as an example. Let's search Digoxin in PubChem and GtoPDb. For molecules with chirality, you will at least have two SMILES, canonical SMILES without isomeric information or isomeric SMILES labelling the chiral atoms.
You will see that the SMILES codes from both websites are not identical. In fact, SMILES can be in many styles or formats.
To make sure you are refering to the same molecule, SMILES code can be checked via [ChemInfo](http://www.cheminfo.org/flavor/malaria/Utilities/SMILES_generator___checker/index.html).
You will see that the canonical SMILES of Digoxin from PubChem and GtoPDb are converted to the same SMILES code, although the structures are displayed in a slightly different manner.

You can also use software such as RDKit to convert the SMILES codes you get anywhere to a unique form of SMILES.
