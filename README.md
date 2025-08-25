# sit746_code
'sit746 experiments jupyter.ipynb' contains all the code that combines all scripts to run each experiment in Jupyter Notebook.  

`SingleStockKFohlcvCuilogr.py` contains the environment class script for running the main experiments with Cui et al (2023) as a baseline.  

`SingleStockohlcvCuilogr_no_kalman.py` contains the environment class script for running the ablation experiment with the removal of the Kalman Filter.  

In the case Yahoo Finance is down, I have uploaded all Excel files of all the OHCLV data used in this experiment.  

You can directly import the Excel files into Python using pandas.

'A Novel Convolutional Neural Networks for ddqn.pdf' is the pdf for the Cui et al (2023) baseline used in this paper for direct comparison.
