@author Henriklatsch
# Overview

This folder contains different projects from my time at NTNU. Below is a short explanation of the objectives of each project, target variables, files contained and original project deliverables.

## Project 1

This was the final project for the course TDT4173 Maskinlæring at NTNU. The task was given by the company Plaace. Their product is delivering predicted revenues for different retail concepts, based on retail data from similar retail stores in each geographical area of Norway.

The project involved predicting revenues for 8500 retail stores in Norway, based on revenue data for 13000 similar stores. 

The project grade was decided by a kaggle competition leaderboard, where all course participants competed against the course's teacher's assistants. Our final grade achieved one of the highest scores in the course, and the grade A.

The data used in the project is unfortunately proprietary to Plaace, but the short version of model training and model explanations are supplied in the "short_notebook.ipynb". To achieve the final result in this project, extensive exploratory data analysis was performed, and a lot of trial and error.

## Project 2

This was the semester project given in the course TDT4259 Anvendt data science. The project objective was given by the company Aneo, who works in power trading and forecasting power consumption using machine learning techniques.

The project task involved forecasting power consumption 5 days into the future, based on power consumption data from the previous year, and a temperature forecast. The dataset supplied for the project contains power consumption for 5 major cities. 

The "eda.ipynb" file contains a brief exploratory data analysis, used to gain insights into the trends and seasonality of the data. Following the EDA, different machine learning methods were tested in trying to best model the time series, documented in the "modelling.ipynb" file. This file also explores plots comparing each model's performance relative to the baseline predictor.

The data analysis performed in this project, and the accompanying project report received a final grade of B in the course.

The data used for training the models belong to Aneo, and can unfortunately not be published openly. All plots published in the notebook files should however still give an insight into the findings of the project.

## Project 3

This project was the final task in the course TDT4265 Dyp læring og datasyn. The task was to train an object detection model to detect and classifiy road damages on a test set of Norwegian road images. The RDD2022 Road Damage Dataset was supplied to contestants with no limitations on how the dataset should be used for training.

The object detections were uploaded to a leaderboard server where participants could compare scores to each other. Final scores were based both on total accuracy of the detection model trained, and novelty of the methods employed to achieve the final result.

The deliverables for the project included a brief video presentation explaining the methods used to achieve the final result, example detections and a short overview of the detection workflow.

The repository contains the brief project report, explaining model training through Google Colab and Roboflow dataset handling, a video example of road damage detections, the presentation keynote and the "inference.ipynb" file briefly explaining the inference algorithm. The project achieved a final grade of B.
