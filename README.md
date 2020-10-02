# Plant-Seedlings-Classification-using-pretrained-models
Used pre-trained VGG16, ResNet50 and InceptionV3 networks to extract bottleneck features and developed a model on top of each of them to evaluate the model performances.(Model performances include classification report, confusion matrices, plots of Loss Vs Epoch)

## Requirements
* Tensorflow  
* Keras
* Scikit Learn

## Dataset used
Plant Seedlings Classification dataset

## Usage
* Because of unbalanced data, classes were augmented accordingly to make it balanced.
* In the python script, all the three pretrained models were used on the dataset and performance is calculated for each model.
