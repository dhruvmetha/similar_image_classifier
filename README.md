This repository contains experiments performed on image classification of similar looking images (instruments) using fast.ai and transfer learning.

1. Size of the image being fed into the Resnet depends on the classification problem and dataset (using sizes like 448x448 or 336x336).
2. Data augmentation: zoomed in cropping and using only parts (50%) of the image, helps the network understand finer features.
3. Ensembled Voting of various neural networks bumps up the accuracy by almost 2%. (goes from accuracies of rougly 92% to almost 95%)

References
1. fastbook (https://github.com/fastai/fastbook)