# Transfer Learning for Small Dataset Image Classification
*An image classification project on a small dataset, using a pretrained CNN.*  

In recent years, a class of artificial neural networks known as Convolutional Neural Networks (CNNs) has proven highly effective for a variety of applications, such as image and voice recognition. Training these deep networks, however, comes at a cost: they require large quantities of training data, and they can be slow to train even with fast processors and ample storage. It may be necessary to train a CNN with hundreds of thousands or millions of samples to achieve effective performance.  

**Faced with a task where you don't have access to millions of samples, how can you hope to achieve effective performance from a deep neural network?**  

One widely used method is known as *transfer learning*, using a CNN trained on a large dataset to learn essential features that can be *transferred* to another, related problem domain. The pretrained network forms the base upon which a refined network is trained on a smaller dataset specific to the new problem domain. Pretrained networks for transfer learning have proven effective for variety of applications.  

This project notebook demonstrates the effectiveness of transfer learning using the Keras deep learning library to classify images from the small UC Merced Land Use dataset. This dataset consists of 2,100 images from 21 classes (100 images per class), derived from the USGS National Map Urban Area Imagery collection. More information about the dataset can be found at http://vision.ucmerced.edu/datasets/landuse.html.  