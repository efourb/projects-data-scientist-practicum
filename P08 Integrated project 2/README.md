# Recovery of gold from ore

## Introduction for the Project 

Prototype of a machine learning model needs to be prepared for Zyfra. The company is developing efficiency solutions for the heavy industry. The model should predict the amount of gold extracted from gold ore. The data on extraction and purification is available. The model will help optimize production and eliminate unprofitable parameters.

## Analysis results

* Prepared data:
  - Checked that the enrichment efficiency is calculated correctly. Calculate it on the training sample. Found MAE between calculations and feature value. Described findings
  - Analyzed features that are not available in the test sample
  - Conducted data preprocessing
* Analyzed the data:
  - Looked at how the concentration of metals changes at various stages of purification. Described findings
  - Compared the size distributions of raw material granules on the training and test samples
  - Investigated the total concentration of all substances at different stages: in raw materials, in rough and final concentrates
* Built model
  - Wrote a function to calculate the final sMAPE
  - Trained different models and evaluated their quality by cross-validation. Chose the best model and tested it on a test sample. Described findings
