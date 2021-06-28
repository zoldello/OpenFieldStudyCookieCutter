# OpenFieldStudyCookieCutter
This is a cookiecutter demonstration to illustrate the benefit of using cookiecutters in neuroscience experiments.

It uses two files from from the paper -

**Core principles for the implementation of the neurodata without borders data standard**

**Marike L. Reimer, Lakshmi Bangalore, Stephen G. Waxman, Andrew M. Tan**

**Journal of Neuroscience Methods 348 (2021) 108972 Contents**

It is recommended you read the paper to get a background.

# Usage
Creat virtual enviroment -
```
conda create -n openFieldStudy python=3.8
```
Activate virtual environment
```
conda activate openFieldStudy
```

Install dependencies
```
pip install -r requirements.txt
```

Install Cookiecutter
```
conda install cookiecutter
```

Generate code off Cookiecutter -
```
cookiecutter https://github.com/zoldello/OpenFieldStudyCookieCutter.git
```

Go to directory with the code
```
cd Session
```

Do this to see the files -
```
ls
```

- The files should be -
- Chapter2WorkingWithNWBAndDataJointData.ipynb
- ImportsAndTableDefinitions.py
- notes.txt
- requirements.txt

The credentials were added it. Look at the files to see for youself.
