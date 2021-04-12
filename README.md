# Antibiotic-Datasets

## ChEBI dataset
The ChEBI dataset contains images of antibiotic compounds labelled as [name].png in the respective class' folder. The list used to create this dataset was the ontology listing for "antibacterial drugs", see https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI%3A36047. 

Classes are: ['Aminoglycoside', 'Carbapenem', 'Cephalosporin', 'Fluoroquinolone', 'Glycopeptide', 'Imidazole', 'Lipopeptide', 'Macrolide', 'Monobactam', 'Nitrofuran', 'Oxazolidinone', 'Penicillin', 'Pleuromutilin', 'Polypeptides', 'Rifampicin & Others', 'Streptogramin', 'Sulfonamide', 'Tetracycline', 'Trimethoprim', 'β-Lactamase inhibitor']

Other categories that might be of interest are: 
* antibacterial agent: https://www.ebi.ac.uk/chebi/searchId.do;jsessionid=C17FA35B07C950528F6AF45C4D0E03AE?chebiId=CHEBI%3A33282
* antimicrobial agent: https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI%3A33281

## ChEMBL dataset
Two versions are available here. The "total dataset"-version was as-is downloaded from ChEMBL using the search "antibiotic", see https://www.ebi.ac.uk/chembl/g/#search_results/compounds/query=antibiotic. 

The labelled antibiotics dataset contains the cleaned and one-hot encoded dataset plus name (where known), class (incl. class number) and the column "old row" (= when +2 gives the row in the "total dataset").

Classes are: ['anthracycline', 'quinoline', 'glycopeptide', 'macrolide', 'tetracycline', 'histone deacetylase inhibitor', 'aminoglycoside', 'carbapenem', 'undefined', 'sulfonamide', 'new MOA', 'monobactam', 'pyrimidones ', 'cephalosporin', 'rifampicin', 'glycoside', 'dipeptide', 'lincosamide', 'ketolide', 'penicillin', 'polymyxin', 'quinolone', 'aminocyclitol', 'nucleoside analogue', 'epothilones', 'polyene', 'quinone', 'coformycins', 'peptide']
