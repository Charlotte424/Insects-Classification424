# Insects-Classification424

 *This project aims to identify 5 diffrent classes; Butterflies,Mosquitos,Dragonflies,Grasshoppers,and Ladybugs, of insects by using AI* 

![alt text](https://cdn.britannica.com/45/102445-050-E3375B6D/Insect-diversity.jpg)

## How the Algorithm Works
For the AI to be able to classify the insects, the algorithm needed to have traning data to learn, testing data to make sure its working, and val data to make sure the caculations are correct. Although, you need data, thats not alll you need, you also have to train the model to understand what its looking at and then you can use it to classify pictures.
## Creating the Project
The steps:
1. Have your Jetson-Nano setup
   ![alt text](https://hexdocs.pm/nerves_system_jetson_nano/assets/images/jetson_nano_devkit.jpg)
2. Write a program to display the Ai's confidence as well as the class
  ![alt text](https://github.com/Charlotte424/Insects-Classification424/blob/main/Screenshot%202024-07-10%20112326.jpg)
3. Find or create a data set and download it into VS code.The data set I used was from	[Kaggle](https://www.kaggle.com/datasets?search=image+classification).
   ![](https://github.com/Charlotte424/Insects-Classification424/blob/main/Screenshot%202024-07-10%20141319.jpg)
4. Go into your docker and build a model   
6. Run epochs until you are satisfied with the acuracy but keep in mind that to many epochs can cause overfitting

7. Export the network and covert the ResNet-18 model to a onnx format
8. test the model on images
  ![Butterfly](https://github.com/Charlotte424/Insects-Classification424/blob/main/cat.jpg?raw=true)
10. Run more epochs if needed

For more detailed information you can watch 	[Jetson AI Fundemntals](https://www.youtube.com/watch?v=VWdJ4BCtam8&list=PL5B692fm6--uQRRDTPsJDp4o0xbzkoyf8) on YouTube

