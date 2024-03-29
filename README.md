## Max's Car Recognition model deep dive
=========================

### Project Overview  
The goal of this capstone is to analize how image recognition models make predictions by training a model on the stanford cars dataset and then testing on cars that are outside the scope of the model (i.e. the dataset was created in 2012 so a car outside the scope would be a car from 2016). This will provide insights on how image models make predictions and could also allow us to take insights on design trends over time.

### Walkthrough Demo

...
...
...

### Project Flowchart

...
...
...

### Project Organization

...
...
...

* `data` 
    - contains link to copy of the dataset (stored in a publicly accessible Google Drive folder)
    - saved copy of aggregated / processed data as long as those are not too large (> 10 MB)

* `model`
    - joblib dump of final model / model object

* `notebooks`
    - 1.0-mmp-EDA: this notebook contains an EDA of the numical data of the dataset
    - 2.0-mmp-preprocessing: this notebook contains the preprocessing work that I've done in resizing and normalizing them
    - 2.1-mmp-more-preprocessing: fixed my csv files because they did not have complete data
    - 2.2-mmp-rebalancing-the-dataset: rebalanced my train and test sets to an 80%-20% train test split to combat overfitting
    - 3_0_mmp_initial_model_testing: testing out two pretrained models, both overfitting. best result was 49% test accuracy from the MobileNetV2 model

* `reports`
    - contains final report which summarises the project

* `references`
    - contains papers / tutorials used in the project

* `src`
    - Contains the project source code (refactored from the notebooks)

* `.gitignore`
    - Part of Git, includes files and folders to be ignored by Git version control

* `capstine_env.yml`
    - Conda environment specification

* `Makefile`
    - Automation script for the project

* `README.md`
    - Project landing page (this page)

* `LICENSE`
    - Project license

### Dataset

...
...
...

### Credits & References

...
...
...

--------