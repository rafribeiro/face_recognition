# ForenFaceID
 Studies on forensic face identification using automated face recognition models.

### CLLR - Openface - LFW.ipynb

A jupyter notebook for estimating the probability distribution functions of same-source and different-source scores from the LFW dataset, using OpenFace, and calculating Likelihood Ratios, using both gaussian fit and kernel density estimation. Validation of LR methods based on CLLR with 10-fold cross-validation.

A csv file containing the scores is necessary and is available in https://1drv.ms/f/s!AoVqoa5gF0RaskelkY0hDjnGJvJA (178 MB zip file, ~800 MB unzipped). 

### scface_arcface_lr_ece_tippett.ipynb

A jupyter notebook for ECE and Tippett plotting of LRs computed from the SCFace database. LRs computed from similarity scores of ArcFace features using a leave-two-out cross-validation approach.
