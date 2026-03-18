# Image Classification using Convolutional Neural Networks
This project aims to classify the images in the given dataset as cats or dogs using convolutional neural networks(CNN)

# Results:
- Results after training 18,000 images of cats and dogs:

 - number of epochs = 15
 - training data / validation data split = 80/20
 - MODEL
 - CONV 3x3 filter layers with batch norm - 32 x 64 x 96 x 96 x 64
 - Dense layers with drop out of 0.2 and 0.3 - 256 x 128 x 2
 - loss: 0.0638
 - accuracy: 0.9759
 - val_loss: 0.3255
 - val_accuracy: 0.9044
 - The model was tested on the images in the test1 folder. The performance of the model was very good and was able to predict the animals with 97-99% accuracy.

Plots for model accuracy and loss are following:
<img width="520" height="352" alt="image" src="https://github.com/user-attachments/assets/13789f04-864c-4b44-a330-fea26c795386" />

https://github.com/anubhavparas/image-classification-using-cnn/raw/master/output/loss_5000images_15epochs.png?raw=true
https://github.com/anubhavparas/image-classification-using-cnn/raw/master/output/accuracy_18000images_15epochs.png?raw=true
https://github.com/anubhavparas/image-classification-using-cnn/raw/master/output/loss_18000images_15epochs.png?raw=true
https://github.com/anubhavparas/image-classification-using-cnn/raw/master/output/cat_prediction1.PNG?raw=true
https://github.com/anubhavparas/image-classification-using-cnn/raw/master/output/cat_prediction2.PNG?raw=true
https://github.com/anubhavparas/image-classification-using-cnn/raw/master/output/dog_prediction1.PNG?raw=true
https://github.com/anubhavparas/image-classification-using-cnn/raw/master/output/dog_prediction2.PNG?raw=true
