# project: gada
Google Advanced Data Analytics capstone 

This is the final project of the Google Advanced Data Analytics course on https://www.coursera.org/professional-certificates/google-advanced-data-analytics

Data source: https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv

## To launch

```bash
docker build -t gada .
docker run -p 8888:8888 gada

> Tip: If you're using Docker, make sure to install from `requirements.txt` only.  
> For debugging or replicating the local environment exactly, use `requirements-freeze.txt`.
