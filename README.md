# Lyrid Python 3.9 Django Template

## Set virtual environment(optional):
```
python -m venv lyrid-venv
source lyrid-venv/bin/activate
```

## Run locally with:
```
pip install -r requirements.txt
python manage.py runserver
```

Open http://localhost:8000

## Edit the names (optional):
Open .lyrid-definition and change the App and Module name, because this will override another applications with the same name in the platform.

## Then submit to Lyrid Platform:

```
lc code submit
```
Wait until the cloud platform to finish with the build and the default deployment.

## Start hacking:

Edit the route url, settings, and views at /entry folder with your custom APIs. 

Add more middlewares or your business logic in there.
