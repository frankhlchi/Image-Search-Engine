“Image Retrival With Text Query”
https://github.com/frankhlchi/Image-Search-Engine/blob/master/report.pdf

Files needed to run the code:

- GoogleNews-vectors-negative300.bin.gz

- unzip cs5785-fall-2019-final.zip (download from Kaggle, https://www.kaggle.com/c/cs5785-fall-2019-final/data)

- (1)run corresponding resnet feature generation code (Team Ground Truth 1.extract resnet features part.ipynb);
  (2)OR you can also download ready-to-use self-generated features data directly  (generated_resnet_features.zip), from https://drive.google.com/drive/folders/1pkXLFcvuEkC_VQ-QunVUC9EjjlvF8-j5, then unzip generated_resnet_features.zip in this folder
  
The File tree before running the model notebook
- GoogleNews-vectors-negative300.bin.gz
-/descriptions_train
-/descriptions_test
-/tags_train
-/tags_test
-/features_train
-/features_test
-/images_train
-/images_test
-resnet50_train.csv
-resnet101_train.csv
-resnet152_train.csv
-resnet_ResNext_train.csv
-resnet_wide101_train.csv
-resnet50_test.csv
-resnet101_test.csv
-resnet152_test.csv
-resnet_ResNext_test.csv
-resnet_wide101_test.csv

- GBM models are NOT required to run the best model. It is only used in other models. If you want to run them, you can (1)run corresponding lightGBM generation code; (2) download from https://drive.google.com/drive/folders/1pkXLFcvuEkC_VQ-QunVUC9EjjlvF8-j5 (unzip GBM models.zip into fold GBM_model)

- If there is any further question please contact Hongliang CHI, hc962@cornell.edu; Kai Zhang kz298@cornell.edu
