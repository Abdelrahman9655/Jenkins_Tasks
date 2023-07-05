# Jenkins_Tasks
1- What is Jenkins pipeline?

Jenkins Pipeline (or simply "Pipeline") is a suite of plugins which supports implementing and integrating continuous delivery pipelines into Jenkins. A continuous delivery pipeline is an automated expression of your process for getting software from version control right through to your users and customers.

2- What scripting language is Jenkins pipeline syntax based on?
GROOVY

3- What are the different ways to trigger pipeline?
-Use a webhook
-Use a CI/CD job
-commit commands
-slack commands

4- What is different between parameter and jenkins env variable?
Parameters in Jenkins are user-defined inputs that allow customization and configuration of a build or pipeline run.
While env variables are predefined variables that are set by the Jenkins environment itself or can be explicitly defined within your pipeline script or job configuration.

5- What is organization folder job and what is used for ?
Using Organization Folders
Organization Folders enable Jenkins to monitor an entire GitHub Organization, Bitbucket Team/Project, GitLab organization, or Gitea organization and automatically create new Multibranch Pipelines for repositories which contain branches and pull requests containing a Jenkinsfile .

6- Create jenkins pipeline for your repo and use script file (jenkinsfile) to write pipeline syntax, include parameter functions and env variable in it .

7- Create another multibranch pipeline and filter branches to contain only (master , dev , test )
