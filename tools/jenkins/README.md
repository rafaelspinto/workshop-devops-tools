# [Jenkins](https://jenkins.io/)

## Table of Contents

* [Starting Jenkins](#starting-jenkins)
* [Stopping Jenkins](#stopping-jenkins)


## Starting Jenkins

To start the container, run the following command on the folder of Jenkins:

```shell
docker-compose up -d
```

If this is the first time you are starting the container, then you will be prompted to **Unlock Jenkins** by pasting the *initialAdminPassword*. To do that, you will need to enter the container: 

```shell
docker exec -ti jenkins bash
```

and check the password that was created in the file:

```shell
cat /var/jenkins_home/secrets/initialAdminPassword
```

After that, you can start configuring Jenkins.


## Stopping Jenkins

To stop Jenkins, simply run the following command on the Jenkins folder:

```shell
docker-compose down
```
