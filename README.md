
# Bot and Gender Profiling Project 
Welcome to my **Bot and Gender Profiling Project**!  

This folder contains all the code and resources needed to run experiments for bot classification and gender detection.

## Getting Started:
To prepare the necessary files for this project: 
1.  **Run the preprocessing scripts:** 
     -  `preprocessing.ipynb`: Performs preprocessing steps and includes the **feature count** analysis for bot classification. 
      -  `preprocess_feature.ipynb`: Prepares the data by removing elements such as mentions and hashtags. It also contains the **textual feature** analysis for bot detection. 
 --- 
## Experiment Files
The repository includes several notebooks for different analyses: 
### Part-of-Speech Tags Analysis  
-**`pos.ipynb`**: Contains the experiment using **POS tags** for bot detection. 
### Topic Modeling for Bots  
-**`topic.ipynb`**: Contains the implementation for **topic modeling** aimed at bot detection. 
### Emotion Classifier  
-**`emotion_classifier.ipynb`**: Runs the **emotion classifier** analysis using the BERT-Emotions-Classifier. 
    - **Dependency**: Download the pre-trained [BERT-Emotions-Classifier](https://huggingface.co/ayoubkirouane/BERT-Emotions-Classifier). 
### Gender Detection Analysis
-**`gender_detection.ipynb`**: Performs the same analyses as mentioned above but focuses on **gender detection** instead of bot detection. 
### One-Step Classifier  

-**`one-step.ipynb`**: Implements a **one-step classifier** to directly classify between bots, males, and females.

 
## How to Use  
1. Start by running the preprocessing scripts to prepare the data: 
    -  `preprocessing.ipynb`  
    -  `preprocess_feature.ipynb` 
2. Depending on the analysis, choose the corresponding notebook: 
    - For bot classification: Use `pos.ipynb`, `topic.ipynb`, or `emotion_classifier.ipynb`. 
    - For gender detection: Use `gender_detection.ipynb`. 
    - For one-step classification: Use `one-step.ipynb`.
