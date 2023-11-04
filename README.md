# master-thesis-cryptoregimes

This GitHub repository contains the Jupyter notebooks related to my master's thesis.

The notebooks have been uploaded in an executed form so that the results can be compared with the results in the master's thesis.
In order to re-execute them again on your own machine, simply download the open source datasets from Coin Metrics and the Santiment Academy described in the master's thesis into the corresponding directory and adjust the places in the code where the directory paths are specified.

First of all, the dataprep.ipynb should be executed in order to obtain the prepared dataset for the following tasks.
Then one of the following notebooks can be executed to determine the market regimes:
- determination_2states.ipynb for the detections of two market regimes of the ML methods,
- determination_3states.ipynb for the detections of three market regimes of the ML methods or
- rulebased_determination.ipynb for the detections of two market regimes of the rule-based methods.

Afterwards, the notebooks prediction_2states.ipynb and prediction_3states.ipynb can be executed.
At the beginning, these receive the labels of the market regimes that have been determined by the HMM from determination_2states.ipynb and determination_3states.ipynb respectively.
