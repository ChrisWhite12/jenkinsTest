docker build -t myjenkins-blueocean:2.414.2 .
docker network create jenkins
docker exec jenkins-blueocean cat /var/jenkins_home/secrets/initialAdminPassword
129ba433e1bc4910bb4b7cb3341a196d
