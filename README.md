# Kuzushiji-MNIST  - VGG, ResNet & Capsule Net Classifiers


[Kuzushiji-MNIST](https://github.com/rois-codh/kmnist) is a new alternative dataset for the well-known MNIST. The new dataset can serve as a new benchmark system for classification algorithms and can help restoring millions of books from the almost lost Japanese language - Kuzushiji. 

The [paper](https://arxiv.org/abs/1812.01718) describes the dataset, its extraction process and a few use cases and results.  
A summary of the paper can be found [here](https://www.lyrn.ai/2018/12/13/kuzushiji-mnist-japanese-literature-alternative-dataset-for-deep-learning-tasks/).

This code achieves state-of-the-art results (98.9%) on Kuzushiji-MNIST using an ensemble of VGG Network and ResNet and implemented with PyTorch and FastAI (v1). 

It also provides a Kuzushiji-MNIST Dataset class to help others use the new dataset.   

![](https://github.com/rois-codh/kmnist/raw/master/images/kmnist_examples.png)

