# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
The packaje.json file essentially just reads and records information about a project that it needs in order to publish that to the NPM.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
Package.json can really be used anywhere in your project, because really it provides a simple way for people to keep track of packages they use in their application. Sometimes people want to use the same code over and over for different projects, and package.json is perfect for that.
(So like, at the beginning is probably best, but you can use it whenever, or not even at all if you dont want to)
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm i
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
COnnection Strings
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
You can technically just use the `heroku logs` command to see all your recent logs
You can also just: https://dashboard.heroku.com/apps/<app-name>
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
heroku login
heroku git:remote -a <YOUR PROJECT NAME>
git push heroku master
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching is basically a "Lets see if this works okay" kinda project without actually directly affecting the main files. And, if it DOES work okay, and the lead on your team likes it, then that branch can be pushed to your main without any issue.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
COde review should ALWAYS happen after testing. Whether it was a successful test or not, it should be reviewed.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merge
```