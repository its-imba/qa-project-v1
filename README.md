
# QA Final Project

The minimum viable product was to plan, design and implement a solution for automating the development and deployments of a basic user authentication application making use of tools, methodologies and technologies that were covered during our training. 


The application consists of the app and database in a single docker container due to gaps of knowledge that were not filled throughout the weeks of training. There is also a lack of testing during the CI/CD pipeline due to this. Unfortunately we were not given any further support or extentions for our projects so the main focus was just to get a functioning app up and running through a pipeline.

## Architecture

Below you can find my ERD, showing a one-to-many relationship:

![Alt text](https://github.com/its-imba/qa-project-v1/blob/master/Screenshot%202022-10-28%20at%2010.10.58.png)

## Pipeline

The pipeline is automated via Jenkins on an Azure VM. Code is pushed to github, and from there ideally it would trigger a webhook that would tell Jenkins to run the CI/CD pipeline. However due to changes with github API and webhooks now using a personal access token, I was unable to find up to date Jenkins documentation to provide me with the information to add this feature.

[Here is the link to the video walkthrough](https://drive.google.com/file/d/1O_9UezGF9Jir6KSp1-zIld0WQFFNoh3G/view?usp=sharing)
