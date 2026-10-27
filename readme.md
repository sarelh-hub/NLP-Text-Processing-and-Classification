## **Project Overview**

Recruiters and HR teams often deal with thousands of resumes, making manual screening a time-consuming and inefficient process. Extracting key information such as skills, experience, and education from resumes in different formats adds further complexity.

In this project, we build an NLP-based application to automatically parse resumes and extract relevant information using techniques like Named Entity Recognition (NER). The system processes resumes in PDF format using OCR with Apache Tika and applies text preprocessing methods such as tokenization, lemmatization, and stopword removal to clean and structure the data. We leverage the SpaCy library to train a custom NER model capable of identifying entities like name, location, skills, education, and work experience. The model is trained incrementally and evaluated to ensure accurate extraction across different resume formats.

The goal of this project is to create an efficient and scalable solution that can automate resume screening, reduce manual effort, and improve hiring efficiency, enabling organizations to quickly identify the most suitable candidates.


### Steps for running the notebook locally

The Python 3.7 version is supported for the execution of this project.
1. Running the codes locally: Python 3.7
    - Create a virtual environment: In the terminal or command prompt, use the following command to create a new virtual environment:

        - For Windows:
            `py -3.7 -m venv env`

        - For macOS and Linux:
            `python3 -m venv venv`
        This command creates a new virtual environment named "venv" in the current directory.

    - Activate the virtual environment:

        - For Windows (Command Prompt):
            `venv\Scripts\activate`


        - For macOS and Linux (Terminal) :
            `source venv/bin/activate`
    
Once the virtual environment is activated, you should see the environment name (e.g., (venv)) in the terminal or command prompt.

- Install project requirements: With the virtual environment active, you can now install the required packages for your project. Typically, the required packages are listed in a requirements.txt file. Make sure you have the requirements.txt file for your project.

2. Setup the pip and installing dependencies in Virtual environment

    - Upgrade pip and cpython seperately
        `python -m pip install --upgrade "pip<21.0" wheel setuptools`
        `pip install "cython==0.29.37"`


    - To install the requirements, use the following command:
        `pip install --no-build-isolation -r requirements.txt`
        
## **Execution Instructions**

* Install the requirements using the command 'pip install --no-build-isolation -r requirements.txt'
* When running the Jupyter Notebook, make sure to select the kernel corresponding to the virtual environment you created. This ensures that the notebook runs within that environment.


### Modular code

- Inside Virtual Environment
- Please create the directory structure in the following way to execute.

- "D:/ProjectProd/Resume_Parser"
- Run Code `python Engine.py`

