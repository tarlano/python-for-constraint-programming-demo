# Python for Contraint Programming Demo

A few examples on how to do Constraint Programming with Python and the
OrTools library. A few classic problems are solved, like the Job-Shop
and the N-Queens problems.

## Installation

Follow the steps below to run the code on a Debian Stretch.

    apt-get update && apt-get -y install build-essential virtualenv
    
Clone this project's repository

    git clone git@bitbucket.org:<repository-url>.git
    
Create the virtual environment and install the dependencies, including
the OrTools library (currently only available via `easy_install`)

    virtualenv venv
    . venv/bin/activate
    pip install -r <project-path>/requirements.txt
    easy_install ortools

Launch the Jupyter Notebook application and run the examples from
there

    jupyter notebook
