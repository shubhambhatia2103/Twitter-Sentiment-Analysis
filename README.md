
# Twitter-Sentiment-Analysis

Welcome to the Twitter Sentiment Analysis (NLP) project repository! 🌟

## Overview

This project delves into the realm of Natural Language Processing (NLP) to understand and interpret human sentiments expressed on social media platforms, particularly Twitter. By analyzing tweets, we aim to gauge the emotional tone behind the text, thereby exploring the power of NLP in sentiment analysis.

## Dataset

The project utilizes the [Sentiment140 dataset](https://www.kaggle.com/datasets/kazanova/sentiment140?resource=download) from Kaggle, containing 1.6 million tweets labeled with sentiment.

## Key Steps

**1. Data Acquisition:** Downloading the Twitter sentiment140 dataset from [Kaggle](https://www.kaggle.com/).

**2. Data Cleaning :** 
- Handling missing values and duplicates.
- Removing irrelevant information (e.g., URLs, dates, usernames).
- Converting text to lowercase for consistency.

**3. Text Preprocessing :** 
- Tokenizing text into words.
- Removing stopwords (common words with little meaning)
- Applying stemming to reduce words to their root forms. (example : actor, actress, acting = act)

**4. Feature Extraction :** Converting text into numerical vectors using  [TF-IDF](https://www.geeksforgeeks.org/understanding-tf-idf-term-frequency-inverse-document-frequency/).

**5. Model Training :** Building a Logistic Regression classifier to learn sentiment patterns to classify tweets as positive or negative.

**6. Model Evaluation :**  Measuring model accuracy using appropriate metrics.

**7. Model Deployment :** Saving the model for future use and potential deployment in a web application or API.


## How to Use

This section guides you through setting up and running the project:

**1. Prerequisites :**

- **Python :** Ensure you have Python 3.9 installed on your system. You can check by running `python --version` in your terminal


- **Libraries :** Install the required Python libraries listed in `requirements.txt`. Open a terminal, navigate to your project directory, and run:

```bash
  pip install -r requirements.txt
```
- **Setup Kaggle API :** If using the Sentiment140 dataset, follow the instructions to configure the Kaggle API and download the dataset.

```bash
  Before we start downloading the data set, we need the Kaggle API token. To get that

  1. Login into your Kaggle account
  2. Get into your account settings page
  3. Click on Create a new API token
  4. This will prompt you to download the .json file into your system. Save the file, and  we will use it in the next step.
```
- **Kaggle Dataset :**

  Follow these guided step by step instruction from kaggle itself for [Easiest way to download kaggle data in Google Colab](https://www.kaggle.com/discussions/general/74235)


**2. Running the Project :**
- Clone this repository:
```bash
  git clone https://github.com/shubhambhatia2103/Twitter-Sentiment-Analysis.git
```

- **Navigate to the Project Directory :**
```bash
  cd Twitter-Sentiment-Analysis
```

- **Launch Jupyter Notebook :** Open `notebook.ipynb` This file contains the core code for data analysis and model building. The notebook provides step-by-step guidance and explanations for each code section.
```bash
  Jupyter Notebook
```

**3. Additional Notes :**

- You may need to adjust file paths or code blocks depending on your specific setup.
- The notebook assumes the dataset is located in the data folder within the project directory.
- Feel free to experiment and modify the code for further exploration and learning.
## Tech Stack

**Python** 

**Libraries:** pandas, NumPy, NLTK, scikit-learn, pickle

**Kaggle API**

**Jupyter Notebook**

## Contributions

Contributions are welcome! Feel free to `fork` this repository and create a `pull request`.


## Future Work

- Explore different NLP techniques and model architectures.
- Experiment with hyperparameter tuning for model optimization.
- Investigate sentiment analysis for different topics or domains.
- Build a web application or API for real-time sentiment analysis.
## Authors

- [@Shubham Bhatia](https://www.linkedin.com/in/shubhambhatia2103/)


## Feedback

If you have any feedback, please reach out to me at Shubhambhatia2103@gmail.com


## Acknowledgements

 - [Kaggle Dataset: Twitter Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140)
 - [NLTK Book: Natural Language Processing with Python](https://tjzhifei.github.io/resources/NLTK.pdf)
 - [scikit-learn documentation](https://scikit-learn.org/stable/)
 - [Youtube](https://youtu.be/4YGkfAd2iXM?si=gA8Ea2s1mufVRF2f)
 - [GeeksforGeeks](https://www.geeksforgeeks.org/twitter-sentiment-analysis-using-python/)
 - [NLTK Book: Natural Language Processing with Python](https://tjzhifei.github.io/resources/NLTK.pdf)
 - [scikit-learn documentation](https://scikit-learn.org/stable/)
 - [GeeksforGeeks](https://youtu.be/4YGkfAd2iXM?si=gA8Ea2s1mufVRF2f)

## Contact

[<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/linkedin.png" title="LinkedIn">](https://www.linkedin.com/in/shubhambhatia2103/) [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/github.png" title="Github">](https://github.com/shubhambhatia2103) [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/instagram-new.png" title="Instagram">](https://instagram.com/6eingshubham) [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/twitter-squared.png" title="Twitter">](https://twitter.com/whoodattboyy)
## License

This repository is licensed under the MIT License - see the [LICENSE](https://github.com/shubhambhatia2103/Twitter-Sentiment-Analysis/blob/main/LICENSE) file for details. Feel free to use, modify, and distribute the code as per the terms of the license.

