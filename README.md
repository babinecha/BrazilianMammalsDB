# BrazilianMammalsDB
Customized reference database for barcoding and metabarcoding Brazilian mammals

Files:
- BrazilianMammalsSpeciesList.csv
Spreedsheet containing the Brazilian mammals species list compiled from the list of Brazilian Society of Mastozoology (SBMz) (Abreu et al. 2023), complemented with Brazilian species according to the Mammal species of the world (Wilson & Reeder 2005), as well as exotic mammals present in Brazil (Da Rosa et al. 2017). It presents the taxonomic information of 830 mammal species from 270 genera, 55 families, and 11 orders, along with their name source and synonyms where available. The columns indicate whether the species is native or exotic to Brazil, its conservation status according to the IUCN Red List Version 2024-1 (IUCN 2024), its locomotion type (terrestrial "Te", aquatic "Aq", scansorial "Sc", semi-aquatic "SA", arboreal "Ar", flying "Vo") according to Abreu et al. (2023), and occurrence across six Brazilian biomes: Amazon (AMAZ), Atlantic Forest (MATL), Cerrado (CERR), Caatinga (CAAT), Pantanal (PANT), Pampa (PAMP), and Marine (MARI), according to Abreu et al. (2023) and Paglia et al. (2012).

- BrazilianMammalsReferenceDatabase.csv
Spreadsheet containing the customized reference database for barcoding and metabarcoding Brazilian mammals. It includes sequence IDs obtained from GenBank and BOLD for COI, RNA12S, RNA16S, and mitogenomic sequences, along with the respective taxonomic information. The columns provide the following data: phylum, class, order, family, genus, species, source of name, accession number, sequence type, sequence source, and Brazilian mammal status (whether the species is native, exotic, or foreign to Brazil, or if the sequence belongs to other animal classes). It also presents the distribution of species across different Brazilian biomes, represented by the columns AMAZ (Amazon), MATL (Atlantic Forest), CERR (Cerrado), CAAT (Caatinga), PANT (Pantanal), PAMP (Pampa), and MARI (Marine). The values in the biome columns indicate the presence (1) or absence (0) of the species in each biome.

- All_Scripts_28-10-24.txt
Scripts for:
1. Compilation of sequences obtainded from GenBank and BOLD for COI, RNA12S, RNA16S, and mitogenomes from Brazilian mammals (suplemented with other classes)
2. Compilation of taxonomic information of sequences obtained from GenBank and BOLD
3. Edit of Database for PIMBA (Oliveira et al. 2021), PROTAX (Somervuo et al. 2017) and blastn (Altschul et al. 1990).
4. Identification of sequences using PIMBA (Oliveira et al. 2021), PROTAX (Somervuo et al. 2017) and blastn (Altschul et al. 1990).

- ALL_CLASS_COIgenome.fasta
Fasta file containing customized reference database for metabarcoding of Brazilian mammals, containing COI sequences and mitogenomes obtained from GenBank and BOLD.  
- ALL_CLASS_COIgenome_tax.txt
Txt file containing taxonomic information of COI sequences and mitogenomes obtained from GenBank and BOLD.
- ALL_CLASS_12Sgenome.fasta
Fasta file containing customized reference database for metabarcoding of Brazilian mammals, containing RNA12S sequences and mitogenomes obtained from GenBank and BOLD.  
- ALL_CLASS_12Sgenome_tax.txt
Txt file containing taxonomic information of RNA12S sequences and mitogenomes obtained from GenBank and BOLD.
- ALL_CLASS_16Sgenome.fasta
Fasta file containing customized reference database for metabarcoding of Brazilian mammals, containing RNA16S sequences and mitogenomes obtained from GenBank and BOLD.  
- ALL_CLASS_16Sgenome_tax.txt
Txt file containing taxonomic information of RNA16S sequences and mitogenomes obtained from GenBank and BOLD.

- output_PIMBA_PROTAX_SANGER.csv

