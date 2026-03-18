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
<img width="515" height="351" alt="image" src="https://github.com/user-attachments/assets/120215aa-48c2-48b4-9177-48d06d2188ae" />
<img width="712" height="341" alt="image" src="https://github.com/user-attachments/assets/e0685acf-2376-4c3c-89ba-1aa9d1c5518a" />
<img width="613" height="340" alt="image" src="https://github.com/user-attachments/assets/e94914a4-5552-4e13-826b-37bbad7dbc30" />
<img width="1034" height="827" alt="image" src="https://github.com/user-attachments/assets/7406d771-dee7-4548-878f-62580e976863" />
<img width="1021" height="781" alt="image" src="https://github.com/user-attachments/assets/f3676d22-b9ee-44ae-922a-3315148a4a82" />
<img width="980" height="836" alt="image" src="https://github.com/user-attachments/assets/bfc72c32-9b9e-475d-95c1-3df5796fdf66" />
<img width="1008" height="792" alt="image" src="https://github.com/user-attachments/assets/b5475413-0bc9-4de4-bb46-6cfb86111266" />

