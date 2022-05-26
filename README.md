# Interpretable and Predictive Deep Neural Network Modeling of the SARS-CoV-2 Spike Protein Sequence

We gratefully acknowledge all data contributors, i.e. the Authors and their Originating laboratories responsible for obtaining the specimens, and their Submitting laboratories for generating the genetic sequence and metadata and sharing via the GISAID Initiative, on which this research is based. To access acknowledgments, please access https://www.gisaid.org and use the "Data Acknowledgement Locator" with EPI_SET-ID = EPI_SET_20220107zy. (The full list of GISAID accession numbers is available for download as an archived file on this site.)

A preprint describing this work, "An Interpretable Deep Learning Model for Predicting the Risk of Severe COVID-19 from Spike Protein Sequence" by Bahrad A. Sokhansanj, Zhengqiao Zhao, and Gail L. Rosen, is located at https://www.researchsquare.com/article/rs-1234007/v1

## keras_model_summary.png
Graphical depiction of the neural network model.

## EpiList.txt.gz
List of GISAID accession identity numbers for sequences used in the aforementioned preprint.

## Covid_Data_Creation.github.ipynb
Software code used to preprocess sequence data.

## Corona_Transformer.ipynb
This notebook includes the code used to generate classifications of clinical severity, along with other variations on the Transformer model and training tasks. This notebook can also be used to generate taxonomic classifications in preprint available at https://www.medrxiv.org/content/10.1101/2021.12.26.21268414v1. The original and the preprocessed/filtered csv files with data are available here (corona_taxonomy_notpreprocessed.csv and corona_taxonomy_preprocessed.csv). The "Dataset Preprocessing" block in the notebook is written to allow training based on multiple kinds of datasets: coronavirus genomes, distinct SARS-CoV-2 genomes with lineage and date infromation (obtained using procedures contained within Covid_Data_Creation.github.ipynb), and patient datasets (with different levels of preprocessing). These codeblocks refer to sequence data files that are not available for direct download due to GISAID's use restrictions, but which may be reconstructed from GISAID downloads, e.g., using the list of GISAID accession identity numbers available for download from this github.

## COVID_Disease_Severity_Projection.github.ipynb
Software code used to predict the disease severity of Omicron, Delta, and Alpha variants as shown in the aforementioned preprint. Also includes code for the neural networks used in the paper.

## Covid_Predict_Omicron_Resistance.ipynb
Notebook used to predict the antibody evasiveness of Omicron from sequence based on experimental data for reduction in antibody neutralization for other variants. This work is described in our preprint available at https://www.medrxiv.org/content/10.1101/2021.12.26.21268414v1
