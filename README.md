LT2326/LT2926 Final project - Vehicle classification
name: Daniilidou Viktoria Paraskevi

Due to the size of the dataset, it was not possible to upload it to github, so if you want to check it you will find it in this link 
https://www.kaggle.com/datasets/mrtontrnok/5-vehichles-for-multicategory-classification 

There is one jupyter named datasplitfinalproj.ipynb where is the loading of data and the upsampling I added to the dataset so I can have balanced classes. 
In each jupyter there is the model as well as its training and evaluation.  There are 8 different notebooks and their name demonstrates the training dataset choice of the model. 
So, Grayscaleinitialdatasetfinal.ipynb includes training on images converted to grayscale using the initial dataset without any upsampling and data augmentation, 
Grayupsampleddatasetdfinal.ipynb covers training on grayscale images using the upsampled dataset, GrayscaleUpsampledDataAugmentationFinal.ipynb covers 
the training on images converted to grayscale using the upsampled dataset and data augmentation and finally GrayscaleInitialDataAugmentationFinal.ipynb includes training 
on images converted to grayscale using the initial data after adding data augmentation. The same exact logic is followed for colored images so you will find RGBInitialDatasetfinal.ipynb,
RGBupsampleddatasetfinal.ipynb, RGBUpsampledDataaugmentationfinal.ipynb and RGBDataaugmentationfinal.ipynb respectively, in order to be able to compare the evaluation metrics.









