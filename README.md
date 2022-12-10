# Causal_ML_Project
Repository for the final project for Stat 27420

This repo contains data/programs/images used to replicate the paper:

	Levine, Phillip B., Robin McKnight, and Samantha Heep. 2011. "How Effective Are Public Policies 
	to Increase Health Insurance Coverage among Young Adults?" American Economic Journal: Economic Policy, 3 (1): 129-56.

Files/Folders:

	Graphs -- Contains all images used in the final paper
	AIPTW_confounders_droppped.ipynb -- Robustness check when dropping confounders
	AIPTW_estimator -- Creates the pre- and post-trend ATT(g,t) graphs with the AIPTW estimator
	G_Model_Checks -- Overlap check and cross-entropy/accuracy table
	IPW_estimator -- Creates the pre- and post-trend ATT(g,t) graphs with the IPW estimator
	LICENSE.txt -- License for the data found in maindata.7z
	Q_model_Checks -- Creates the accuracy/MSE tables for Q
	Q_estimator -- Creates the pre- and post-trend ATT(g,t) graphs with the Q estimator
	When_Were_Laws.csv -- Csv which contains when each state implemented their SCHIP law
	confounders_timeplot -- Generates the plot of the change in confounders over time 
	maindata.7z -- Zip file containing data from Levine et al. (2011)
  
