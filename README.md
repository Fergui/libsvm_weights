# Weights for data instances

Users can give a weight to each data instance. 

For LIBSVM users, please download the zip file (MATLAB and Python interfaces are included). 
For LIBLINEAR users, please download the zip file (MATLAB and Python interfaces are included).
You must store weights in a separated file and specify -W your_weight_file. This setting is different from earlier versions where weights are in the first column of training data.
Training/testing sets are the same as those for standard LIBSVM/LIBLINEAR.
We do not support weights for test data.
All solvers are supported.
Matlab/Python interfaces for both LIBSVM/LIBLIENAR are supported.
We are interested in successful stories of using instance weights. Please keep us informed.

Author: Ming-Wei Chang, Hsuan-Tien Lin, Ming-Hen Tsai, Chia-Hua Ho and Hsiang-Fu Yu.
