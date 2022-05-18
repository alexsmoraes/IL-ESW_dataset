# IL-ECW_dataset


```
Here we provide the files of the IL-ECW dataset. The files are organized as follows.
```


- Inside the folder ***cores_backbones*** there are the SMILES and the XYZ files of all cores and backbones used in the study.

- Inside the folder ***dataset_complete***  there are the SMILES and XYZ files of all ions generated in this study. The XYZ files correspond to the optimized geometries and are inside the folders  "cations_xyz" and "anions_xyz". The two "*.csv*" files contain the cations and anions SMILES.
	- In each "*.csv*" file, there are also IDs for each ion. These IDs are used for the electrochemical window (ECW) calculation, both in the "*ecw.csv*" file and in the ECW calculator app (both explained below)
	- Finally, each file contains the HOMO, LUMO, gap and total energy of each ion.

- The "*ecw.csv*" (zipped into the "*ecw.zip*") file contains all ionic liquid pairs and their respective ECWs.

- To make it easier to obtain the ECW for a specific cation-anion pair, we also developed an online app, which is a calculator for the ECW. The calculator can be accessed through the link https://ecw.pages.dev/ and the instructions for using it are given below.

```
Instructructions for the ECW calculator:

1. In the app, there are two spaces, one for the cation ID and the other for the anion ID.
2. When each space is filled with IDs, the app shows the structure of the ion and its HOMO and LUMO energies, as well as its SMILES.
3. When both spaces are filled, the ECW is also showed.
```