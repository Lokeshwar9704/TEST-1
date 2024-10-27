# Consumer Forecast Prediction

## Description
A Regression type prediction model using *Random Forest Classifier* algorithm. It uses MSE (Mean Squared Error) as the metric for prediction.

## Steps

### Building Files
1) train_model.py: which has regression model code
2) requirements.txt: which has the required library names
3) AEP_hourly.csv: .csv dataset which includes the data regarding counsumer forcast prediction
4) Dockerfile: which contains the commands to be run in docker

### Git & Other Commands used in Command Prompt
1) `mkdir <file_name>` to create the folder
2) `cd <file_name>` to go inside the folder
3) `git init`, initializing folder as git repository
4) manually add all the files
5) `git add .` to add all the files into git track
6) `git commit -m "<message>"`, it commits whatever is there in the track
7) `git remote add origin <GitHub repository link>`, builds connection between git and github
8) `git push --set-upstream origin master`, sends all the files from git to github.


### Jenkins
1) created a new item with item name as **<item_name>**
2) selected *Freestyle project* as the item type
3) selected *Git* in **Source Code Management**
4) added *Execute Windows batch command* step in **Build Steps**
5) Saved the Configurations
6) Clicked build now

#### Output
 ![image](https://github.com/user-attachments/assets/cd93429b-59d8-4ddc-9779-a0ab2f0f0a15)



### Dockers
1) used `cd` to go forward and `cd..` to do backward, to get to the correct path in command prompt (i.e. the folder where all the files including docerfile is located.
2) executed the command `docker build -t <docker_image_name> .` to build the docker image.
3) executed the command `docker run <docker_image_name>` to run the docker image.

#### Output
  ##### Command Prompt
![image](https://github.com/user-attachments/assets/27c08c2b-0b35-4c46-8f21-93bdd1c0c179)


  
  ##### Docker Hub
![image](https://github.com/user-attachments/assets/bf880eb8-3cc2-43ae-aca9-396ec5331a10)

  **Selenium**
  1) integrated flask into app.py. And build an html file called index.html inside templates folder.
  2) created selenium_test.py file which contains the selenium code for autotesting app.py

![image](https://github.com/user-attachments/assets/eeeb28ac-f4b3-4958-a2c0-48cefa70b274)

![image](https://github.com/user-attachments/assets/e636b615-d7d1-4c1a-bbc9-f2c8c904b3f7)



