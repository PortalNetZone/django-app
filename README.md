# django-app
Getting started with Django Framework 
## Inicial setup
1. Create the project repository
#### Continuous Integration
2. Integrating the project dependencies list with Pyup
* Sign in up to your [Pyup](https://pyup.io/sign-in/) account.
* Look at the top screen right corner and click `Add Repo`, take a search for your repository description, or grab it from the list of items below further.
* Once the choice has been made, click `Add`, a Setup screen will prompt to you, set the Dependency Updates as active and `all` for all the dependencies, don't accept `Schedule Updates`, leave `Safety CI` marked as true. Click `Add` to confirm these settings.
* After that, the initial setup will create a feature branch named `pyup-bot` followed by a pull request, and an opened issue under the repository of the project. Don't worry about the message `No requirement files could be found.` there are no pinned dependencies yet, and also no badges for while.
* Then, in Github, all you have to do is to accept that initial pull request and confirm it with `Rebase and Merge`, delete the branch, and close the issue.
