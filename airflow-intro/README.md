# Airflow Setup on Local Docker Machine


## UV Commands
1. Setup Python environment by running following command
```zsh 
uv venv --python 3.11
``` 
2. Activate the python env 
```zsh 
source .venv/bin/activate
``` 

3. Install the apache airflow dependencies
```zsh 
uv pip install apache-airflow==3.0.0
``` 

## Docker Compose
1. Run docker compose file
```zsh 
docker compose up
``` 

## Airflow
1. Login into the [Airflow Link](http://localhost:8080)
2. Enter the credentials
- Username : airflow
- Password: airflow
3. [Reference Links](https://airflow.apache.org/docs/apache-airflow/stable/index.html)