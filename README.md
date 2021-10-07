# django-app
Getting started with Django Framework 
## Inicial setup
#### Continuous Integration
1. First of all, create a repository to your project.
2. Integrating the project dependencies list with Pyup:
* Sign in up to your [Pyup](https://pyup.io/sign-in/) account.
* Look at the top screen right corner and click `Add Repo`, take a search for your repository description, or grab it from the list of items below further.
* Once the choice has been made, click `Add`, and a setup screen will prompt to you. Set the Dependency Updates as active and select `all` for all the dependencies; don't accept `Schedule Updates`; leave `Safety CI` marked as true; click `Add` to confirm these settings.
* After that, the initial setup will create a feature branch named `pyup-bot` followed by a pull request, and an opened issue under the repository of the project. \
Don't worry about the message `No requirement files could be found.` there are no pinned dependencies yet, and also no badges for while.
* Then, in Github, all you have to do is to accept that initial pull request and confirm it with `Rebase and Merge`, delete the branch, and close the issue.
3. We will proceed to the next steps by opening issues and creating feature branches. So now, you'll need to follow these issues. 
