# Sentiment Analysis Model

## Overview

A deep learning neural network model designed to analyze and predict sentiment in movie reviews. The model is built from
scratch using Python and deployed on Amazon SageMaker for scalable inference.

## Running the project
### 1. Installations
Project Sentiment Analysis Model Faced uses [MiniConda](https://docs.anaconda.com/miniconda/). 
Below is a detailed instructions on how to install the latest version of MiniConda on your chosen machine:

- **Linux:** https://conda.io/projects/conda/en/latest/user-guide/install/linux.html
- **Mac:** https://conda.io/projects/conda/en/latest/user-guide/install/macos.html
- **Windows:** https://conda.io/projects/conda/en/latest/user-guide/install/windows.html

#### Git and version control
These instructions also assume you have `git` installed for working with Github from a terminal window, but if you do not, you can download that first with the command:
```
conda install git
```

### 2. Clone the repository
Clone the repository, and navigate to the downloaded folder. This may take a minute or two to clone due to the included image data.

```
git clone git@github.com:jerryOkafor/SentimentAnalysisModel.git
cd SentimentAnalysisModel
```


### 3. Create and Activate a Virtual Environment
For Windows users, the following commands must be executed from the **Anaconda Prompt** rather than a Windows terminal window. For Mac, a normal terminal window will work. 


**Now, we're ready to create our local environment!**
Create (and activate) a new environment, named `deep-learning` with Python 3.6. If prompted to proceed with the install `(Proceed [y]/n)` type y.

- __Linux__ or __Mac__: 

	```
	conda create -n deep-learning python=3.6
	source activate deep-learning
	```
- __Windows__: 


	```
	conda create --name deep-learning python=3.6
	activate deep-learning
	```
	
At this point, your command line should look something like: `(deep-learning) <User> SentimentAnalysisModel $`. The `(deep-learning)` indicates that your environment has been activated, and you can proceed with further package installations.

	
### 4. Install PyTorch and torchvision; this should install the latest version of PyTorch.
	
- __Linux__ or __Mac__: 

	```
	conda install pytorch -c pytorch 
	```
	
- __Windows__: 

	```
	conda install pytorch -c pytorch
	```
### 5. Install a few required pip packages, which are specified in the requirements text file (including OpenCV).

```
pip install -r requirements.txt
```

### 6. That's it! :🥳
Run the notebook. If you are still in the project directory, simply proceed to the second command, else run the first command and then the second one:

```
cd
cd SentimentAnalysisModel
```
Run the notebook

```
jupyter notebook

```
