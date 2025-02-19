
# Sirius Observation Study

This is a small Python JupyterLab project to dynamically model the heliacal rising of the star Sirius for a given place and date, so as to assist with planning an observation run.

It's intended solely for personal development and combines my interest in Python coding with some basic astronomy concepts. It demonstrates the use of the Astropy and Astroplan packages to fetch realtime positions of the Sun, Sirius, and Moon. It uses dimensionalized values, transforms them to a local observation context, confirms their rise times, and plots their positions with Matplotlib.

## To preview this workbook:
[sirius_obs_study.ipynb](https://github.com/aramis-dm/sirius_obs_study/blob/main/sirius_obs_study.ipynb)

## To setup this workbook:

Clone the repository:
```bash
git clone https://github.com/aramis-dm/sirius_obs_study.git
cd sirius_obs_study
```
Create and activate a virtual environment:  
```bash
python -m venv venv
source venv/bin/activate  
```  
Update pip and install the requirements:  
```bash
python -m pip install pip --upgrade
pip install -r requirements.txt
```
Run JupyterLab workbook  
```bash
jupyter lab sirius_obs_study.ipynb  
```
