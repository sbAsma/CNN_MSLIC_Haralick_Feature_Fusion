# CNN and M-SLIC Superpixels Feature Fusion for VHR Image Classification
This is the code used to generate the results of [1]. Please refer to [1] for more details. Please cite [1] if you are to use the dataset.


<a id="1">[1]</a>
B. A. Semcheddine and A. Daamouche, "CNN and M-SLIC Superpixels Feature Fusion for VHR Image Classification," 2022 International Conference of Advanced Technology in 
Electronic and Electrical Engineering (ICATEEE), M'sila, Algeria, 2022, pp. 1-4, doi: 10.1109/ICATEEE57445.2022.10093756.

## Note
The SCf and SHCf methods might give slightly different results than what you will find in [1], because of the randomness in the initialization 
and during the learning process of the CNN. This code has also a much lower number of epochs in the training process of the CNN, prior to the feature extraction phase.

## Dependencies
- python == 3.7
- numpy ==  1.21.6
- pandas ==  1.3.5
- sklearn ==  1.0.2
- cv2 ==  3.4.2
- matplotlib ==  3.1.3
- skimage ==  0.19.2
- scipy ==  1.7.3
- tensorflow ==  2.3.1
- keras ==  2.4.0
- PIL ==  7.0.0
