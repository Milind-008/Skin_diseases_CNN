# Skin_diseases_CNN
A neural network trained to identify the skin diseases

# Background
Skin diseases are ranked as the fourth most common cause of human illness, but many affected people do not consult a physician. Skin Diseases increase with age , Of the 2,701 individuals in the study, at least one skin abnormality was observed in 1,662 of the participants (64.5 percent). The most common diagnoses were actinic keratosis (26.6 percent), rosacea (25.5 percent), and eczema (11.7 percent). Skin diseases increased with age and were more frequent in men (72.3 percent) than in women (58.0 percent). Nearly two-thirds of the affected participants were unaware of their abnormal skin findings.

# Objective
The aim of the study was to use Convolutional neural network which would be able to identify the type of Skin diseases that the person is suffering from.

# Methods
A simple convolutional network was trained with 3840 training images, 1632 validation images and 1371 testing images with help of tensorflow,keras,matplotlib and numpy.
Here some data sample can be observed from the data directory with their respective classes on the top.The data set contains 10 classes that are Acne and Rosacea Photos, actinic keratosis, Actinic Keratosis Basal Cell Carcinoma and other Malignant Lesions, Atopic Dermatitis Photos, basal cell carcinoma, Bullous Disease Photos, Cellulitis Impetigo and other Bacterial Infections, dermatofibroma, Eczema Photos and Exanthems and Drug Eruptions.

![Screenshot (796)](https://user-images.githubusercontent.com/71492023/188316642-91e1435d-a3f9-44f7-99df-ea7b68817969.png)

# Result
The overall loss has decreased while each Epochs but Accuracy of the model seems to be at 2.0-2.1 with the current nueral network.However the precision is found out to be high.

![Screenshot (800)](https://user-images.githubusercontent.com/71492023/188316782-522d1ba5-f935-4653-9293-efa89865cba8.png)
![Screenshot (799)](https://user-images.githubusercontent.com/71492023/188316788-9b97705b-f4bc-4df0-8289-4e351302fbda.png)
![Screenshot (798)](https://user-images.githubusercontent.com/71492023/188316793-361d2c9a-7435-4b40-85ae-1afd96e8a319.png)

# Future Scope
The Result shows Accuracy to be at 2.21 This is very low and this can be as the data itself is very huge and diverse in information the neural network should be more complex and precise as to capture the feature that really points out the diseases. Also This is a sequential NN which is is primitive to functional NN. With the the use of more complex Functional Nureal network with more data to train and to be tested more accurate and precise reult can be obtained.
