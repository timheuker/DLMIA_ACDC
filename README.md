# DLMIA_ACDC
ACDC challenge - Deep Learning for Medical Image Analysis - Group 4

The 'augmentation.ipnyb' can be used to generate augmented images based from the complete dataset

'im_aug' and 'gt_aug' contain augmented images, as well as standard images.
The images have the following name im_pxxx_zx_fx_nx.npy where
- p indicates the patient number (between 0 and 100)
- z indicates the slice number in z-direction
- f indicates the phase (f=0 for systole, f=1 for diastole)
- n indicates the image number (n=0 is the original slice, n=1 and n=2 are augmented slices)

'zzztest_train_split.ipnyb' was used to generate the train and valiadation sets

'file_list_test.npy' and 'file_list_train.npy' list the files of the test and train files

'false_crop_list.npy' list all the images that were falsely cropped

'train_LV.ipnyb', 'train_MYO.ipnyb', 'train_RV.ipnyb' can be used to train the networks

trained_nets contains all the trained networks that were used during evaluation

'evaluate' is used to compute the metrics
