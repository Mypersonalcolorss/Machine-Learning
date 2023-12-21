# Machine-Learning

- Dataset:
We use unstructured data which are face images with a total of 4 skin tone labels with each label totaling 1,500 images. In terms of data collection, we scraped data and utilized the Monk Skin Tone (MST) public dataset from Google Research. 

- Dataset Link:
https://drive.google.com/file/d/1k5Vfi2ThZa5BevxJ37eSHUKwVFxfRrOH/view?usp=sharing

- Data Preprocessing:
We preprocess the image data with 512 x 512 format as input to this deep learning model. We also applied data augmentation with ImageDataGenerator to increase the number of images with modifications through vertical and horizontal rotation, shear, and zoom levels.

- Deep Learning Approach:
We use computer vision approach to classify skin tone into 4 labels with Convolutional Neural Network method to process image data better. We used the TensorFlow framework to build this model.

- Deep Learning Modelling:
We utilize the pre-trained model by fine-tuning and adding layers according to the task to be solved by the deep learning model. We use MobileNetV2 from the hard API with fine-tuning by taking the last 5 layers of MobileNetV2 and adding layers such as GlobalAveragePooling and dense layers. In addition, we also implemented BatchNormalization and Dropout layer to prevent overfitting in the Deep Learning model.

- Model Deployment:
In terms of the deployment model, we implemented the use of APIs to deploy this deep learning model. We used Fast API and collaborated with the cloud computing team to perform the deployment process. 

