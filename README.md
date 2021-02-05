# Using proteomics of ovarian cancer to constrain a genome-scale metabolic model 

Aim: Identify person-specific biomarkers for drug and treatment responses. 

- `Human-GEM.xml` is the latest collection of a genome-scale model (GSM) of human metabolism by [Robinson et al. 2020](https://stke.sciencemag.org/content/13/624/eaaz1482.abstract)

- `annotate_model.ipynb` takes all of the reactions in the model and for each set of ENSGs looks up the corresponding protein identifier and name from Uniprot and associates it with that reaction.

- `model_proteins.csv` is the output from the Python script that matches model reactions to protein names and identifiers. The ReactionRule column can be used to check whether the reaction is catalyzed by a single protein, a protein complex or different isoforms. 

- `Human-GEM-annotated.xml` is an instance of the GSM by Robinson et al. 2020 with further information included in the reaction name, reaction notes and reaction annotations. 
