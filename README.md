# CI pipeline with github actions 
This ia an example application which will get built via a github actions based CI pipeline

The idea is to build an image whenver a commit is pushed

There are 2 jobs, 
1. For build
2. For deploy, which will only run if the first job is successfull
