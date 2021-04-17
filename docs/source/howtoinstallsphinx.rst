.. _sphinx:

How to install Sphinx and work with restructured text
======================================================


Source:
https://www.youtube.com/watch?v=WcUhGT4rs5o&list=PLE72UCmIe7T9HewaqCUhKqiMK3LxYStjy&index=2



1. Create a git repo
2. Clone the repo to your local machine

Next, we are going to need Python and pip to install Sphinx. If the commands are unrecognized, add python and pip to your environment variable.

To check the version of python and pip, enter the following commands:
python --version
pip --version

3. Create a virtual environment using the command below. 

python venv <env_name>

With Python 3.0 and above, you do not need to install a virtual environment as it comes installed. It is venv.

4. Activate the virtual environment

cd into your project folder
enter the following command: <env_name>\Scripts\activate.bat

5. Install Sphinx

You can install sphinx in a different folder, say docs.

cd into the docs folder
enter the following command: pip install sphinx
enter the following command: sphinx-quickstart


You run the make html command from the the folder where you have sphinx installed, in this case the docs folder.