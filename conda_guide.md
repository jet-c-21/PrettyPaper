# How to build a virtual environment by conda

1. create venv
   
   ```shell
   conda create --name <ur_env_name> python=<python_version>
   ```
   
   ex:
   
   ```shell
   conda create --name pretty_paper python=3.8
   ```

2. activate the venv
   
   ```shell
   conda activate <ur_env_name>
   ```
   
   ex:
   
   ```shell
   conda activate pretty_paper
   ```

# How to remove a conda virtual env

1. remove venv
   
   ```shell
   conda env remove --name <ur_env_name>
   ```
   
   ex:
   
   ```shell
   conda env remove --name pretty_paper
   ```

# Other useful command

- view all conda env
  
  ```shell
  conda env list
  ```

- deactivate current conda env
  
  ```shell
  conda deactivate
  ```

- update conda
  
  ```shell
  conda update -n base -c defaults conda
  ```
