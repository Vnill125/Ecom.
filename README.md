To start project, create Tailwind Theme:

1. Add tailwind to your application in settings.py:
  INSTALLED_APPS = [
  'tailwind',
]

2. python manage.py tailwind init

3. Add your newly created 'theme' app to INSTALLED_APPS in settings.py:
  INSTALLED_APPS = [
  'tailwind',
  'theme'
]

4. Register the generated 'theme' app by adding the following line to settings.py file:
   TAILWIND_APP_NAME = 'theme'

5. Make sure that the INTERNAL_IPS list is present in the settings.py file and contains the 127.0.0.1 ip address:
   INTERNAL_IPS = [
    "127.0.0.1",
]

6. Add NPM_BIN_PATH in settings.py:
   NPM_BIN_PATH = "C:/Program Files/nodejs/npm.cmd"
