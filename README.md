### Image Classification of similar looking images using fast.ai an transfer learning

This repository contains experiments performed on image classification of similar looking images (instruments) using fast.ai and transfer learning.

1. Size of the image being fed into the Resnet depends on the classification problem and dataset (using sizes like 448x448 or 336x336).
2. Data augmentation: zoomed in cropping and using only parts (50%) of the image, helps the network understand finer features.
3. Ensembled voting of various neural networks to check if we get better results.


To run the experiment, you would have to train the model on the dataset provided. This will create a ```model_exp``` folder which will contain all the different models in the experiment trained. You can see the results of each of them in the notebook.

This project uses the Bing API on Azure to create a dataset.

References
1. fastbook (https://github.com/fastai/fastbook)