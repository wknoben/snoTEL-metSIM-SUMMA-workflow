# snoTEL-metSIM-SUMMA-workflow

This document a describes a workflow that:
-	Acquires meteorological data from the USDA’s Snow Telemetry Data Collection Network (snoTEL) and the North American Land Data Assimilation System (NLDAS)
-	Formats this data for use in forcing metSIM, a metrological simulator that mimics daily forcing data and disaggregates it at a sub-daily time scale.
-	Runs metSIM simulations and formats the resulting reanalysis data into meteorological forcing files for SUMMA (Structure for Unifying Multiple Modelling Alternatives (Clarke et al., 2015))
-	Creates file control scripts and attribute files for initializing point scale SUMMA runs.
-	And eventually compares SUMMA model output with snoTEL SWE and snowdepth data

The workflow can be recreated by following the instructions found within the folders. The workflow accesses folders in the subsequent order:
1)	DATA_ACQUISITION
2)	METSIM_INSTALLATION
3)	CREATE_METSIM_INPUTFILES
4)	CREATE_SUMMA_FORCINGFILES
5)	CREATE_SUMMA_ATTRIBUTES
6)  CREATE_SUMMA_INITIALCONDITIONS
7)  CREATE_SUMMA_trialParams
9)	MODEL_EVALUATION
