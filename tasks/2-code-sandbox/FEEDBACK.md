# Golem JS Preview Program Feedback Form

## Introduction
Thank you for taking the time to complete this Golem JS Preview Program task! 
We appreciate your effort in helping us gather valuable feedback and suggestions on how to improve the Golem Network. 
Please fill out the following form to provide your feedback and estimated completion times for each task step.

## Task: #2 - Code Sandbox

### Estimated completion time:
| Task Step                                                                        | Completion Time (in minutes) |
|----------------------------------------------------------------------------------|------------------------------|
| Convert the docker image to a GVMI image and publish it to receive an image hash |       180                      |
| Create an HTML template                                                          |       15                       |
| Add an execution code in Golem JS API                                            |       10                       |

### Feedback:
Please provide any feedback you have regarding each task step below:

#### Step 1: Convert the docker image to a GVMI image and publish it to receive an image hash

Working with your sample image was not helpful for me. I got this error
````
ERROR: Image for name 'golem-example:latest' not found
```
To overcome the issue and test the `gvmkit-build` tool, I was obliged to use another image from Docker Hub.
````
gvmkit-build redis:latest
```
I got this as output
````
Output File  : docker-redis-latest-2334573cc5.gvmi
```

#### Step 2: Create an HTML template

Nothing special here; excepect that the documentation is not very clear concerning API. Or your expectation for this task was not that clear?

#### Step 3: Add an execution code in Golem JS API

I find that your doc lacks clarity. I can't find how to really consume the API. You should give an example with the expected output.

## General feedback:
Is there anything else you'd like to share about your experience 
completing this task or using the Golem Network in general? 

It looks great what you're creating, but there's a need for beta-testers as well as a call for the open source community to support. You need also to think of a dev advocate or evangelist for the project. The documentation is not well writen, there's a need to improve it to make it compliante with Google style.

### Suggestions for Improvement

In order to make it more easier for tester, you need to add example of how it should look like. 

Thank you for your feedback and for contributing to the Golem Network!
