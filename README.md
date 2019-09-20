# DevOps-HomeWork
This exercise is to assess your technical proficiency with Software Engineering, DevOps and Infrastructure tasks. There is no need to do all the exercises, but try to get as much done as you can, so we can get a good feel of your skillset. Don't be afraid to step outside your comfort-zone and try something new.

As We believe in "Everything as a code", We expect you to write the automation code for every stages. Also, Document the same in clear steps.

If you have any questions, feel free to reach out to us.

# Exercise
This exercise is split in several subtasks. We are curious to see where you feel most comfortable and where you struggle.

# Fork this repository
All your changes should be made in a private fork of this repository. When you're done, please:

Share your fork with the askprasanth user (Settings -> Members -> Share with Member)
Make sure that you grant this user the Reporter role, so that our reviewers can check out the code using Git.
Reply to the email that asked you to do this DevOps Assignment, with a link to the repository that the "askprasanth" now should have access to.
# Notes :- Please don't directly push to this repository.
# 1. Create an API
Create an HTTP-API (e.g. REST) that allows reading & writing (maybe even updating & deleting) data from your database. You may use any tech stack and programming language of your choice for the task.

# 2. Create a Frontend App
Create a sample frontend which should consume the above API. You may use any tech stack and programming language of your choice for the task.

# 3. Dockerize
Automate setup of your Frontend & API with Docker, so it can be run everywhere comfortably with one or two commands.

# Hints
Docker Install
# 4. Deploy to Kubernetes
Enable your Docker containers to be deployed on a Kubernetes cluster. The following deployment tools / provider are acceptable:

Minikube
AWS / Azure / GCP (You may choose to the free tier account provided by the provider)
Hints
MiniKube (free, local)
GKE (more realistic deployment, may cost something)
AKS (more realistic deployment, may cost something)
AWS (more realistic deployment, may cost something)

# 5. Automate the Route to Live
Setup and Configure the Jenkins on the existing Kubernetes Cluster.
Setup the Pipeline which would trigger the job as soon as any checkin happens in the code.
Pipeline should verify the code, Unit Test and whatever else you can think of.
Jenkins should be able to deploy the app to the Kubernetes cluster.
# 6. Whatever you can think of
Do you have more ideas to optimize your workflow or automate deployment? Feel free to go wild and dazzle us with your solutions
