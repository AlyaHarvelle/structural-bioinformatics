# Structural Bioinformatics

Before running the script:
- Download any PDB file in a .cif format from https://www.rcsb.org/
- Put this file in the folder "contacts_classification"

In our folder we have 1aba.cif file for testing.

Running the code:
1) Open the folder "contact_classification" in the terminal
2) Run the command `$python3 calc_features.py 1aba.cif -out_dir output/`

This command generates .tsv file in the "output" folder. 
The file consists of features columns and the "Interaction" column, calculated by the classifier_rf.ipynb.

The same process can be repeated with other PDB files. 
After adding new file to the "contact_classification" folder, you need to replace "1aba.cif" in the python command to the name of new PDB.
