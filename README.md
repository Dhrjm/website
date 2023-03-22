# website 
## implement Devops Lifecycle for a product based company ######


Git Workflow has to be implemented
Code Build should automatically be triggered once commit is made to master branch or develop branch.
If commit is made to master branch, test and push to prod
If commit is made to develop branch, just test the product, do not push to prod
The Code should be containerized with the help of a Dockerfile. The Dockerfile should be
built every time there is a push to Git-Hub.

The code should reside in '/var/www/html

Job 1 - Building Website
Job 2 - Testing Website
Job 3 - Push to Production

##cluster....
Server 1 - should have Jenkins Master, 
Server 2 - Testing Server, Jenkins Slave
Server 3 - Prod Server, Jenkins Slave

