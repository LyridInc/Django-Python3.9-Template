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

<a href="https://app.lyrid.io/login?one-click-deploy=true&origin=github&repository-url=https://github.com/LyridInc/Django-Python3.9-Template.git&env=empty&project-type=Django-Python3.9&repo-name=Django-Python3.9-Template">
  <button>
    <img src="/static/assets/svg/ocd_deploy_to_lyrid.svg" style="height: 50px; width:200px;"/>
  </button>
</a>