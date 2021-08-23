# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
Contains code that heroku needs to run dependencies. 
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
Just like .env, it needs to be directly inside the server folder.  It will not be found correctly if it is nested elsewhere.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
??  outDir: '../YOURSERVERNAME/client'
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
.env files
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
Click on View Logs, or use the command prompt
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Put in the settings for heroku to watch for changes - anytime it "sees" changes, it updates your app.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
You can make and test all changes that you need to on the development or main branch without making your new code live.  Once all bugs are fixed, you can send changes to the production branch.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Before code is sent to production branch.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merge
```
