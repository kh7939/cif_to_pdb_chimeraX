# cif_to_pdb_chimeraX
Using ChimeraX software to convert cif to pdb
Useful when converting Alphafold3 output (.cif) to pdb

# Create a txt file that contains the name of cif files
# Create a cxc file
Format should look like

open file.cif <br />
save file.pdb<br />
close <br />

# Open ChimeraX -> File tab -> set working folder (where cif files are) -> command line -> runscript "cxc_file_path"
