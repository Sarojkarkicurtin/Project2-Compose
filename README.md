# Project2-Compose
we created the docker compose yml file in this repo(Project2-compose) that run dind and jenkins container that uses dind container to run jenkins pipeline
It contain two container as dind and jenkins container that run local host port 8080
dind container contain image,user,privileged
jenkins container contain ports 8080 and environments as "tcp:// dind:2375"
