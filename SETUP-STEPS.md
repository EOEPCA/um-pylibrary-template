# Steps to use this template
- Edit docs to fit your repository
- Edit readme to fit your repository
- Edit setup.py to fit your repository
- Replace code and requirements.txt in src by your own! Make sure to use pytest, or replace it in the .travis.yml to use the correct testing suite 
- Un-comment the "notifications" segment in .travis.yml, and input the correct data for slack and/or emails you want to notify
- Generate a new token in PyPi account exclusively for this library

- setup the following variables (in travis webpage, for this project) to ensure travis automated CI works (https://travis-ci.com/github/EOEPCA/<project>/settings):
    1. GH_REPOS_NAME (this repo's name)
    2. GH_USER_NAME (GitHub name for the responsible of this module)
    3. GH_USER_EMAIL (GitHub email for the responsible of this module)
    4. TOKEN_PYPI (Token you created in a previous step)

- Destroy this file, this is only intended to apply the template!
