# Assignment 1 - Supervised Learning on Bitcoin transaction history and Skin-Non skin data

This doc is designed to help you prepare your local python environment. After following this README you will have a python environment and jupyter notebook ready and will be able to run the different machine learning experiments on the two groups of data. Let's get started! 

1. Get repository
First thing first, pull this repository to your local machine:
https://github.com/ziyanxiongxin/1_Supervised_Learning

2. Set up the environment:
Use Conda to setup your environment, simply run: conda create --name ml_env python=3.7 -y
Once it's created you can activate it by running: conda activate ml_env
3. install packages
You can see the complete list of packages and required versions in requirements.txt.
To install, navigate to 1_Supervised_Learning directory, activate your environment (`conda activate ml_env`), then run:
pip install -r requirements.txt

4. Open jupyter notebook
We have already installed jupyter in step 2, to open it up you can run:
jupyter notebook

5. Navigate to subfolders to run experiment
There are 10 subfolders and each containes experiement codes for one supervised learning algorithm used on one group of data.
For example: the folder 'Decision_bitcoin' is the decision tree algorithm on bitcoin transcation data. In each subfolders there will be a readme.txt to explain how the experiment is done.
 


