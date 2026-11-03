# FrothmaleriEpichloeDrought

```
The project is organized under the main directory FrothmaleriEpichloeDrought/, structured into four
major modules: data/ and scripts/. The former module contains data and output files corresponding to 
specific stages of the analysis, whereas the latter contains the scripts. Folder system as follows:

FrothmaleriEpichloeDrought/
│
├── data/
│   ├── nutrients/                      
│   │   └── nutrients_dataset.csv       # Results of the macro and micronutrients measurements
│   │
│   ├── proline/                        
│   │   └── Proline_dataset_250.csv     # Results of the proline concentration measurements 
│   │   
│   ├── alkaloids/                      
│   │   ├── alkaloids_PCR.csv           # Results of PCR conducted on the selected alkaloid genes
│   │   │                               
│   │   ├── alkaloids_qualitative.csv   # Results of qualitative analysis on the four alkaloid classes
│   │   │                      
│   │   └── alkaloids_quantitative.csv  # Results of quantitative analysis of main compounds detected.                        
│   │   
│   │   
│   ├── RNAseq
│   │   ├── count_matrix_H_Festuca.tsv     
│   │   │  
│   │   ├── count_matrix_E_Epichloe.tsv                         
│   │   │
│   │   ├── Frubra_gene_GO.tsv
│   │   │  
│   │   ├── Frubra_InterProScan.tsv
│   │   │
│   │   ├── EfestucaeFl1_gene_GO.tsv
│   │   │  
│   │   ├── EfestucaeFl1_InterProScan.tsv
│   │   │  
│   │   └── phisiology_RNAseq.csv
│   │   
│   ├── output_script1/                  # Output files from foliar nutrient composition analysis (from script_1.Rmd)
│   │                                    
│   │                                    
│   ├── output_script2/                  # Output files from free proline cocnentration analyses (script_2.Rmd)
│   │                                                
│   │   
│   ├── output_script3/                  # Output files from alkaloids profile analyses (script_3.Rmd)
│   │                                                           
│   │   
│   ├── output_RNAsequnix/               # Main outout files from dual RNA-seq bioinformatic processing (.sh scripts  
│   │                                    
│   │     
│   └── output_script4/                  # Output files from transcriptomic host and endophyte analyses (script_4.Rmd)
│                                        
│                                      
│
├── scripts/
│   ├── script_1.Rmd
│   │
│   ├── script_2.Rmd
│   │
│   ├── script_3.Rmd
│   │
│   ├── RNAseq_unix/
│   │   │   
│   │   ├── 01_REFERENCEGENOM/         
│   │   │                                      
│   │   │ 
│   │   ├── 02_TRIMFASTP/                
│   │   │                                     
│   │   │ 
│   │   ├── 03_MAPSTAR/         
│   │   │                                      
│   │   │
│   │   ├── 04_FEATURECOUNTS/        
│   │   │                                                                
│   │   │  
│   │   └── 05_FUNCTIONALANNOTATION/       
│   │                                         
│   │  
│   └── script_4.Rmd
└

Important note: The link to access the host reference genome is not shared in the manuscript nor here, because it has not been published yet by our research group.

```
