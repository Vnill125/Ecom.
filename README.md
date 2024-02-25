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



![ecom 1](https://github.com/Vnill125/Ecom./assets/129762972/b0f3eba1-0c6c-4d0b-bf4b-bbda89da530a)
![ecom2](https://github.com/Vnill125/Ecom./assets/129762972/67c3d3ed-ed75-4626-8f3a-cdded19c788b)
![ecom3](https://github.com/Vnill125/Ecom./assets/129762972/2a9d9dab-e0ab-4f83-83ad-cfbccbc2f279)
![ecom4](https://github.com/Vnill125/Ecom./assets/129762972/ff5334f1-910b-4c58-adeb-ab48e000a77d)
![ecom6](https://github.com/Vnill125/Ecom./assets/129762972/6f48e425-a8e6-4f61-9815-68c1b470ef39)
![ecom7](https://github.com/Vnill125/Ecom./assets/129762972/a7d38e20-24ec-4f16-b563-cc8647e06251)
![ecom8](https://github.com/Vnill125/Ecom./assets/129762972/9a72349b-5682-4af0-aca7-498680adb9b0)
![ecom9](https://github.com/Vnill125/Ecom./assets/129762972/b834226b-5b98-42a5-a645-0e441c9cc77c)
