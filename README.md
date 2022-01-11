# ALDA-FALL21-P12
</br>
Project Summary:
</br></br>
In our project, we use the Kaggle real and fake face image dataset to train a set of machine learning
models including several different architectures of different levels of complexity. The goal here is to
understand how performance changes as we increase the model complexity and to find out where the
ideal level of complexity for this task is while also training a suitable model to effectively classify
fake images. We also attempt to see the effectiveness of transfer learning from a similar task to this
one.
</br></br>
Further, we find that our best-performing model architecture is the deep convolutional neural network
enhanced using transfer learning from the VGG16 network pre-trained on the imagenet dataset. We
use transfer learning because the lower layers of Convolutional neural networks often learn lower
level features such as edges and simple shapes, and can easily be reused for other image classification
tasks. We hypothesise that this would serve as a much better alternative than training the new model
from scratch, especially when the amount of data available is not very high. Once trained on the
kaggle dataset, we also use this model to train and evaluate its performance on another real vs fake
face classification task, but this time using GAN generated images for the fake images and Flickr Face
images for the real images. To generate the GAN images, we use Nvidia’s StyleGan2-ADA, which
is an advanced GAN trained on a large amount of data for 9 days using very high GPU computing
power and is made publicly available by Nvidia.
</br></br>
We choose to train the following models, listed in increasing order of complexity. We use a lot of
convolutional neural networks because it is easy to manipulate their complexity level via the number
of hidden layers and number of neurons/filters per layer and because they are particularly suited to
image classification tasks:
• Support Vector Machine
• Random Forest Classifier
• Shallow Convolutional Neural Network
• Mid-Depth Convolutional Neural Network
• Deep Convolutional Neural Network
• Deep Convolutional Neural Network with Transfer Learning
• Very Deep Convolutional Neural Network with Transfer Learning
</br></br>

Links to Datasets:
- [Kaggle Real vs Fake faces](https://www.kaggle.com/ciplab/real-and-fake-face-detection)
- [Flickr Faces HQ](https://www.kaggle.com/arnaud58/flickrfaceshq-dataset-ffhq)
- [Jeff Heaton's Notebook to generate GAN Images using NVIDIA StyleGan2-ADA](https://github.com/jeffheaton/t81_558_deep_learning/blob/master/t81_558_class_07_3_style_gan.ipynb)


Contributors: </br></br>
- Ginuga Venkata Bharadwaj Reddy </br>
greddy@ncsu.edu </br>
</br>

- Harshil Shah </br>
hshah6@ncsu.edu </br>
</br>

- Saloni Nileshkumar Mahatma </br>
smahatm@ncsu.edu </br>
</br>

- Vineet Vimal Chheda </br>
vchheda@ncsu.edu </br>
</br>
