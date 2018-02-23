# [Sonarqube](https://www.sonarqube.org/)

## Table of Contents

* [Starting Sonarqube](#starting-sonarqube)
* [Stopping Sonarqube](#stopping-sonarqube)
* [Analyzing a Project](#analyzing-a-project)


## Starting Sonarqube

To start the container, run the following command on the folder of Sonarqube:

```shell
docker-compose up -d
```

## Stopping Sonarqube

To stop Sonarqube, simply run the following command on the Sonarqube folder:

```shell
docker-compose down
```

## Analyzing a Project

To analyze a project you can choose one of the following scanners:

* [Default](https://docs.sonarqube.org/display/SCAN/Analyzing+with+SonarQube+Scanner)
* [MSBuild](https://docs.sonarqube.org/display/SCAN/Analyzing+with+SonarQube+Scanner+for+MSBuild)
* [Maven](https://docs.sonarqube.org/display/SCAN/Analyzing+with+SonarQube+Scanner+for+Maven)
* [Gradle](https://docs.sonarqube.org/display/SCAN/Analyzing+with+SonarQube+Scanner+for+Gradle)
* [Ant](https://docs.sonarqube.org/display/SCAN/Analyzing+with+SonarQube+Scanner+for+Ant)
* [Jenkins](https://docs.sonarqube.org/display/SCAN/Analyzing+with+SonarQube+Scanner+for+Jenkins)
* [VSTS-TFS](https://docs.sonarqube.org/display/SCAN/Analyzing+with+SonarQube+Extension+for+VSTS-TFS)
