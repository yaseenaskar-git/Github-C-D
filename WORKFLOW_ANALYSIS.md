## This is a file to answer the questions analyzing the deploy.yml file. 

### Question 1: What triggers this workflow to run?
Whenever something is pushed to the main branch, or a pull request is made on the main branch, this workflow is triggered to check whether whatever has been pushed or whatever change is in the pull request is correct or not. 

### Question 2: What are the four main steps this workflow performs?
Firstly, it gets the code from the repository, then it validates the HTML file by checking the quality and adherence to HTML standards. Thirdly, it checks for errors to finally upload the site and make it ready for deployment. 

### Question 3: What does the "Checkout code" step do and why is it necessary?
To my understanding, checkout code creates a local version of the code for the workflow to run and test. 

### Question 4: What is the purpose of the environment configuration?
The purpose if to make sure the code is deployed in github pages. 

### Question 5: How does this automated deployment improve reliability compared to manual deployment?
It checks for everything that can possibly go wrong that manual deployment sometimes misses. In addition, it tells what or where the problem is unlike manual deployment in which you have to spend time looking for it yourself.

### Question 6: What would happen if you pushed code to a different branch (not main)?
Nothing will happen and this workflow will not be triggered as it is only for the main branch. 