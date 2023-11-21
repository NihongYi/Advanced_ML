# Advanced_ML
Personal projects in Advanced Machine Learning course (UCLA MSBA 434), Autoencoder, CNN, RNN, GAN, Transformer, and ensemble included.

## Autoencoder
Use encoder and decoder to remove noise from dataset. ML Flow was used for hyperparameter tuning with random strategy.

## CNN
Use transfer learning from mobilenet to classify if there are people in COCO dataset. Data Augmentation and Rescaling were explored.

## RNN
Build an RNN from scratch to predict the temperature based on the previous period's weather. Additional feature engineering was conducted.

## GAN
Use multi-modal to classify if an image is fake. resnet (for image) and BERT (for text) were used as base models.

## Ensemble
Use ensemble to predict the number of vehicles and signals in an image. For base models, we used mobilenet, built vanilla CNN from scratch, and mean model. For ensemble, simple average, linear regression, XGBoost, and NN were explored.
