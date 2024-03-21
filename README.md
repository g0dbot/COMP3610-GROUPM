# COMP3610-GROUPM

# Abstract
AI art has rapidly surged in popularity in recent months and with its rise, a lot of mixed opinions on the topic. Individuals expressed their concerns about the legality, artistic value, and possible propagation of deepfake-like content. Some companies have also expressed their unwillingness to use AI generated art in any form at their business. As regulations for AI art begin to be developed, the need for distinguishing between human and AI generated art would begin to increase as well. This project aims to develop a binary classification model that is capable of doing just that.

# Dataset
This project utilizes a dataset from Kaggle.com entitled “AI-ArtBench”. This dataset contains over 185,000 images of art with 60,000 human-drawn, and the remaining images being AI generated with an equal split between the Latent Diffusion and Standard Diffusion models. Both the human-drawn and Latent Diffusion art images are 256x256 resolution and the Standard Diffusion art images are 786x786 resolution.

# Feature Extraction
For feature extraction, a Convolutional Neural Network (CNN) specifically a pre-trained VGG16 model was used to extract features from an image that is deemed as important in differentiating whether the art piece is human, or AI generated.
