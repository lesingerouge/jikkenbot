# jikkenbot
Deployment management system

The main purpose of this system is to streamline the deployment and management of test branches in a containerized environment.

The system will pull the code from the repo, build the branch, build the image and then push the result to a registry and also deploy the image (and any dependencies defined) to a Docker Engine or Swarm infrastructure.
