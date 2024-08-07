# climate change detection
## Abstract
For much of the global population, climate change appears as a slow, gradual shift in daily weather. This leads many to perceive its impacts as minor or negligible, thereby fostering a troubling sense of apathy (the ``boiling frog" effect).  How can we convey urgency when the crisis appears so subtle? Here, through a series of behavioral experiments, we show that presenting people with binary climate data (e.g., lake freeze history) significantly heightens the perceived impact of climate change compared to continuous data (e.g., mean temperature). Computational modeling and follow-up experiments suggest that binary data elevates perceived impact because it creates an ``illusion" of sudden shifts. This effect is robustly confirmed through multiple replications and an experiment with real-world freeze and temperature data. These findings provide a cognitive basis for the ``boiling frog'' effect and offer a novel approach for policymakers and educators to better communicate the urgency of climate change.    

Run cpd_models.Rmd to perform retrospective Bayesian changepoint detection on simulated data from the /simulated_binary_and_continuous_data directory.

Run generate_simulated_data to generate new binary and continuous data within a given correlation range.

the /experiment_stimuli directory contains the images used as stimuli for each of the experiments run in the paper. For the change perception experiment, we also include the data in used to create the stimuli under the /simulated_data_change_perception_experiment directory. The /real_lake_freeze_and_temp_data contains lake freeze and temperature data used in the real lake change perception experiment. 
