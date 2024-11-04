[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/swKMSSMl)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16850923&assignment_repo_type=AssignmentRepo)
# Computer Graphics Booting Up

## Let's start with ModernGL

This lab stands to prepare the moderngl development environment. Below the steps and requirements for initial coding tasks. Please make sure to edit the python provided files; for dependencies, you can add the files you need.

1. Install moderngl and its dependencies
2. Make sure that the following programs run
    - [01_hello_world.py](./01_hello_world.py)
    - [06_multiple_objects.py](./06_multiple_objects.py)
    - [09_models_and_images.py](./09_models_and_images.py)
        - Modify this program to change the box's texture to a correctly aligned TEC logo
3. Document how to execute the 3 programs in the section below.

* For documentation and missing dependencies, follow these links:
    - https://github.com/moderngl/moderngl
    - https://moderngl.readthedocs.io/

## How to Run Your Program

### Prerequisites
- Python 3.7 or higher
- pip

### Dependencies Installation
Install the required libraries using pip:

bash
pip install moderngl    
pip install numpy      
pip install PyGLM     
pip install objloader  
pip install pygame    


Alternatively, install all dependencies at once using requirements.txt:

bash
pip install -r requirements.txt

### Running the Programs
To execute each program, use Python from the command line:

1. Hello World Example:
bash
python 01_hello_world.py


2. Multiple Objects Example:
bash
python 06_multiple_objects.py


3. Models and Images Example (with TEC logo):
bash
python 09_models_and_images.py



## Grading Policy

- 25% - 01_hello_world.py is running with no errors
- 25% - 06_multiple_objects.py is running with no errors
- 25% - 09_models_and_images.py is running with the requested change (TEC logo texture)
- 25% - Documentation on how to run your programs