# FARM5000
Crash cource 

**Autodock_result** #FOLDER
This folder contains docking-results from Autodock by Osman

**glide_dock_minh** #FOLDER
This folder contains docking-results from Glide/Schrodinger by Minh

INPUT --> OUTPUT:
657 structures from ChEMBLID (628 compounds active: pChEMBL_value > 5.0) + 1000 decoys from Schrodinger_decoys_set --> 1657 structures to LigPrep --> 2599 OUT of LigPrep --> Ligand Docking by Glide 
--> 2536 structures (chosen 20 poses per ligand) --> Dropped duplicates by ChEMBLID by using Python --> 1618 structures remained --> Enrichment
