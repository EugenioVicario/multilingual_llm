# multilingual_llm

This repository contains the data and code used to generate and reproduce the results reported in the paper:

**Vicario, E., Bilancini, E., & Boncinelli, L. (2026). *Multilingual Large Language Models and Cultural Diversity: Evidence from Civic and Moral Judgments*.**
SSRN Working Paper. Available at: https://ssrn.com/abstract=6633921
DOI: http://dx.doi.org/10.2139/ssrn.6633921

The repository includes:

* multilingual WVS/EVS survey items used to query the LLM;
* raw and processed language-level LLM responses;
* procedures for aggregating language-level responses into country-level estimates;
* country-level datasets used in the analyses;
* code to reproduce all figures, distance matrices, clustering analyses, and country-level comparisons reported in the paper.

## Repository structure

### data/

Contains the language-level and country-level datasets used throughout the study.

* **language_level/**: multilingual survey items and language-level LLM responses.
* **country_level/**: country-level LLM estimates, survey data, and harmonized datasets used in the analyses.

### code/

Contains the notebooks used to generate the datasets and reproduce all analyses reported in the paper.

* **data_generation/**: data collection and aggregation procedures.
* **analysis/**: statistical analyses, clustering procedures, and visualizations.

## Citation

If you use the data or code contained in this repository, please cite:

> Vicario, Eugenio, Bilancini, Ennio, and Boncinelli, Leonardo. *Multilingual Large Language Models and Cultural Diversity: Evidence from Civic and Moral Judgments*. SSRN Working Paper, 2026. Available at: https://ssrn.com/abstract=6633921. DOI: http://dx.doi.org/10.2139/ssrn.6633921

## License

Please refer to the repository license for terms of use and redistribution.
