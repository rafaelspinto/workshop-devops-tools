# DevOps Tools Workshop (Work in Progress)

This workshop is designed to help you start or improve your knowledge of working in a *DevOps environment*. 

The goal for this workshop is to prepare a fully working set of tools that will help you start building the *"DevOps environment"*. For simplicity reasons some of the tools will be setup locally while others will be public/online.

## What is DevOps

*First rule of DevOps, there are no rules*. You will not find a single or an exact definition for *DevOps*, just try to google it and you will see. In my opinion that's the way how it should be. *DevOps* is dependent on a team and how that team performs, so, in this sense every team will have its own definition.

With that being said, ***DevOps*** or ***Engineering Agility*** as I like to call it, is ***Agile 2.0*** because it's all about being agile in a fast and highly competitive world by taking advantage of technology and engineering best practices to easily adapt to change.

**Engineering Agility** = **Culture** + **Technology** + **Best Practices** + **Talent**

## Table of Contents

* [Quick start](#quick-start)
* [How it works](#how-it-works)
* [Tools](#tools)

## Quick start

Prerequisites

* You have [docker](https://www.docker.com/) installed
* You have [docker-compose](https://docs.docker.com/compose/) installed


## How it works

This workshop uses [docker-compose](https://docs.docker.com/compose/) to easily setup the local tools. Inside the [tools](/tools) folder there are the required files and instructions of usage per tool.


## Tools

There are virtually an infinite amount of tools that you can use to help you on the technology side but all of them will fall under one or more of these categories:

1. [Project Tracking](#1-project-tracking)
2. [Source Code Management](#2-source-code-management)
3. [Automation Server](#3-automation-server)
4. [Static Code Analysis](#4-static-code-analysis)
5. [Testing](#5-testing)
6. [Artifact Management](#6-artifact-management)
7. [Instant Feedback](#7-instant-feedback)
8. [Analytics & Monitoring](#8-analytics--monitoring)

The tools identified here will be labeled as:

* **Local setup** - For these kind of tools this workshop will provide a simple way to have a local installation. 
* **Public free** - These kind of tools provide a version that you don't need to pay for usage although there is a chance that you may pay for certain features (upgrades).
* **Public commercial** - Using these kind of tool implies that you will pay a fee.

**Notes:**

* A **better tool** does not exist. It's up to the team to decide which tool suits its needs.
* This list will be updated on a regular basis.


### 1. Project Tracking

* [Trello](https://trello.com/) - Public free
* [JIRA](https://www.atlassian.com/software/jira) - Public commercial

### 2. Source Code Management

* [Git](https://git-scm.com/) - [Local setup](https://git-scm.com/downloads)
* [Github](https://github.com/) - Public free
* [Bitbucket](https://bitbucket.org) - Public free

### 3. Automation Server

* [Jenkins](https://jenkins.io/) - [Local setup](/tools/jenkins)
* [Travis CI](https://travis-ci.org/) - Public free

### 4. Static Code Analysis

* [Sonarqube](https://www.sonarqube.org/) - [Local setup](/tools/sonarqube)
* [SonarCloud](https://sonarcloud.io/) - Public free

### 5. Testing

* [Selenium Grid](http://www.seleniumhq.org/) - [Local setup](/tools/selenium-grid)
* [Web Page Test](https://www.webpagetest.org/) - [Local setup](/tools/wpt)


### 6. Artifact Management

* [Nexus OSS](https://www.sonatype.com/nexus-repository-oss) - [Local setup](/tools/nexus)
* [Artifactory](https://jfrog.com/artifactory/) - Public free

### 7. Instant Feedback

* [Slack](https://slack.com/) - Public free

### 8. Analytics & Monitoring

* [Elastic](https://www.elastic.co/products) - [Local setup](/tools/elastic)
