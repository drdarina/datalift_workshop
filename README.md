# Ratings Workshop
## At Datalift on June 24 2022

### Setup:
pipenv install
pipenv install git+https://github.com/drdarina/glicko2.git@master#egg=glicko2
(optional - alternatively you can pipenv run jupyter lab) pipenv run python -m ipykernel install --user --name=datalift-workshop
Glicko2: please use this package git+https://github.com/drdarina/glicko2.git@master#egg=glicko2 and NOT the default Glicko2 package that you get from Pypi!

Open the `test_imports.ipynb` notebook and make sure that you can run the imports!

Troubleshooting: 
- Cannot import Glicko2: Please check that you have installed the correct package. Do NOT install from Pypi.