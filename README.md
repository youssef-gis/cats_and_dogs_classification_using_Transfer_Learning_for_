# Dog vs Cat Convolutional Neural Network classification


### Data
The model is trained on Kaggle dataset [kernels edition](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data)

### Model
We use Tensorflow  and Keras MobileNetV2 to build the model. The last layer is sigmoid with 2 classes (dog and cat). See jupyter notebook for more details.
![](https://machinethink.net/images/mobilenet-v2/ExpandProject@2x.png)
![](https://machinethink.net/images/mobilenet-v2/Compression@2x.png)

### Training
- The data from the Kaggle dataset is processed to fit into MobileNetV2 input. See jupyter notebook  for more details.

- The model achieved 99% accuracy on train set and 95% on validation set after 5 epochs 
