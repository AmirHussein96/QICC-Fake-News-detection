# Code for the QICC Fake News Competition

This repository contains source code of the feature based approach for Fake news detection [QICC fake news competition](https://sites.google.com/view/fakenews-contest) that was used by our team FAR-NLP

## Files Description
* The `final_feature_based_FN.ipynb` notebook contains detailed feature based implementation. 
* The `base_model.ipynb` contains CNN and Bidirectional LSTM implementations.
* The `Qatar_data_articles.rar` folder contains the provided training and validation data.

#### How to run the code
1. Set the paths in \*.json files. Copy files in folder "copy-to-CHBMIT-folder" to your CHBMIT dataset folder.

2. Run the code
```console
python main.py --mode MODE --dataset DATASET
