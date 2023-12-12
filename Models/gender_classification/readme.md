The contents of this directory are available only on the private version of this repository. During the 2021 UC Berkeley research project, two teams tackled news-v-opinion and gender-classification problems respectively. This directory contains the work of the gender classification team in the private version of this repository.

The withheld files are:
* `old_models` - contains implementations for gender classifier models
* `output_data` - contains evaluation records for classifiers
* `visuals` - contains plots of classifier performance
* `Classifier Accuracy Summary.ipynb` - contains an analysis of initial benchmark data from GenderAPI, NamSor, Genderize and Gender-Guesser
* `Gender Classifying Pipeline.ipynb` - contains final pipeline - check names against previously run names and commonly classified names, run remaining names through Gender-Guesser, and then run any names marked as unknown through GenderAPI
