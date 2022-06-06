                                            SPEECH TO TEXT CONVERSION
 
 Problem Statement -
 
 In this project the goal is to convert the audio data into textual data.
 
 Description Overview -
 
 Speech Recognition is an important feature in several applications used such as Home Automation,Artificial Intelligence etc.This aim to provide use of SpeechRecognition
 library from python and can be used on microcontrollers such as Raspberry Pi with the help of external headphones.
 
 Technology Used -
 
 Here we will be using Python 3.6 and SpeechRecognition Package
 
 Installation of the Project -
 
 The installation of the project is easy.Please do follow the steps to create a virtual environment(good pratice while creating a new project) and then install the    necessary packages in the environment
 
 In PyCharm it's easy
 
 STEPS:-
 1. Create a New Project 
 2. Navigate to the directory of the project
 3. Select the option to create a new virtual environment using conda with python 3.6
 4. Finally create the project using used resources
 5. After the project has been created,install the necessary packages from requirements.txt fule using the command
 
 pip install -r requirements.txt
 
 In Conda also it's easy
 
 STEPS:-
 1. Create a new virtual environment using the command 
 
 conda create -n your_env_name python=3.6
 
 2. Navigate to the project directory
 3. Install the necessary packages from requirements.txt file using the command 
 
 pip install -r requirements.txt
 
 WorkFlow Diagram
 
![2022-06-06](https://user-images.githubusercontent.com/61505882/172188796-0cb60e7d-cb19-4a3f-95ee-2cb625348afc.png)

Implementation -

1. Project Directory

![2022-06-06 (2)](https://user-images.githubusercontent.com/61505882/172190107-48d4ee72-6daf-448e-a3b1-429420cd51fa.png)

This is the folder structure of the project

2. requirements.txt

![2022-06-06 (4)](https://user-images.githubusercontent.com/61505882/172191177-d2eaa12c-e0fb-466d-baf1-fb2f73c789b2.png)

3. speechToText.py

![2022-06-06 (6)](https://user-images.githubusercontent.com/61505882/172191867-537ecef6-bb38-4fe7-9d40-1facd8b9f791.png)

This file contain the script to convert the speech to text using SpeechRecognition package

4. clientApp.py

![image](https://user-images.githubusercontent.com/61505882/172192518-3eb08164-8c27-460e-9e30-ceab6ff84275.png)

This is the flask server file and entry point of your application

TESTING IN LOCAL/API -

To run this project in your local system just run the file clientApp.py and after that web server will start at localhost 5000 port

![image](https://user-images.githubusercontent.com/61505882/172194376-ed583cf0-bb1c-42de-8ed0-81809619efc9.png)

Browse and Upload the .wav file and click on Predict Button

![image](https://user-images.githubusercontent.com/61505882/172194879-83083dca-4246-42e8-b122-80e7b7fd02a1.png)

Finally you will get the decoded text in the Results box

Conclusion -

Hence we have sucessfully converted audio data or speech to digital data

Improvements -

Here we can improve the results by testing with other API which is available from different third party sources or by applying deep learning approaches.









 
 
