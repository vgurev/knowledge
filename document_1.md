# Molecular fingerprints

Molecular fingerprints, also known as chemical fingerprints or descriptors, are computational methods that encode the structural features of small molecules and correlate them with their biological activities and physicochemical properties. These fingerprints are usually presented as vectors, where each element represents the degree, frequency, or existence of a specific structural feature.

# Clustering by molecular fingerprints

In the below table we divide molecule set into multiple clusters based on their fingerprints. 

| Cluster 1 | Cluster 2 | Cluster 3 | Cluster 4 | Cluster 5|
| - | - | - | - | -|
| COc1ccc(C2=CC(c3cccc([N+](=O)[O-])c3)N(C(C)=O)N2)cc1 | CC(CO)(CCCCOc1cc(F)ccc1F)NC1CC1 | CC(C)(N)CNC(=O)N1CCCC2(CCOCC2)C1 | Cc1ccn(-c2ccc(NC(=O)Cc3ccc(F)cc3)cc2)n1 | CCC(C)NCC(=O)N(C)C1CCCN(C)C1|
| CC(=O)OC12NC1(C#N)C(c1ccc([N+](=O)[O-])cc1)C1=C(CCCC1=O)O2 | CCNC1Cc2ccc(OC)cc2O1 | CN(C)C(=O)CN=C(NCCC1=CCCCC1)NC1CCN(Cc2ccccc2)CC1 | CNc1cnn(Cc2ccc(C)cc2)c(=O)c1 | CCCCC(CCCC)(C(=O)NN1CCN(C)CC1)C(=O)NN1CCN(C)CC1|
| N#CC(=Cc1ccc([N+](=O)[O-])cc1)C(=O)Nc1sc2c(c1C#N)CCCC2 | Cc1ccccc1OCCN(C)C1CCCCC1CN | CCCN1CC(CNC2=NCCCN2C)CC1=O | CCC(C(=O)Nc1cc(C)nn1-c1cc(C#N)ccc1Cl)=C1N=CC=CN1 | CC(C)C(C)(C)CNC(=O)C1CNCCN1C|
| Nc1n[nH]c(-c2cccnc2)c1[N+](=O)[O-] | COCC(O)CN(C)Cc1cc(C#CCO)ccc1OC | CN=C(NCCN(C(C)C)C(C)C)NCc1cccc(NC(=O)N2CCCC2)c1 | Cc1[nH]n(-c2ccccn2)c(=O)c1Cc1cccnc1 | CC1CN(C(=O)C2CCC(C(F)(F)F)CN2)CC(C)N1C|
| Cc1ncc([N+](=O)[O-])cc1C(=O)NC(CO)c1ccco1 | CN(CCO)Cc1cccc(O)c1 | CC1CN(C(=O)NCC2CCC2)CC2(CCOC2C)O1 | NC(=S)N(NC(=O)c1ccc(-c2ccc(Cl)cc2)s1)c1ccccc1C(F)(F)F | CCCCCCN(C(=O)C(C)C)c1nc(C)co1|
| Cn1nc(CNC(=O)C=Cc2ccc([N+](=O)[O-])cc2)cc1-c1ccccn1 | CCc1cc(C2CNCC(C)O2)ccc1OC | Nc1ccc2c(c1)CCCC2NC(=O)N1CCC12CCC2 | Oc1cnc2c(Br)cccn12 | CC(O)CC1CCCN1C(=O)CCC=Cc1ccccc1|
| O=C1C(=Cc2cn(-c3ccccc3)nc2-c2cccc([N+](=O)[O-])c2)NC(=S)N1c1ccccc1 | CCCNC(COC1CCC1)c1cc(C)ccc1C | CCC1(CC)CCN(C(=O)NN)C1 | COC(C)c1c(NC(=O)Nc2cnc(OC(F)F)c(Cl)c2)cnc2ccnn12 | CCNCC(=O)N1CC(C)OC(C)(C)C1|
| Cc1ccc(OCc2csc(-c3ccsc3)n2)c([N+](=O)[O-])n1 | CCNCCCC(C)Oc1ccc(C)cc1Br | CCNC(=NCc1ccc(Cn2cnc3ccccc32)cc1)NCC(=O)NC(C)(C)C | CN(Cc1cnn(C)c1)C(=O)c1ccnc(NN)c1F | CC(CN)CCC(=O)N1CCCN(CC(N)=O)CC1|
| COC(=O)CCC1=C(C)c2nc1cc1[nH]c(cc3[nH]c(cc4nc(c2[N+](=O)[O-])C=C4C)cc3C)c(C)c1CCC(=O)OC | COc1ccc(CCN(C)C(=O)NC(C)C)cc1OC | CC(C)C(=O)N1CCN(c2nc(NC3COC3)cc(C(C)(C)I)n2)CC1 | CN(C)c1ccc(NC(=O)c2cc3ncccn3n2)cc1 | CC(C)C1NC(C(C)C)N(C2CCC(C)C(C)C2)C1=O|
| O=[N+]([O-])c1ncn(Cc2ncc(-c3ccccc3)o2)n1 | CC1CCC(NCCOCCOc2ccccc2)CC1 | CC1(C)CN(CCNC(=O)N2CCOCC3(CCOCC3)C2)CCO1 | Cc1cc(-c2cnc(NC(=O)c3c(Cl)c(C(F)(F)F)nn3C)cn2)n(C)n1 | CCNC1CCCN(C(=O)C(C)(C)CC)c2ccccc21|
| CSc1nc2nc(C)c3c(=O)n(-c4ccc(C)c([N+](=O)[O-])c4)ccc3n2n1 | COc1ccc(OCCC(C)(N)CCCCB(O)O)cc1 | C#CCOCC1CCCN(C(=O)NCCc2ccccc2)C1 | CC(NC(=O)c1ccc(-n2cnnn2)cc1)C1CC1 | Cc1cc(N(C2CC2)C2CCN(C3CCCN(C)C3=O)CC2)ncn1|
| CON=C(C(=O)O[N+]1(O)N=Nc2ccccc21)c1csc(N)n1 | COCCNCc1ccccc1Oc1cccc(Cl)c1Cl | CC1SCCN(CC(=O)NC(=O)Nc2ccccc2)C1C | Cc1cc(CNC(=O)c2cc3nc(-c4ccc(C(C)C)cc4)cc(C(F)(F)F)n3n2)nn1C | CC(C)CCN1CCN(C(=O)C(C)C(C)C(=O)O)CC1|
| O=[N+]([O-])c1ccc2nc(-c3cncc(Br)c3)oc2c1 | CCNC(Cc1ccccc1F)C1(OC)CCC1 | CCOC(=O)N1CCC(NC(=NC)NCc2cccc(NC(=O)C3CCCO3)c2)CC1 | Cc1nn(C)c(C(=O)Nc2c(C(N)=O)sc3nc(C(F)F)cc(C4CC4)c23)c1Cl | CC1CN(CCC(=O)N2CCc3ccccc3C2)CC1(O)C1CC1|
| O=[N+]([O-])c1ccc(C=CC=Nc2ccc3oc(-c4ccncc4)nc3c2)cc1 | CC1=C(Oc2cc(C)cc(C#N)c2)C(C2CC2)=NC1CCO | CNc1cc(C(=O)NCCN(C)C2CCCC2)cc(C)n1 | Cc1ccc2c(c1)C(NC(=O)c1cnn(C)c1)C(C)C2 | CN(C(=O)C1CCNC1)C1CCC(C)(C)CC1|
| Cc1ccc(C(C)NC(=O)c2cc(Cn3nc(C)c([N+](=O)[O-])c3C)cs2)c(C)c1 | CC(C)OCCCCNc1cc(N)cc(OC(C)C)c1 | CCOCCC1(CNC(=NC)NCc2ccc(N3CCOC(C)C3)nc2)CCCC1 | Cn1ccnc1NC(=O)C=Cc1ccccc1 | CCCCc1ccc(NC2CCN(C)C2=O)cc1|
| Cc1cc(NC(=O)c2ccc(Cl)cc2F)n(-c2ccc([N+](=O)[O-])cc2)n1 | COc1ccc(C2(O)CNC2)cc1OC | CNCCC1CCN(C(=O)c2ccc(C)c(NC(=O)Nc3ccccc3)c2)CC1 | [N-]=[N+]=NC1Oc2ccc(Cl)cc2N1c1ccccc1Cl | COCCCN(CCOC)C(=O)CCC1CCCCN1|
| O=C(OCc1ccc([N+](=O)[O-])cc1)N(C(=O)OCc1ccc([N+](=O)[O-])cc1)c1nccs1 | COc1cccc(CN(C)C(CN)C2CCCCCC2)c1 | CCOc1cccc(C(C)NC(=O)NCC(c2ccccc2)N2CCCC2)c1 | N#Cc1ccc2nc(Nc3ccc(-c4c(C(=O)NCC(F)(F)F)cn5ncnc(N)c45)cc3)[nH]c2c1 | CC(C)N1C(=O)CCC1C(=O)NC1CCCCCC1|
| O=Nc1ccccc1C(=O)Sc1nc2c3c(ccc2[nH]1)C(=O)c1ccccc1C3=O | CNCc1cc(Br)c(OCC(C)(O)C(C)C)c(OC)c1 | CN=C(NCc1ccc(N2CCOCC2)cc1)NCc1coc(-c2ccccc2)n1 | COC(c1ccccc1)n1cnc(=N)c2[nH]c(C(C)C)nc21 | CC1CNC(C(=O)NCC(C)N2CCCC2)CN1|
| N#CC(=Cc1cn[nH]c1-c1cccc([N+](=O)[O-])c1)c1nc(-c2cc3cc(Cl)ccc3oc2=O)cs1 | COc1cc(OC)c(CNCC(C)N)c(OC)c1 | CCCC1(CNC(=O)N2CCCC(C)C2)CC1 | Cc1c(NC(=O)NNc2ccc(Cl)cc2Cl)sc2nc(-c3ccc(Cl)cc3)nn12 | CC(CN)CN1CCCN(C(C)C(=O)NC(C)C)CC1|
| Cc1cccc(-c2nnc(C(C)OC(=O)C=Cc3ccc([N+](=O)[O-])cc3)o2)c1 | COc1cc(OCc2ccccc2)cc2c1C(C)[NH+](Cc1ccccc1)C(C)C2 | CC(C)C(=O)N1CCCc2ccc(NC(=O)NCCCc3ccccc3)cc21 | Cc1cccc(NC(=O)Nc2cccc(Cc3nn(C(C)(C)C)c4ncnc(N)c34)c2)c1 | CCN(CC1CCCNC1)C(=O)CCOC|


The fingerprints capture following molecular features:

* Cluster 1 
    * Contains molecules with nitro groups (N+[O-]) and other functionalities like cyano groups (C#N) and sulfonamides (NC(=S)).
    * These molecules often have aromatic rings with electron-withdrawing groups, which could impact their physicochemical properties and biological activities.
* Cluster 2
    * Features molecules with diverse substituents like ether linkages (OC) and secondary amines (NC).
    * Includes cyclic structures and molecules with oxygen-containing functional groups (e.g., COCC).
* Cluster 3
    * Comprised of molecules with amide groups (C=O) and heterocyclic structures.
    * Common motifs include piperazine rings and other nitrogen-containing rings, indicating potential bioactivity in pharmaceuticals.
* Cluster 4
    * Characterized by molecules with heteroatoms in rings (e.g., thiazoles, pyrazines).
    * The presence of sulfonamides and various nitrogenous rings suggests unique biological activities.
* Cluster 5
    * Contains molecules with both aliphatic and aromatic characteristics, including tertiary amines and various substitutions on aromatic rings.
    * Structural diversity with functionalities like carbonyls and nitriles suggests varied physicochemical properties.