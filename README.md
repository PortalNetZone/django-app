# django-app
Getting started with Django Framework 
## Initial setup
#### Continuous Integration
1. First of all, create a repository to your project.
2. Integrating the project dependencies list with Pyup:
* Sign in up to your [Pyup](https://pyup.io/sign-in/) account.
* Look at the top screen right corner and click `Add Repo`, take a search for your repository description, or grab it from the list of items below further.
* Once the choice has been made, click `Add`, and a setup screen will prompt to you. Set the Dependency Updates as active and select `all` for all the dependencies; don't accept `Schedule Updates`; leave `Safety CI` marked as true; click `Add` to confirm these settings.
* After that, the initial setup will create a feature branch named `pyup-bot` followed by a pull request, and an opened issue under the repository of the project. \
Don't worry about the message `No requirement files could be found.` there are no pinned dependencies yet, and also no badges for while.
* Then, in GitHub, all you have to do is to accept that initial pull request and confirm it with `Rebase and Merge`, delete the branch, and close the issue.
3. The next steps:
* Take a clone of your project to your local machine.
* From now on, we'll proceed to the next steps by opening issues and creating feature branches. So, you'll need to follow each issue.

##Badges
1. Building Travis CI from Upstream: \
Branch main \
[![Build Status](https://app.travis-ci.com/PortalNetZone/django-app.svg?branch=main)](https://app.travis-ci.com/PortalNetZone/django-app) \
~~Branch master~~ \
[![Build Status](https://app.travis-ci.com/PortalNetZone/django-app.svg?branch=dev)](https://app.travis-ci.com/PortalNetZone/django-app)
2. ~~Building Travis CI from Fork (branch main):~~ \
[![Build Status](https://app.travis-ci.com/PortalNetZone/django-app.svg?branch=main)](https://app.travis-ci.com/PortalNetZone/django-app)
### Providing a test coverage with Codecov:
[![codecov](https://codecov.io/gh/PortalNetZone/django-app/branch/main/graph/badge.svg?token=4GNFEXKWCW)](https://codecov.io/gh/PortalNetZone/django-app)
### Integrating dynamic updates to dependencies of the project with Pyup:
[![Updates](https://pyup.io/repos/github/PortalNetZone/django-app/shield.svg)](https://pyup.io/repos/github/PortalNetZone/django-app/) [![Python 3](https://pyup.io/repos/github/PortalNetZone/django-app/python-3-shield.svg)](https://pyup.io/repos/github/PortalNetZone/django-app/)
### More utils for accomplishment:
* Deployment on [Heroku](https://dashboard.heroku.com/apps/pythonprodjango-app)
* Standard [Django Server](http://127.0.0.1:8000/)