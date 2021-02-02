# User cases

| Purpose | Current method | 3D-beacons method |  
|-----------|:-----------:|-----------:|  
| Get the best available experimental or theoretical model for list of accessions from screening process to identify potential binding sites | Search in PDB first using the accessions, and then try to generate a model using SwissModel  | Iterate all accessions using summary endpoint | 
| Know which experimental and predicted models are available for a specified organism/taxid | Not yet implemented for predicted models, InterPro provides only Experimental structures for taxonomy. | Combine UniProt Protein API and 3D-Beacon summary endpoint |
| Query a certain region of a protein sequence for structures | Search UniProt sequence in [SIFTS](https://www.ebi.ac.uk/pdbe/docs/sifts/) | Sequence search endpoint |  
| When there isn't a structure, the closest sequence and functionally related homology structure or model is wanted to study variations | Use UniProt accession and amino acid locations in [SIFTS](https://www.ebi.ac.uk/pdbe/docs/sifts/) | Combination of summary and annotation endpoints |
| Parse and fetch all the published experimental or theoretical interaction models for multiple sequences| Combination of UniProt, Blast, HHsearch, local PDB database, PDB, SIFTS | |

