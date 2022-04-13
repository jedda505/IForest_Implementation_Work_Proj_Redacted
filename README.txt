## This is an implementation of Isolation Forest Outlier detection that I created for a project at work. Some information has been replaced or redacted but the purpose of this script is to show how I used IForest and how I pre-processed the Data.

Pseudonymiser_lns.ipynb was a script I wrote to pseudonymise sensitive data before processing with the model.

Run IForest_Model.ipynb to pre-process the data pseudonymised data and run the model. This will create a model output with outlier scores and indicator (-1 being an outlier and 1 being an inlier). 

Merging_data.ipynb merges the pseudonymised data back with the sensitive data so the model output can be analysed.

IForest_Success_Test.ipynb groups the data together so overall documents can be analysed together rather than individual features of the documents.