# Reproducing this web app
To recreate this web app on your own computer, do the following.

# Create conda environment
Firstly, we will create a conda environment called eda

     conda create -n eda python=3.7.9

Secondly, we will login to the eda environement

     conda activate eda

Install prerequisite libraries

Download requirements.txt file

wget https://github.com/Kisalaykisu/Eda-app-with-Streamlit/blob/main/requirements.txt

Pip install libraries

      pip install -r requirements.txt

Download and unzip contents from GitHub repo

Download and unzip contents from https://github.com/Kisalaykisu/Eda-app-with-Streamlit.git

Launch the app

      streamlit run app.py
