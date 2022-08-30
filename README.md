# Screening of the Role of Chemical Structure in the Electrochemical Stability Window of Ionic Liquids: DFT Calculations Combined with Data Mining
#### Authors: [Alex S. Moraes](https://scholar.google.com/citations?hl=pt-BR&user=bNF_gEsAAAAJ), [Gabriel A. Pinheiro](https://scholar.google.com/citations?hl=pt-BR&user=819H8Y8AAAAJ), [Tuanan C. Lourenço](https://scholar.google.com/citations?hl=pt-BR&user=mbEklmcAAAAJ), [Mauro C. Lopes](https://scholar.google.com/citations?user=L3AnKVMAAAAJ&hl=pt-BR&oi=ao), [Marcos G. Quiles](https://scholar.google.com/citations?view_op=list_works&hl=pt-BR&hl=pt-BR&user=kQXxkc4AAAAJ&sortby=pubdate), [Luis G. Dias](https://scholar.google.com/citations?user=RT9lc-AAAAAJ&hl=pt-BR&oi=ao), [Juarez L. F. Da Silva](https://scholar.google.com/citations?user=wQG1X8wAAAAJ&hl=pt-BR&oi=ao)

#### [Link to Paper](link)

### IL-ESW_dataset

Here we provide the files of the IL-ESW dataset. The files are organized as follows.

- Inside the folder [cores_backbones](https://github.com/asmoraes92/IL-ESW_dataset/tree/main/cores_backbones) there are the SMILES and the XYZ files of all cores and backbones used in the study.

- Inside the folder [dataset_complete](https://github.com/asmoraes92/IL-ESW_dataset/tree/main/dataset_complete) there are the SMILES and XYZ files of all ions generated in this study. The XYZ files correspond to the optimized geometries and are inside the folders  [cations_xyz](https://github.com/asmoraes92/IL-ESW_dataset/tree/main/dataset_complete/cations_xyz) and [anions_xyz](https://github.com/asmoraes92/IL-ESW_dataset/tree/main/dataset_complete/anions_xyz). The two `.csv` files contain the cations and anions SMILES.
	- In each `.csv` file, there are also IDs for each ion. These IDs are used for the electrochemical window (ESW) calculation, both in the `esw.csv` file and in the ESW calculator app (both explained below)
	- Finally, each file contains the HOMO, LUMO, gap and total energy of each ion.

- The `esw.csv` (zipped into the `esw.zip`) file contains all ionic liquid pairs and their respective ESWs.

- The files cations.json and anions.json are files in the json format that contain the following information for each cation and anion, respectively: HOMO, LUMO, Total Energy, cores and backbones for the fully optimized ions.

- To make it easier to obtain the ESW for a specific cation-anion pair, we also developed an online app, which is a calculator for the ESW. The calculator can be accessed through [this link](https://esw.pages.dev/) and the instructions for using it are given below.


### Instructions for the ESW calculator:

1. In the app, there are two spaces, one for the cation ID and the other for the anion ID.
2. When each space is filled with IDs, the app shows the structure of the ion and its HOMO and LUMO energies, as well as its SMILES.
3. When both spaces are filled, the ESW is also showed.


#### Cite

Please cite [our paper](...) if you use this dataset in your own work:

```
@inproceedings{...
}
