# cats-vs-dogs-classification-using-transfer-learning
## Use tensorflow pretrained MobileNet_V2 as a layer to classify cats_vs_dogs dataset.
This model was trained using the TensorFlow dataset "cats_vs_dogs". 
The model uses the MobileNet_V2 pretrained layer as the base model and at the top a Dense layer of 2 to classify the two classes was used.
The base model or "MobielNet" layers are frozen and only the rest of the weights are used for training. 
A validation accuracy of 98.19 is achieved.

