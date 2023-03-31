# tf-dev-certificate-practice-boston-housing-prices


Type: Scalar regression problem

Observation: The main focus is how to handle a scenario where you have little data to work with, like in this case where the validation set will be under-represented and thus this will lead to variations in the metric just by the way the samples that will fall in the validation set might not be the best representatives of the training distribution we could end up with just the highest house values only and for training the lowest values and that evaluation will not be significant to make a decision about the qualities of that model.

The main point here is how to apply a K-fold method of evaluation as in this case to solve that constraint.


Metrics is MAE
Loss is MSE

After that, the baseline performance on MAE is 6.533 on the test set.
The model with k=4 folds achieve 2.5 on the test set.



