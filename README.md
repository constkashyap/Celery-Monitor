# Celery Monitor


## This is a monitor for celery to be used with Django or any other framework in which you are implementing celery.



## Change the project name to yours.

## Start the celery worker by running :

### `celery -A proj worker --loglevel=info`

## Place the monitor in your project directory and run :

### `python monitor.py`

## Details you can get :

### Task Succeeded with the UUID of task.
### Task Failed.
### Worker is back online.

## You can also create your own handlers.

</br>

## You can get more info on Monitoring and Managment of celery here : https://docs.celeryproject.org/en/stable/userguide/monitoring.html

