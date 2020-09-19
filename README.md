#a1_Supervised_Learning
# Assignment 1 - Supervised Learning on Bitcoin transaction history data and Skin-Non skin data

This doc helps you prepare your local python environment. After have a python environment and jupyter notebook ready then you will be able to run the different machine learning experiments on the two groups of data. Let's get started! 

1. Get repository
   - Pull this repository to your local machine: <https://github.com/ziyanxiongxin/a1_Supervised_Learning>

2. Set up the environment
   - Use Conda to setup your environment, simply run: conda create --name ml_env python=3.7 -y. Once it's created you can activate it by running: 
                          ```
                          conda activate ml_env
                          ```
   
   
   

3. install packages
   - You can see the complete list of packages and required versions in requirements.txt. 
   - To install, navigate to a1_Supervised_Learning directory, activate your environment (```conda activate ml_env```), then run: 
                          ```
   	                       pip install -r requirements.txt
                          ```
   	
   	
   

4. Open jupyter notebook
   - We have already installed jupyter in step 3, to open it up you can run: jupyter notebook

5. Download the two groups of data to the current folder. You need to unzip the bitcoin data.
   - Bitcoin transaction history data: <https://archive.ics.uci.edu/ml/datasets/BitcoinHeistRansomwareAddressDataset>
   - Skin-Non skin data: <https://archive.ics.uci.edu/ml/datasets/Skin+Segmentation>

6. Navigate to subfolders to run experiment
   - There are 12 subfolders and each contains experiment codes for one supervised learning algorithm used on one group of data. For example: the folder 'Decision_bitcoin' is the decision tree algorithm on bitcoin transaction data. Each folder also contains the graph in the analysis write-up generated from the codes


 



