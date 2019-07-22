# Plagiarism Detection [![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/cviejom/Investment-and-Trading/blob/master/LICENSE) [![Awesome Badges](https://img.shields.io/badge/badges-awesome-green.svg)](https://naereen.github.io/badges/)

### The plagiarism detection model examines a text file and performs binary classification to determine if contents commited plagiarism in comparison to an original file analysis
 
In this project, we will building a plagiarism detector that examines a text file and performs binary classification; labeling that file as either plagiarized or not, depending on how similar that text file is to a provided source text. Detecting plagiarism is an active area of research; the task is non-trivial and the differences between paraphrased answers and original work are often not so obvious.

![Sample Image](https://github.com/cviejom/Plagiarism-Detection/blob/master/screen-shot-2019-02-28-at-2.59.48-pm.png)

Plagiarism detection is the process of locating instances of plagiarism within a work or document. 
The widespread use of computers and the advent of the Internet has made it easier to plagiarize the work of others. Most cases of plagiarism are found in academia, where documents are typically essays or reports.  

this project trains a plagiarism detection model using AWS SageMaker 

**Project componets:**
* Convert categorical to numerical data
* Split data into training and test sets
* Create containment features
* Calculate the longest common subsequence
* Train a linear classifier and a nueronal network classifier
* Evaluate model performance

**Project Notebooks:**
* 1 Data Exploration.ipynb
* 2 Plagiarism Feature Engineering.ipynb
* 3 Training a Model Torch.ipynb
* 4 Training a Model Linear.ipynb

Data
----
...


Project Details
---------------
The project is separated into 3 parts with associated notebooks for each one of them:<br>
**Exploratory data analysis:** Please see [Data Exploration](https://github.com/cviejom/Plagiarism-Detection/blob/master/1_Data_Exploration.ipynb)<br>
**Feature Engineering:** Please see [Feature Engineering](https://github.com/cviejom/Plagiarism-Detection/blob/master/2_Plagiarism_Feature_Engineering.ipynb)<br>
**Machine Learning Models:** PyTorch Model, Please see [PyTorch Model](https://github.com/cviejom/Investment-and-Trading/blob/master/CONTRIBUTING.md) /  Linear Model, Please see [Linear Model](https://github.com/cviejom/Investment-and-Trading/blob/master/CONTRIBUTING.md)


Project Resources
-----------------
Paper explaining the techniques implement in the model https://s3.amazonaws.com/video.udacity-data.com/topher/2019/January/5c412841_developing-a-corpus-of-plagiarised-short-answers/developing-a-corpus-of-plagiarised-short-answers.pdf<br>
Udacity Git Commit Message Style Guide http://udacity.github.io/git-styleguide/<br>
Plagiarism Detection Wikipedia Description https://en.wikipedia.org/wiki/Plagiarism_detection

Contributing
------------
Please see [CONTRIBUTING.md](https://github.com/cviejom/Investment-and-Trading/blob/master/CONTRIBUTING.md) if you want to help

Licence
-------
The MIT License (MIT) <br>
Copyright (c) 2019, cviejom <br>
May be redistributed under the terms specified in the [LICENSE](https://github.com/cviejom/Plagiarism-Detection/blob/master/LICENSE) file.

About this Project
------------------
This project was created as a part of the assigments from Udacity, **Machine Learning Engineering** nanodegree