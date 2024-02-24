---
layout: single
permalink: /projects/
title: "Projects"
author_profile: true
classes: wide
gallery:
  - url: assets/images/projects/fwb_setup.png
    image_path: assets/images/projects/fwb_setup.png
    alt: "Distributed Processing with PySpark"
    title: "Distributed Processing with PySpark"
  - url: assets/images/projects/imp_features.png
    image_path: assets/images/projects/imp_features.png
    alt: "Important Features"
    title: "Important Features"
---


| **S.No** | **Project Name**                | **Primary Tech/Skill Used** | **Purpose** | **Type** |
|----------|---------------------------------|-----------------------|-------------|----------| 
| 1        | [♻️ Machine Unlearning / Forgetting](#MachineUnlearning) | Torch  |  Exploring solutions to make models forget training data partially           | Individual Work |
| 2        | [🔠 Machine Translation](#MachineTranslation) | Tensorflow   |  Seq2Seq Model architectures for Language Translation on Right-Left typed Languages           | Individual Work |
| 3        | [💊 Health Determinants](#HealthDeterminants) | Spark     |  Distributed analysis to determine financial factors affecting the health of an individual    | Group Work |
| 4        | [🍨 Vanilla Network](#VanillaNetwork) | Python       |  Math behind deep neural network learning          | Individual Work |
| 5        | [📷 Convolute](#Convolute) | Tensorflow  |  Training several CNN architectures from scratch           | Individual Work |
| 6        | [📱 SocioConnect](#SocioConnect) | Flask  |  Prototype website demoing a new social media platform  | Group Work |
| 7        | [🚗 Auto-Insurance Risk Analysis](#AutoRisk)    | Scikit-learn             | Using ML to predict whether a car is associated with any risks based on the car's attributes | Group Work |
| 8        | [🏠 St.Petersburg Property Value Analysis](#PropertyValue)    | Geopandas             | Property value analysis for the city of St. Pete  | Group Work |
| 9        | [🛡️ Insurance Management : System Design](#LuckyInsurance)    | UML, LucidChart             | UML based design of an Insurance Management System | Group Work |
| 10        | [🔎 Analysis of Cyber attack against T-Mobile](#CyberAttack)    | Info-Security analysis             | Report on the 2021 T-Mobile data breach and steps to protect against such attacks  | Individual Work |


## <a id="MachineUnlearning"></a>♻️ Machine Unlearning

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)

The field of Unlearning specifically deals with removing the influence of data points from a model without having to retrain it from scratch – in other words, making a model forget certain information. The concept struck my interest as the process of deep learning is very similar to human learning – *can model forgetting be related to how the human brain forgets information as well?* – we all have memories we want to remember, memories we want to forget and maybe we can help the model too!

Find the project on: 
[![Website](https://img.shields.io/badge/Website-8A2BE2)](https://joe-arul.github.io/machine_unlearning/) [![Github](https://badgen.net/badge/icon/GitHub?icon=github&label)](https://github.com/joe-arul/machine_unlearning.git) 

## <a id="MachineTranslation"></a>🔠 Machine Translation

![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

In this assignment I explore different strategies used in building and training a Language Translator. I use Seq2Seq learning to convert sequences from English to Hebrew(Right to left typed/ DextroSinistral). I also employ techniques such as bi-directional learning and Attention mechanism which serve as the building blocks of advanced transformer-based NLP models such as GPT, Llama etc. 

Find the project on: 
[![Github](https://badgen.net/badge/icon/GitHub?icon=github&label)](https://github.com/joe-arul/machine_translation.git) 


## <a id="HealthDeterminants"></a>💊 Health Determinants

![Apache Spark](https://img.shields.io/badge/Apache%20Spark-FDEE21?style=flat-square&logo=apachespark&logoColor=black) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

The primary goal of this project is to identify how financial factors (and the emotional elements that come with it) affect the health of an individual. The analysis is based on data from the [National Financial Well-being Survey](https://www.consumerfinance.gov/data-research/financial-well-being-survey-data/), which also includes a section asking participants to rate their perception of their own health. The output of such an analysis would help companies operating in the FinSpace optimize their products according to customer needs.

Though this project could have been completed with tools such as Tableau or with simple Python libraries, one of the goals associated is to demonstrate distributed storage and processing technologies - so Spark is being used to accomodate scaling in the future. 

Find the project on: 
[![Github](https://badgen.net/badge/icon/GitHub?icon=github&label)](https://github.com/joe-arul/HealthDeterminants) [![YouTube](https://badgen.net/badge/icon/YouTube?icon=youtube&label)](https://www.youtube.com/watch?v=x0RHXVPTCtk&t=50s) 

## <a id="VanillaNetwork"></a>🍨 Vanilla Network

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

I implement the gradient descent and backpropagation mathematically from scratch, and implement it in Python code. These form as the building blocks of the abstract neural network layers, using which I explore how models learn patterns within data. I also test the effects of varying several structural and algorithmic hyperparameters on the learning process.

Find the project on: 
[![Github](https://badgen.net/badge/icon/GitHub?icon=github&label)](https://github.com/joe-arul/vanillaNetwork.git) 

## <a id="Convolute"></a>📷 Convolute

![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

This project demonstrates training various CNN architectures (including ResNet and VGG16) from scratch to build a Computer Vision Model. The implementation taught me the complexities and nuances of training an Image Classifier, and prepared me to build real-world models for CV. 

Find the project on: 
[![Github](https://badgen.net/badge/icon/GitHub?icon=github&label)](https://github.com/joe-arul/convolute.git) 

## <a id="SocioConnect"></a>📱 SocioConnect

![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

In this project, I worked with a team in developing a website. The website is an advertising platform for a new social media app called 'SocioConnect' and lets users sign up for the app. The project uses the Python Flask framework to render pages, submit forms and connect with the database.

Find the project on: 
[![Website](https://img.shields.io/badge/Website-8A2BE2)](https://socioconnect.pythonanywhere.com/) 
[![Github](https://badgen.net/badge/icon/GitHub?icon=github&label)](https://github.com/joe-arul/socioConnect.git) 

## <a id="AutoRisk"></a>🚗 Auto-Insurance Risk Analysis

![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

The focus of this project was develop a classification model to better predict whether risk is associated with a car based on its attributes. This will aid in the risk assessment process to offer more individualized rates car insurance rates, promoting customer retention and company solvency. The primary motive behind this analysis was to explore machine learning models available for Structured data (numerical, categorical), train and tune them for good results, and learn the various metrics available for each kind of business problem. 

Find the project on: 
[![Github](https://badgen.net/badge/icon/GitHub?icon=github&label)](https://github.com/joe-arul/auto_risk) 

## <a id="PropertyValue"></a> 🏠 St.Petersburg Property Value Analysis

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

In this project we (group) analyze the South St. Petersburg Community Redevelopment Area (CRA) that was established in 2015 to promote reinvestment in housing and neighborhoods, non-residential properties, education, and workforce development in the city. We aim to help the city with these findings by understanding historical trends of property values since the adoption of the CRA. 

*The dataset for this project was provided by the City of St.Pete and is confidential. So I provide a link to a video of the project demo that showcases our analysis approach.*

Find the project on: [![YouTube](https://badgen.net/badge/icon/YouTube?icon=youtube&label)](https://www.youtube.com/watch?v=ZLMxLkWyuCQ&list=LL&index=14&t=76s) 

## <a id="LuckyInsurance"></a> 🛡️ Insurance Management : System Design

UML-based system design project for the day-day operations of an Insurance Company.

Find the project on: [![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1N_JDcxyGylSgHQm8kccIjjOCw4G0rD0k/view?usp=drive_link) 

## <a id="CyberAttack"></a> 🔎 Analysis of Cyber Attack against T-Mobile


This project report showcases a comprehensive analysis of the 2021 data breach against T-Mobile, how to avoid such incidents and countermeasures, policies against future incidents.

Find the project on: [![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1XujjekVR-Eo2u2UlM0H5jV1WrIrQ7SFh/view?usp=drive_link) 


