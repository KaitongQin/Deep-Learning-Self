# Anaconda Help
## 1. How to build a new virtual environment
### 1.1 use `conda create`
`conda create --name myenv python=3.10`

### 1.2 activate the environment
`conda activate myenv`

### 1.3 install useful package
`conda install numpy`

## 2. How to exit from the virtual environment
### 2.1 deactivate
`conda deactivate`
### 2.2 (Optional) delete the env
`conda env remove --name myenv`

## 3. How to use the vir env in bash
### 3.1 activate(entrance)
`conda activate myenv`
### 3.2 deactivate(exit)
`conda deactivate`

## 4. Others
### 4.1 envs list
`conda info --envs`
`conda env list`

