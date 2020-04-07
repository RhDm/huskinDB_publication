<a href="https://huskindb.drug-design.de" target="_blank"><img src="https://github.com/RhDm/huskinDB_publication/blob/master/images/Logo_new_12.png" alt="drawing" width="400px"/></a>

# Jupyter Notebook which leads through the code used to create [huskinDB](https://huskindb.drug-design.de) publication Figures
#### It is possible to install all required packages locally and run the code (for this purpose, please follow the installation guide)
## or run it on Binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/RhDm/huskinDB_publication.git/master)

#### Minimal macOS/Linux Installation (Python3 or even Python2.7)
open Terminal and input following commands:
1. clone the repository into some folder
```
git clone https://github.com/RhDm/huskinDB_publication.git
```
2. navigate into huskinDB_publication folder
```
cd huskinDB_publication/
```
3. install pip and create a separate virtual environment
```
pip install virtualenv
virtualenv -p $(which python) venv
```
4. activate the environment
```
source venv/bin/activate
```
4. install required packages
```
pip install -r requirements.txt
```
5. run Jupyter Notebook
```
jupyter notebook
```
6. click on the file `huskinDB_publication_plots.ipynb`
