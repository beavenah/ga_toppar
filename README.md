# ga_toppar
CHARMM-type topology and parameter stream file for gramicidin A

In conjunction with toppar_all36_prot_c36m_d_aminoacids.str, par_all36m_prot.prm, and top_all36_prot.rtf, this stream file allows a complete build of gramicidin A (gA) with the CHARMM C36 force field. Use PDB:1JNO or PDB:1MAG. The stream file contains the necessary topology and parameter information for the gA "capping residues" (here "residue" is used in the CHARMM-sense, in which a standalone unit is a residue).

The first defined residue is the CHO, which is based on CHARMM formamide. The second is the ethanolamine (EAM) residue, which is based on CHARMM serine. Necessary parameter information is taken from throughout the CHARMM force field by analogy.

This C36 version has been tested, but not as extensively as the C22 version. Please contact me if errors are found.
