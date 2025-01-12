# Spam Detector

## About
This program is developed to demonstrate my learnings as a part of AI Boot-camp by University of Pennsylvania, Liberal and Professional Studies. [More Info...](https://bootcamp.sas.upenn.edu/artificial-intelligence/landing/)
<br/><br/>
This program puts the topics discussed in **Classification in Machine Learning and Gradio App** into action

## Topics covered in this program
1. **Loading Data from file**:
    - Loading data from csv using pandas `read_csv()` function
    - Creating datafram from loaded data using Pandas dataframe.

2. **Splitting Data**:
    - Splitting data for training and testing models using `train_test_split()` function
    - Adjusting train-test split percentages using `test_size` attribute

3. **Using Multimodel training using pipelines**:
    - Creating and training models using `Pipeline`
    - Using `TF-IDF` vecrotizer with `stop_words`
    - Using `LinearSVC` model for predicting classification
4. **Using Gradio module to create User Interfface**:
    - Creatinng user interface application using `Gradio`
    - Customizing standard Gradio interface to display custom labels
    - Allowing user to Flag for errors.


## How to run this program
Follow instructions below to run this program
> NOTE: Following setup and commands are tested in macOS Sonoma 14.5 only

### Pre-requisites
- **Anaconda** (recommended for environment management)
- **Homebrew** (for installing dependencies)
- Python 3.x
- Pandas library
- SKLearn library
- Gradio library

Install Anaconda and set up your environment:

```bash
# Install Anaconda using Homebrew
brew install --cask anaconda

# Create a new environment (optional but recommended)
conda create -n dev python=3.10

# Activate the environment
conda activate dev

# Install necessary libraries
conda install pandas
conda install scikit-learn
conda install gradio
```
## Usage
- Checkout git repository using git clone
`git clone https://github.com/36kp/sms_spam_detector`
- Go to the repo home directory
`cd \YOUR_PATH\sms_spam_detector`
- Execute the Jupyter Notebook
`jupyter notebook`
- Open `gradio_sms_text_classification.ipynb` from browser