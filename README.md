antibiotic_resistance_in_gonorrhea
==============================

Using genetic data from strains of gonorrhea, I developed three models to predict resistance to
azithromycin, ciprofloxacin, and cefixime to efficiently inform physicians of effective
treatments and combat the rise of antibiotic resistance that accompanies frequent prescription
of primary antibiotic treatments. I utilized statistical analysis to determine features
correlated with resistance among 8000 DNA sequences and ensemble methods to develop models with
effective recall.

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── interim        <- Intermediate data that has been transformed.
    │       ├── azm_data.csv
    │       ├── azm_data_step2.csv
    │       ├── cip_data.csv
    │       ├── cip_data_step2.csv
    │       ├── cfx_data.csv
    │       └── cfx_data_step2.csv
    │   ├── processed      <- The final, canonical data sets for modeling.
    │       ├── azm_data_final.csv
    │       ├── cip_data.csv
    │       ├── cip_data_final.csv
    │       ├── cfx_data.csv
    │       └── cfx_data_final.csv
    │   └── raw            <- The original, immutable data dump.
    │       ├── azm_sr_gwas_filtered_unitigs.Rtab
    │       ├── cfx_sr_gwas_filtered_unitigs.Rtab
    │       ├── cip_sr_gwas_filtered_unitigs.Rtab
    │       └── metadata.csv
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks
    │   ├── 01_data_wrangling.ipynb
    │   ├── 02_exploratory_data_analysis.ipynb
    │   ├── 03_preprocessing_and_training.ipynb
    │   └── 04_modeling.ipynb 
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   ├── final_report_antibiotic_resistance.pdf
    │   ├── project_proposal_antibiotic_resistance.pdf
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    └── src                <- Source code for use in this project.



--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
