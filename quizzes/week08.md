# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
Package.json is a file used to list what packages need to be installed to run the project.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
At the top level, you will need your package.json to show what dependencies and metadata are.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
NPM run build, similar to the dev runtime, if there are issues it will spit them out here before you're allowed to put it out to the world.
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
.env or environment variables.
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
You can view logs with the Heroku CLI, the dashboard, your logging add-on, or in your log drain.

```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
You push your changes through using git, the good old fashioned way.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
If you have a live production version, you need a space that isn't the one being used by thousands of people to create new functionality (and break old ones)
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
BEFORE production.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Combining 2 branches is called a merge.
```