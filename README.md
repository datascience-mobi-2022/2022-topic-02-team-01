# ***Data analysis project***  2022-topic-02-team-01 

# ***Breast Cancer*** <!-- ![pink-ribbon](<iframe src="https://giphy.com/embed/dd7QLPAjyYZSNgQVNf" width="420" height="480" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/stickers/pink-ribbon-dd7QLPAjyYZSNgQVNf">via GIPHY</a></p>)  -->

## Table of content :open_book:

- [About our project](#About-our-project)
- [Folder structure](#Folder-structure)
- [Best Plots](#Best-Figures)
- [Pathways](#Pathways)
- [Literature](#Literature)


## About our project

In our project we want to explore the genetic origin of tumorigenesis by identifying pathways differentially expressed in cancer patients and specifically breast cancer patients. 

<!-- add more text later  -->


## Folder structure


- **Archive Old Files:** contains old outdated files we have archived in case they are needed as a referance.

- **Data_Cleaning:** contains the markdown files used to perform the data cleaning on the given data sets, where we filtered out low-varience genes as well as unwanted (non-protein-coding) biotypes. 

- **Data Exploration:** contains the markdown files used for our descriptive analysis, as well as mastercodes for generating different types of plots. 

- **Generation of Pathway Matrix:** contains the markdown files used to generate our pathway matrix. This includes pathway gathering, pathway selection, merging, scoring and diagnostic code. 

- **Pan Cancer Analysis:** contains the markdown files used for our pan cancer analysis, where we aimed to identify differences and simmilarities of all cacer types in our dataset. This code includes volcano plots, heatmaps and overlap comparisons of BRCA and non BRCA expression data, as well as diagnostic code.

- **Focused Analysis:** contains the markdown files used for our focused analysis, where we investigated gene expression scores from the BRCA tumour and normal tissue to identify trends in their differentiation. This code contains volcano plots, overlap comparisons and heatmaps as well as diagnostic code.

- **Regression Analysis:** contains the markdown files used in our regression analysis, where we generated a regression model to predict a selected pathway. This folder includes the pathway selection code as well as the regression algorithm. A list of pathways used in the regression analisis can be found at the end of this read me document.

- **Report:** contains the final report markdown and all related files  

- **Output:** contains the graphical outputs and plots 

- **Output read me:** contains the plots that are shown in this read me. 


## Best Figures

![Fig 1: Focused Analysis Heatmap](/Output%20read%20me/Fig1_rm.png)


![Fig 2: Focused Analysis Volcano Plot](/Output%20read%20me/Fig2_rm.png)


## Pathways 

#### 90 Most important Biomarker gene groups for BRCA (Most differentially active in between BRCA and other cancer types:

 [1]"Prol_EGFR"                                                                                
 [2] "ABE_VEGFA_TARGETS_2HR"                                                                    
 [3] "ACEVEDO_LIVER_CANCER_UP"                                                                  
 [4] "ACEVEDO_LIVER_TUMOR_VS_NORMAL_ADJACENT_TISSUE_DN"                                         
 [5] "ACEVEDO_LIVER_TUMOR_VS_NORMAL_ADJACENT_TISSUE_UP"                                         
 [6] "AGUIRRE_PANCREATIC_CANCER_COPY_NUMBER_DN"                                                 
 [7] "AIYAR_COBRA1_TARGETS_UP"                                                                  
 [8] "ALCALAY_AML_BY_NPM1_LOCALIZATION_UP"                                                      
 [9] "ANASTASSIOU_MULTICANCER_INVASIVENESS_SIGNATURE"                                           
[10] "APPIERTO_RESPONSE_TO_FENRETINIDE_UP"                                                      
[11] "AZARE_STAT3_TARGETS"                                                                      
[12] "BAE_BRCA1_TARGETS_DN"                                                                     
[13] "BAELDE_DIABETIC_NEPHROPATHY_DN"                                                           
[14] "BAKKER_FOXO3_TARGETS_UP"                                                                  
[15] "BALDWIN_PRKCI_TARGETS_UP"                                                                 
[16] "BANDRES_RESPONSE_TO_CARMUSTIN_MGMT_48HR_DN"                                               
[17] "BECKER_TAMOXIFEN_RESISTANCE_DN"                                                           
[18] "BENPORATH_NANOG_TARGETS"                                                                  
[19] "BENPORATH_NOS_TARGETS"                                                                    
[20] "BENPORATH_OCT4_TARGETS"                                                                   
[21] "BENPORATH_SOX2_TARGETS"                                                                   
[22] "BERENJENO_ROCK_SIGNALING_NOT_VIA_RHOA_DN"                                                 
[23] "BERTUCCI_MEDULLARY_VS_DUCTAL_BREAST_CANCER_DN"                                            
[24] "BHAT_ESR1_TARGETS_NOT_VIA_AKT1_DN"                                                        
[25] "BHAT_ESR1_TARGETS_NOT_VIA_AKT1_UP"                                                        
[26] "BHAT_ESR1_TARGETS_VIA_AKT1_DN"                                                            
[27] "BILANGES_SERUM_SENSITIVE_VIA_TSC2"                                                        
[28] "BILBAN_B_CLL_LPL_UP"                                                                      
[29] "BILD_CTNNB1_ONCOGENIC_SIGNATURE"                                                          
[30] "BIOCARTA_ARENRF2_PATHWAY"                                                                 
[31] "BIOCARTA_BAD_PATHWAY"                                                                     
[32] "VANTVEER_BREAST_CANCER_BRCA1_DN"                                                          
[33] "VANTVEER_BREAST_CANCER_ESR1_UP"                                                           
[34] "VANTVEER_BREAST_CANCER_METASTASIS_UP"                                                     
[35] "VECCHI_GASTRIC_CANCER_ADVANCED_VS_EARLY_UP"                                               
[36] "WAGSCHAL_EHMT2_TARGETS_UP"                                                                
[37] "WAKABAYASHI_ADIPOGENESIS_PPARG_BOUND_8D"                                                  
[38] "WALLACE_PROSTATE_CANCER_RACE_DN"                                                          
[39] "WANG_CLIM2_TARGETS_DN"                                                                    
[40] "WANG_LMO4_TARGETS_DN"                                                                     
[41] "WANG_LMO4_TARGETS_UP"                                                                     
[42] "WANG_SMARCE1_TARGETS_UP"                                                                  
[43] "WANG_TUMOR_INVASIVENESS_DN"                                                               
[44] "WEI_MIR34A_TARGETS"                                                                       
[45] "WELCH_GATA1_TARGETS"                                                                      
[46] "WENDT_COHESIN_TARGETS_UP"                                                                 
[47] "WHITFIELD_CELL_CYCLE_M_G1"                                                                
[48] "WILLIAMS_ESR2_TARGETS_UP"                                                                 
[49] "WP_ANDROGEN_RECEPTOR_SIGNALING_PATHWAY"                                                   
[50] "WP_CILIARY_LANDSCAPE"  
[51] "WP_DRUG_INDUCTION_OF_BILE_ACID_PATHWAY"                                                   
[52] "WP_FAMILIAL_HYPERLIPIDEMIA_TYPE_4"                                                        
[53] "WP_FARNESOID_X_RECEPTOR_PATHWAY"                                                          
[54] "WP_FGFR3_SIGNALING_IN_CHONDROCYTE_PROLIFERATION_AND_TERMINAL_DIFFERENTIATION"             
[55] "WP_GDNFRET_SIGNALING_AXIS"                                                                
[56] "WP_GLYCOLYSIS_AND_GLUCONEOGENESIS"                                                        
[57] "WP_HEMATOPOIETIC_STEM_CELL_GENE_REGULATION_BY_GABP_ALPHABETA_COMPLEX"                     
[58] "WP_HYPOTHESIZED_PATHWAYS_IN_PATHOGENESIS_OF_CARDIOVASCULAR_DISEASE"                       
[59] "WP_LEPTIN_SIGNALING_PATHWAY"                                                              
[60] "WP_MAMMARY_GLAND_DEVELOPMENT_PATHWAY_PREGNANCY_AND_LACTATION_STAGE_3_OF_4"                
[61] "WP_MELANOMA"                                                                              
[62] "WP_METABOLIC_PATHWAY_OF_LDL_HDL_AND_TG_INCLUDING_DISEASES"                                
[63] "WP_MIRNA_REGULATION_OF_PROSTATE_CANCER_SIGNALING_PATHWAYS"                                
[64] "WP_MIRNA_TARGETS_IN_ECM_AND_MEMBRANE_RECEPTORS"                                           
[65] "WP_OLIGODENDROCYTE_SPECIFICATION_AND_DIFFERENTIATION_LEADING_TO_MYELIN_COMPONENTS_FOR_CNS"
[66] "WP_PATHWAYS_AFFECTED_IN_ADENOID_CYSTIC_CARCINOMA"                                         
[67] "WP_PI3KAKTMTOR_SIGNALING_PATHWAY_AND_THERAPEUTIC_OPPORTUNITIES"                           
[68] "WP_PRADERWILLI_AND_ANGELMAN_SYNDROME"                                                     
[69] "WP_PROXIMAL_TUBULE_TRANSPORT"                                                             
[70] "WP_STATIN_INHIBITION_OF_CHOLESTEROL_PRODUCTION"                                           
[71] "XU_GH1_AUTOCRINE_TARGETS_DN"                                                              
[72] "YAGI_AML_WITH_T_9_11_TRANSLOCATION"                                                       
[73] "YANAGIHARA_ESX1_TARGETS"                                                                  
[74] "YANG_BREAST_CANCER_ESR1_BULK_UP"                                                          
[75] "YANG_BREAST_CANCER_ESR1_LASER_UP"                                                         
[76] "YANG_BREAST_CANCER_ESR1_UP"                                                               
[77] "YAO_TEMPORAL_RESPONSE_TO_PROGESTERONE_CLUSTER_10"                                         
[78] "YOSHIMURA_MAPK8_TARGETS_DN"                                                               
[79] "YOSHIMURA_MAPK8_TARGETS_UP"                                                               
[80] "ZHAN_MULTIPLE_MYELOMA_CD1_DN"                                                             
[81] "ZHAN_MULTIPLE_MYELOMA_LB_UP"                                                              
[82] "ZHANG_BREAST_CANCER_PROGENITORS_DN"                                                       
[83] "ZHANG_BREAST_CANCER_PROGENITORS_UP"                                                       
[84] "ZHANG_RESPONSE_TO_IKK_INHIBITOR_AND_TNF_DN"                                               
[85] "ZHENG_IL22_SIGNALING_DN"                                                                  
[86] "ZHU_CMV_24_HR_DN"                                                                         
[87] "ZHU_CMV_ALL_DN"                                                                           
[88] "ZIRN_TRETINOIN_RESPONSE_UP"                                                               
[89] "ZWANG_EGF_INTERVAL_UP"                                                                    
[90] "ZWANG_TRANSIENTLY_UP_BY_2ND_EGF_PULSE_ONLY"  


#### 25 pathways used in Regression Analisis

[1] ZHOU_TNF_SIGNALING_30MIN 
[2] YOSHIMURA_MAPK8_TARGETS_DN 
[3] ZAMORA_NOS2_TARGETS_DN  
[4] ZHAN_MULTIPLE_MYELOMA_CD1_AND_CD2_DN ] 
[6] ZHANG_PROLIFERATING_VS_QUIESCENT   
[7] ZHONG_SECRETOME_OF_LUNG_CANCER_AND_ENDOTHELIUM  
[8] YAO_TEMPORAL_RESPONSE_TO_PROGESTERONE_CLUSTER_9   
[9] YAGI_AML_WITH_T_8_21_TRANSLOCATION 
[10] YAGI_AML_FAB_MARKERS   
[11] WP_VEGFAVEGFR2_SIGNALING_PATHWAY
[12] WU_CELL_MIGRATION   WU_HBX_TARGETS_2_UP     
[13] WP_PRIMARY_FOCAL_SEGMENTAL_GLOMERULOSCLEROSIS_FSGS  
[14] WP_NUCLEAR_RECEPTORS_IN_LIPID_METABOLISM_AND_TOXICITY  
[15] WP_EXTRACELLULAR_VESICLES_IN_THE_CROSSTALK_OF_CARDIAC_CELLS       
[16] WP_CYTOPLASMIC_RIBOSOMAL_PROTEINS  
[17] WP_CLEAR_CELL_RENAL_CELL_CARCINOMA_PATHWAYS  
[18] WOO_LIVER_CANCER_RECURRENCE_UP  
[19] WANG_TUMOR_INVASIVENESS_UP   
[20] WATANABE_RECTAL_CANCER_RADIOTHERAPY_RESPONSIVE_DN   
[21] WEBER_METHYLATED_HCP_IN_FIBROBLAST_DN WEBER_METHYLATED_HCP_IN_SPERM_DN     
[22] WEBER_METHYLATED_HCP_IN_SPERM_UP    
[23] WEIGEL_OXIDATIVE_STRESS_BY_HNE_AND_H2O2    
[24] WEINMANN_ADAPTATION_TO_HYPOXIA_UP


## Literature

#### Reviews on general cancer biology and cancer metabolism

- **Cancer biology -** Hanahan, Douglas, and Robert A. Weinberg. "Hallmarks of cancer: the next generation." cell 144, no. 5 (2011): 646-674. https://doi.org/10.1016/j.cell.2011.02.013
- **Cancer metabolism -** De Berardinis, R. J., & Chandel, N. S. (2016). Fundamentals of cancer metabolism. Science      Advances, 2(5). https://doi.org/10.1126/sciadv.1600200
- **Cancer metabolism -** Pavlova, Natalya N., and Craig B. Thompson. "The emerging hallmarks of cancer metabolism." Cell metabolism 23, no. 1 (2016): 27-47.https://doi.org/10.1016/j.cmet.2015.12.006

#### Analysis of cancer hallmarks across multiple cancer types using integrative approches

- **Cancer immunology -** Thorsson, Vésteinn, David L. Gibbs, Scott D. Brown, Denise Wolf, Dante S. Bortone, Tai-Hsien Ou Yang, Eduard Porta-Pardo et al. "The immune landscape of cancer." Immunity 48, no. 4 (2018): 812-830. https://doi.org/10.1016/j.immuni.2018.03.023
- **Cancer metabolism -** Peng, Xinxin, Zhongyuan Chen, Farshad Farshidfar, Xiaoyan Xu, Philip L. Lorenzi, Yumeng Wang, Feixiong Cheng et al. "Molecular characterization and clinical relevance of metabolic expression subtypes in human cancers." Cell reports 23, no. 1 (2018): 255-269. https://doi.org/10.1016/j.celrep.2018.03.077
- **Cancer stemness/de-differenciation** Malta, Tathiane M., Artem Sokolov, Andrew J. Gentles, Tomasz Burzykowski, Laila Poisson, John N. Weinstein, Bożena Kamińska et al. "Machine learning identifies stemness features associated with oncogenic dedifferentiation." Cell 173, no. 2 (2018): 338-354. https://doi.org/10.1016/j.cell.2018.03.034
- **DNA damage in cancer -** Knijnenburg, Theo A., Linghua Wang, Michael T. Zimmermann, Nyasha Chambwe, Galen F. Gao, Andrew D. Cherniack, Huihui Fan et al. "Genomic and molecular landscape of DNA damage repair deficiency across The Cancer Genome Atlas." Cell reports 23, no. 1 (2018): 239-254. https://doi.org/10.1016/j.celrep.2018.03.076
- **RAS signalling Cancer -** Way, Gregory P., Francisco Sanchez-Vega, Konnor La, Joshua Armenia, Walid K. Chatila, Augustin Luna, Chris Sander et al. "Machine learning detects pan-cancer ras pathway activation in the cancer genome atlas." Cell reports 23, no. 1 (2018): 172-180. https://doi.org/10.1016/j.celrep.2018.03.046


