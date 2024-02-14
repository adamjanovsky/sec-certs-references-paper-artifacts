# Paper artifacts

This repository contains the artifacts that accompany the submission of the paper **Chain of Trust: Unraveling the References among Common Criteria Certified Device** to the 2024 IFIP-SEC conference.

The reader can find here the following files:

**Data**:
- [Manual annotations](https://github.com/crocs-muni/sec-certs/tree/31063a6d07033a589d727c70805d9b6843af8317/src/sec_certs/data/reference_annotations): For the manual annotations of reference contexts, we refer the reader to the `sec-certs repository.
- [Hyperparameters](data/hyperparameters/): The best (and all searched) hyperparameter values and the whole protocol captured by Optuna
- [plots](data/plots/): The CSV files produced by `references.ipynb` notebook (see below) and consumed by `plots.ipynb` notebook (see below).
- [Model evaluation](data/model_evaluation/): Model-evaluation data produced by the `prediction.ipynb` notebook (see below).
- [Vulnerability propagation experiment](data/vulnerability_propagation_experiment): Data related to the experiment mapping the propagation of vulnerabilities in the realm of CC-certified products.
- The dataset of CC-related artifacts was produced with `sec-certs` tool and can be obtained from:

**Documents**:

- [Annotation codebook](documents/codebook.pdf): the complete codebook for the manual annotation of the context of inter-certificate references.
- [Hyperparameter tunning](documents/hyperparameter_tunning.md): Description of all hyperparameters that were searched when finetunning the model.

**Notebooks**:

- [plots](notebooks/plots.ipynb): Jupyter notebook with the code to generate the plots in the paper.
- For additional sources, we refer the reader to the `sec-certs` repository, where the complementary material resides:
    - [Reference analysis](https://github.com/crocs-muni/sec-certs/blob/31063a6d07033a589d727c70805d9b6843af8317/notebooks/cc/references.ipynb): Notebook that was used to produce numbers for our reference analysis.
    - [Prediction](https://github.com/crocs-muni/sec-certs/blob/31063a6d07033a589d727c70805d9b6843af8317/notebooks/cc/reference_annotations/prediction.ipynb): Notebook used to train the model that annotated reference contexts.
    - [Annotation-related notebooks](https://github.com/crocs-muni/sec-certs/tree/31063a6d07033a589d727c70805d9b6843af8317/notebooks/cc/reference_annotations): Notebooks used to split the data into training/validation/test sets, and for the notebook with inter-annotator measurement agreement.
