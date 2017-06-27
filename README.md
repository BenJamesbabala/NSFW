# Adult Content Recognition from Images Using a Mixture of Convolutional Neural Networks
A mixture of convolutional neural networks for adult content recognition [1]. Unlike other works, our method is formulated on a weighted sum of multiple deep neural network models. The weights of each CNN models are expressed as a linear regression problem learnt using Ordinary Least Squares (OLS). Experimental results demonstrate that the proposed model outperforms both single CNN model and the average sum of CNN models in adult content recognition.
In this research, we collected the data manually from the Internet yielding 41,154 adult images. For negative images, images from the ILSVRC-2013 test set were used. These data are separated into training, validation, and testing sets. The dataset available for research purposes (contact me if you want to get access to the dataset). 

[1]: https://arxiv.org/abs/1612.09506