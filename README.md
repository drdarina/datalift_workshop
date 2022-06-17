# Ratings Workshop
## At Datalift on June 24 2022

### Setup:
Install pipenv: https://pipenv.pypa.io/en/latest/
run `pipenv install`
run `pipenv install git+https://github.com/drdarina/glicko2.git@master#egg=glicko2`
(optional - alternatively you can pipenv run jupyter lab) pipenv run python -m ipykernel install --user --name=datalift-workshop

*IMPORTANT* Do not run `pipenv install glicko2` - this will install a different package that we do not want to use

Troubleshooting: If `from glicko2 import Glicko2` raises an `ImportErorr` you didn't follow the steps above and installed the wrong glicko package.

Open the `start_here.ipynb` notebook and make sure that you can run the imports!

*Please test that you can run all imports in the first cell of the notebook before the workshop*
