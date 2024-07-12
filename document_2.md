# Molecular fingerprints

Molecular fingerprints, also known as chemical fingerprints or descriptors, are computational methods that encode the structural features of small molecules and correlate them with their biological activities and physicochemical properties. These fingerprints are usually presented as vectors, where each element represents the degree, frequency, or existence of a specific structural feature.

# Clustering by molecular fingerprints

In the below table we divide molecule set into multiple clusters based on their fingerprints. 

| Cluster 1 | Cluster 2 | Cluster 3 | Cluster 4 | Cluster 5|
| - | - | - | - | -|
| CCn1c(SCC(=O)Nc2ccc(O)c([N+](=O)[O-])c2)nnc1C(NC(=O)c1cccc(C)c1)C(C)C | CN=C(NCc1ccccc1Oc1ccc(C)cc1)NCC1(CCO)CCOC1 | CCC(CN)N1CCN(C(=O)NCC(F)(F)F)CC1 | CCC(C(=O)Nc1ccccc1Cl)n1nc(-c2ccccc2)cc(NC(=O)C(C)C)c1=O | CC(=O)NCC(=O)N1CCN(CCl)CC1C|
| CCCc1cccc([N+](=O)[O-])c1COc1ccn(S)n1 | Cc1ccc(COc2cc(C)c(NCC(=O)CC(C)(C)C)c(C)c2)cc1 | CN=C(NCC(C)Oc1ccccc1C)NC1CCN(CC(=O)NC)CC1 | O=C(Nc1cccc(Cn2cccn2)c1)c1cnn2c(C(F)F)cc(-c3ccc(F)cc3)nc12 | CC(=O)C(Cc1ccccc1)NC(=O)CN1CCCC(C)C1|
| O=C(Nc1cc(Oc2ccc(F)cc2F)cc([N+](=O)[O-])c1)c1oc(=O)c2ccccc2c1-c1ccccc1 | CC(C)COCCOc1ccc(CO)nc1 | CC1CCCN(C(=O)C2CCN(C(=O)NC3CC3)CC2)C1 | O=C(Nc1ccc(-c2cn3cccnc3n2)cc1)c1ccc(-c2cnco2)cc1 | CCC1C(=O)NCCN1C(=O)CCC1CCC(N)CC1|
| Nc1c(C(=O)c2c(=O)o[nH][n+]2-c2ccc(OC(F)(F)F)cc2)sc2nc(-c3cccs3)cc(C(F)(F)F)c12 | CCOc1cccc(CNCc2ccoc2)c1OC | CCNC(=O)C(C)(C)CN=C(NCC)N1CCN(CC(=O)N2CCCCC2)CC1 | CNc1cc(F)cn(-c2cnn(C)c2)c1=O | CC1(C)CCCCC1C(=O)N1CCC(CO)C1|
| O=c1c([N+](=O)[O-])c(Cl)ccn1Cc1ccc(C(F)(F)F)cc1 | CCN(c1ccc(O)cc1)C(C)CCc1ccc(O)cc1 | CC(C)C12CN3CCN(CC(=C1NNC(=O)Nc1ccccc1)C3)C2 | Cc1nc(C(=O)N=[N+]=[N-])nc2ccccc12 | CC1CCN(c2ccc(NC3=C(c4ccccc4)C(=O)N(C)C3=O)cc2)CC1|
| O=C(Nc1nc2ccccc2s1)c1ccc([N+](=O)[O-])cc1C(=O)Nc1nc2ccccc2s1 | COc1ccc(C(C)=O)cc1CN(C)CCN(C)C | CN1CCN(C(=O)Nc2ccc3nc[nH]c3c2)CC1 | N#CCc1ccc(NC(=O)c2ccc(=O)n(-c3ccccc3)n2)cc1 | Cc1ccc(C(C)(C)C)cc1SCc1ccc(C(=O)N(Cc2cccnc2)Cc2cccn2C)o1|
| Cc1nc([O-])c(C#[NH+])c(C)c1N=Nc1ccc([N+](=O)[O-])cc1 | COCc1cc(OC)c(CNO)cc1OC | COC(=O)C1CCC(NC(=O)C2CCN(c3ncc(C(=N)N)cn3)CC2)CC1 | Cn1ncc(-c2ccc(F)cc2)c1-c1cccc(NC(=O)Nc2ccc(Cl)cc2)c1 | C=CCC(C)N1C(=O)NC(C)C1=O|
| O=C(N1C=CN(c2ccccc2[N+](=O)[O-])C1c1nccn1-c1ccccc1[N+](=O)[O-])C12CC3CC(CC(C3)C1)C2 | COCCC(O)COc1cccnc1 | CCC1(NC(=O)Nc2ccc(N3CCC3=O)cc2)CCOCC1 | Cc1cc(NC(=O)c2c(C3CCC3)cnn2C)nc2nc(C(F)(F)F)nn12 | CC(C)CC1NC2(CCCC2)C(=O)N1C1CCOC1|
| COc1cc(NC(=O)CSc2n[nH]c(COc3ccccc3)n2)ccc1[N+](=O)[O-] | CN=C(NCCC(F)(F)F)NCC(c1ccc(OC)cc1)N(C)C | Cc1ccc(NC(=O)N2CCN(c3nc(C)cc(N4CCN(C)CC4)n3)CC2)c(C)c1 | N#Cc1ccc(-c2c(-c3ccc(F)cc3F)nc3[nH]c(-c4ccc(C(F)(F)F)cc4)cc(=O)n23)cc1 | CC(C)CCC1CC(=O)N(C(C)C)C1|
| CC(C)c1[nH]c(C(C)O)nc1Sc1cccc([N+](=O)[O-])c1 | COc1ccc2c(c1)CC(CN)(N(C)CCSC)CC2 | CC(C)C1CCCN1C(=O)NC1CC1 | Cn1ncc(N)c1NC(=O)c1ccc(F)cc1I | CCCNC(=O)CN(C)C(=O)C1CCCN1|


The fingerprints capture following molecular features:

* Cluster 1
    * Contains molecules with diverse structures, many of which include aromatic rings, nitro groups, and various substituents like carbonyl groups and fluorinated groups. These molecules often feature complex heterocycles and fused ring systems.
* Cluster 2
    * Includes molecules that often contain ether linkages (–O–) and aromatic rings with substituents such as methoxy (–OCH₃) or alkoxy (–OR) groups. These compounds tend to have simpler structures compared to Cluster 1, focusing more on ethers and aromatic compounds.
* Cluster 3
    * Features molecules with nitrogen-containing heterocycles, such as piperazine or piperidine rings. These compounds frequently exhibit amide bonds (–CONH–) and substituents that include nitrogen in different forms (e.g., amines, imides).
* Cluster 4
    * Comprises molecules that have complex heterocyclic structures and frequently include fused aromatic systems and fluorinated groups. These compounds often show a mix of carbonyl groups, nitrogen atoms in heterocycles, and functional groups like nitriles (–CN) or nitro groups.
* Cluster 5
    * Contains molecules that are often characterized by the presence of cyclic structures with nitrogen atoms, including various amides and secondary amines. These molecules sometimes include aliphatic chains and more complex nitrogen functionalities.


