# Tinder Backend Deploy

we will be deploying the backend to Heroku.

Create a new Heroku app. fill in the name `bcknd-tinder`.
---
---
One way to do this is to use the Heroku CLI.
If you haven't already, log in to your Heroku account and follow the prompts to create a new SSH public key.
```sh
$ heroku login
```
Create a new Git repository
Initialize a git repository in a new or existing directory
```sh
$ cd my-project/
$ git init
$ heroku git:remote -a bknd-tinder
```

Deploy your application
Commit your code to the repository and deploy it to Heroku using Git.
```sh
$ git add .
$ git commit -am "make it better"
$ git push heroku master
```

Existing Git repository
For existing repositories, simply add the heroku remote
```sh
$ heroku git:remote -a bknd-tinder
```
---
---

2nd way is to use gitHub.


    Steps:
    1. Create a new Heroku app.
    2. fill in the name `bcknd-tinder`
    3. one way to do this is to use the Heroku CLI.
    4. 2nd way to use gitHub