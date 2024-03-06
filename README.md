# Pass Classification

This software reproduce the results reported in the manuscript entitled _"Who are the best passing players in professional soccer? A machine learning approach for classifying passes with different levels of difficulty and discriminating the best passing players"._

### Abstract

The present study aimed to assess the use of technical-tactical variables and machine learning (ML) classifiers in the automatic classification of the passing difficulty (DP) level in soccer matches and to illustrate the use of the model with the best performance to distinguish the best passing players. We compared eight ML classifiers according to their accuracy performance in classifying passing events using 35 technical-tactical variables based on spatiotemporal data. The Support Vector Machine (SVM) algorithm achieved balanced accuracy of 0.70 ± 0.04%, considering a multi-class classification. Next, we illustrate the use of the best-performing classifier in the assessment of players. In our study, 2,522 pass actions were classified by the SVM algorithm as low (53.9%), medium (23.6%), and high difficulty passes (22.5%). Furthermore, we used successful rates in low-DP, medium-DP, and high-DP as inputs for principal component analysis (PCA). The first principal component (PC1) showed a higher correlation with high-DP (0.80), followed by medium-DP (0.73), and low-DP accuracy (0.24). The PC1 scores were used to rank the best passing players. This information can be a very rich performance indication by ranking the best passing players and teams, and can be applied in offensive sequences analysis and talent identification.

### Requirements

The list of requirements is available [here](https://github.com/allansp84/pass-classification/blob/master/requirements.txt).

This software runs on Linux Operating systems, and it was tested on Ubuntu 20.04 LTS.


### Compiling and Running this Software

1. Create and activate a new virtual environment:

    ```bash
    (base) foo@bar:~$ conda create --name passclass-env python=3.9`
    (base) foo@bar:~$ conda activate passclass-env
    ```

2. Install dependeces required for running this app:

    ```bash
    (passclass-env) foo@bar:~$ sh install_requirements.sh
    ```

3. Install this package

    ```bash
    (passclass-env) foo@bar:~$ python setup.py develop
    ```


### How to Use this Software?

To run this sofware, please execute the following command:

    (passclass-env) foo@bar:~$ ./scripts/run-experiments.sh


*PS.: The results (files and models) produced during experiments will be stored in the **working** directory.*


### Please, Cite our Work!

If you use this software, please cite our paper published in TODO:

> **Reference**
>     TODO


> **Bibtex**
>     TODO

### License

This software is available under condition of the [MIT Licence](https://github.com/allansp84/pass-classification/blob/master/LICENSE).
