# Choosing a location for a well

## Introduction for the Project 

A mining company tasked me with finding the best place for a new well. I used the following steps to choose the location:
* Collected the oil well parameters in the selected region: oil quality and volume of reserves
* Built a model for predicting the volume of reserves in the new wells
* Picked the oil wells with the highest estimated values
* Picked the region with the highest total profit for the selected oil wells

## Analysis results

* Uploaded and prepared data. Explained the procedure
* Trained and tested the model for each region:
  - Divided the data into training and validation samples in the ratio of 75:25
  - Trained the model and made predictions on the validation set
  - Saved predictions and correct answers on the validation set
  - Printed on the screen the average stock of the predicted raw materials and the RMSE of the model
  - Analyzed the results
* Prepared for profit calculation:
  - Saved all key values for calculations in separate variables
  - Calculated a sufficient volume of raw materials for break-even development of a new well. Compared the received volume of raw materials with the average stock in each region
  - Wrote conclusions on the stage of preparing the profit calculation
* Wrote a function to calculate profit for selected wells and model predictions:
  - Selected wells with maximum prediction values
  - Summed up the target value of the volume of raw materials corresponding to these predictions
  - Calculated the profit for the received volume of raw materials
* Calculated risks and profits for each region:
  - Applied Bootstrap technique with 1000 samples to find profit distribution
  - Found average profit, 95% confidence interval and risk of loss
  - Wrote conclusions: proposed a region for well development and justified the choice
