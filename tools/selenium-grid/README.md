# [Selenium Grid](http://www.seleniumhq.org/)

A Selenium Grid consists of a single Hub and one or more Nodes. The workflow of running tests using a Selenium Grid is as follows: 

1. The hub receives a test to be executed along with information on which browser and ‘platform’ (i.e. WINDOWS, LINUX, etc) where the test should be run. It ‘knows’ the configuration of each node that has been ‘registered’ to the hub. 
2. Using this information it selects an available node that has the requested browser-platform combination. 
3. Once a node has been selected, Selenium commands initiated by the test are sent to the hub, which passes them to the node assigned to that test. 
4. The node runs the browser, and executes the Selenium commands within that browser against the application under test.


The docker-compose.yml provided in this workshop contains a definition for a **Hub**, a **Chrome Node** and a **Firefox Node**. There are two other definitions: **Chrome-Debug** and **Firefox-Debug**, that allows users to see in the tests running in realtime using a VNC client.


## Table of Contents

* [Starting a Selenium Grid](#starting-a-selenium-grid)
* [Stopping a Selenium Grid](#stopping-a-selenium-grid)


## Starting a Selenium Grid

To start the grid you can specify the number of node instances by using the ```--scale``` flag of ```docker-compose```:

```--scale <service_name>=<number_of_instances>```

For example, to start a grid with 1 hub and 3 chrome instances, run the following command:

```shell
docker-compose up -d --scale chrome=3 --scale firefox=0 --scale chrome-debug=0 --scale firefox-debug=0
```

**Note:** If you run the default command:

```shell
docker-compose up -d
```
it will start 1 hub and 1 instance of each of the types of nodes defined in the yaml file.

## Stopping a Selenium Grid

To stop the Selenium Grid, simply run the following command on the Nexus folder:

```shell
docker-compose down
```
