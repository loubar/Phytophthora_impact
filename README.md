
**Phytophthora_trait_framework**

The data and code reproduce the analyses in the main text of Barwell et al. (in prep.) A conceptual trait-based framework for invasion risk assessment of oomycete plant pathogens.


**Phytophthora_global_impacts**

The data and code reproduce the analyses in the main text of Barwell et al. (in prep.), Trait-based approaches for predicting future global impacts in the genus *Phytophthora*.

The analyses estimate the relationships between traits, phylogenetic position and global impacts in Phytophthora. The approach was designed to be a first step towards developing a trait-based early warning system for pathogens for use in plant health risk assessment.

The scripts are numbered in the order they should be run to reproduce the results presented in the text. Each script outputs the R objects required for the next stage of the analysis. 

As the full set of candidate models includes 1284 models, the model comparison was run in parallel on a cluster.  Reproducing step 2 (2_fit_global_impact_models_disease.R) could, therefore, take a very long time.  To enable users to complete the workflow from start to finish in a reasonable amount of time, the fitted model objects and outputs from 2_fit_global_impact_models_disease.R are also provided in the folder disease_traits, meaning this step can be skipped if required.

