# Celery Monitor


## This is a monitor for celery to be used with Django or any other framework in which you are implementing celery.



## Change the project name to yours.

## Start the celery worker by running :

### `celery -A proj worker --loglevel=info`

## Start the beat scheduler :

### `celery -A proj beat -l info`

## Place the monitor in your project directory and run :

### `python monitor.py`

## Details you can get :

### Task Succeeded with the UUID of task.
### Task Failed.
### Worker is back online.

## You can also create your own handlers.

## To Know more about Monitoring and Management of celery clusters visit :

https://docs.celeryproject.org/en/stable/userguide/monitoring.html

