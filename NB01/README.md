# Getting started 

#### Explanation

Create a new Python 3.6 env: 

```
conda create -n datvis36 python=3.6 anaconda
```

Activate it:

```
source activate datvis36 
```

Clone this repository and navigate into it:
```
git clone https://github.com/agahkarakuzu/datavis_edu.git
cd datavis_edu
```

Install requirements: 
```
pip install -r requirements.txt
```
Installation of the packages defined by `postBuild` script may change from OS to OS. If you are on Ubuntu `./postBuild` should do the trick. If you are on OSX or Windows, just copy paste the whole content to your terminal. 

You are ready to go! Start your favorite Jupyter interface (ensure that you are in repo): 

```
jupyter notebook 
OR
jupyter lab
```

