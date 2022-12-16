# Django Admin Template

## Library

| name           | version | description          |
| -------------- | ------- | -------------------- |
| Django         | 4.1     | Web Server Framework |
| gunicorn       | 20.1.0  |
| django-environ | 0.9.0   |
| autopep8       | 2.0.1   |

## Command

### Windows

```powershell
New-Item "README.md" -ItemType file
New-Item "requirements.txt" -ItemType file
New-Item .github/workflows -ItemType directory
New-Item -Name deploy.yml -Path .github\workflows
```

```powershell
virtualenv venv
venv\Scripts\activate
pip install -r requirements.txt
```

```powershell
py app/manage.py migrate
# superuser가 없을 경우
# py app/manage.py createsuperuser
py app/manage.py runserver
```

### Reference

- <https://docs.djangoproject.com/en/4.1/intro/tutorial01/>
