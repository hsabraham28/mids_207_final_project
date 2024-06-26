# Houston, We Have A Problem: Image Classification in the Age of AI Generation
## Hannah Abraham, Annie Miller, Jasmine Zhang

### Brief Description
The Real and AI Generated Image Classification project’s goal is to train and develop various machine learning models for the classification of real and AI generated images. This model will be trained on a dataset that contains both real images and images generated by Latent Diffusion Models (LDMs) from Kaggle. 

### Data
The dataset being used for this project is the CIFAKE: Real and AI-Generated Synthetic Images data set (https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images). This dataset contains 60,000 synthetically generated images and 60,000 real images from the CIFAR-10 dataset. The synthetically generated images mirror the ten classes that were present in the CIFAR-10 dataset, and those are airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. The synthetically generated images were generated using Latent Diffusion Models, specifically the Stable Diffusion version 1.4 model. There are two classes in this dataset; real and fake. 

### Models
We developed 12 models to classify images as real or fake (AI-generated).

3 Basic Models: random forest regression, logistic regression, support vector machine

4 Deep Learning Algorithms: convolutional neural network, feedforward neural network, AlexNet Architecture, Inception Architecture

3 Transfer Learning Algorithms: MobileNetV3Large, VGG16, EfficientNetV2L

2 Advanced Algorithms: Vision Transformer, Ensemble of CNN, AlexNet, VGG16

### Results
Though our baseline models—logistic regression, support vector machine, and random forest—fail to achieve our stated success accuracy of 90% on the test set, all but one of our neural network-based architectures surpass our success accuracy threshold. Of our four deep learning models, our feedforward neural network falls short of success criteria with a test classification accuracy of 78.57%; all other deep learning models achieve 95-96% test accuracy. Our transfer learning models—MobileNetV3Large, VGG16, and EfficientNetV2L—perform even better, with EfficientNetV2L notably achieving 97.73% test accuracy. Our ensemble of our CNN, AlexNet, and VGG16 models achieves 95.61% test accuracy, and our vision transformer achieves 99.03% test accuracy, with 99.00% precision and recall—the highest of all our models.


