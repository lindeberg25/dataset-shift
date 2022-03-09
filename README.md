# Dataset-shift

The basic idea to identify shift: if there is a shift in the dataset, then on mixing the train and test file, you should still be able to classify an instance of the mixed dataset as train or test with reasonable accuracy.

Values close to 0.5 indicate that the classifier is not able to discriminate between the two datasets. This could be interpreted as a situation where no discernable shift has occurred in the data. Values close to 1 indicate that the dataset shift is detectable, and we may need to revisit modeling.
