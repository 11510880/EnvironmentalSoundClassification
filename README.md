Environmental Sound Classification
==================================

Here, an algorithm to classify environmental sounds with the aim of providing contextual information to devices such as hearing aids for optimum performance is proposed. We use signal sub-band energy to construct signal-dependent dictionary and matching pursuit algorithms to obtain a sparse representation of a signal. The coefficients of the sparse vector are used as weights to compute weighted features. These features, along with mel frequency cepstral coefficients (MFCC), are used as feature vectors for classification. Experimental results show that the proposed method gives an accuracy as high as 95.6 %, while classifying 14 categories of environmental sound using a Gaussian mixture model (GMM). For more details, please refer to [1]. Please cite [1] if you are using this code.

A note on the data : All data were obtained from the website http://freesound.org. The class wise data information can be obtained from the file "finalList.list".


[1] Sivasankaran, S.; Prabhu, K.M.M., "Robust features for environmental sound classification," Electronics, Computing and Communication Technologies (CONECCT), 2013 IEEE International Conference on , vol., no., pp.1,6, 17-19 Jan. 2013
