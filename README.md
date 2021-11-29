# moldesc-app

# Watch the tutorial video

[How to build a Bioinformatics web app (Molecular Descriptor Calculator) in Python | Streamlit #21](https://youtu.be/htBIP17S-20)

<a href="https://youtu.be/htBIP17S-20"><img src="http://img.youtube.com/vi/htBIP17S-20/0.jpg" alt="How to build a Bioinformatics web app (Molecular Descriptor Calculator) in Python | Streamlit #21" title="How to build a Bioinformatics web app (Molecular Descriptor Calculator) in Python | Streamlit #21" width="400" /></a>

# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *moldesc*
```
conda create -n moldesc python=3.7.9
```
Secondly, we will login to the *moldesc* environement
```
conda activate moldesc
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://raw.githubusercontent.com/dataprofessor/moldesc-app/main/requirements.txt

```

Pip install libraries
```
pip install -r requirements.txt
```

###  Download and unzip contents from GitHub repo

Download and unzip contents from https://github.com/dataprofessor/moldesc-app/archive/main.zip

###  Launch the app

```
streamlit run app.py
```
