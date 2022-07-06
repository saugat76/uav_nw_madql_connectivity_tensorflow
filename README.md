# UAV_SubBand_Allocation_DQN
Allocation of the resource blocks to the ground user for distributed UAV based cellular system with only the transfer of reward values. Additional improvement over the other setup by the use of Deep Q Learning approach.

# Dependencies installation and steps to run on a Conda Environment
## 1) Installation of Anaconda / Ommit this step in already installed 
Install annconda on your machine. For further information follow this link https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html
## 2) Open anaconda prompt and create a new conda environment with python 3.10. After that activate the environment
```conda create -n uavenv python==3.10
conda activate uavenv
```
## 3) Install the following dependencies
Install gym, tensorflow-gpu with it's required dependencies
```
conda install gym
conda install pip
pip install tensorflow-gpu
```
## 4) Open your IDE through the conda environment
### Preferred Method
If you already have Visual Studio Code. You can enter the following command in the same conda enviroment to open up the IDE.
```
code
```
### Alternative Method
You can also open up your own IDE and change the interpreter setting to the python.exe file with the .conda/env/uavenv folder before running the code
## 5) Optional step to clone git 
Inside visual studio code click on "New File" and in file and inside explorer tab click on "Clone Repository".
Enter the URL of this git repo to run this code.
https://github.com/saugat76/UAV_SubBand_Allocation_DQN.
