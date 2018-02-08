---
title: "Deployment"
author: "Peter Whitney"
 
==================
deployment->pom.xml

This is a multi-module maven pom file that composes
two example child projects, impala and wordcount.

Note that two child projects are used to demonstrate how
scripted deployment can be used for the purpose of deploying
different code artifacts to a remote host.  

==================
deployment->impala
deployment->impala->pom.xml

Contains all artifacts of a simple example impala script
project. The intent of this project is to demonstrate remote
deployment of script based code artifacts.

The pom.xml file contains all of the remote deployment operations.

==================
deployment->wordcount
deployment->wordcount->pom.xml

Contains all artifacts of a simple example spark / scala implementation
The intent of this project is to demonstrate remote deployment of jar 
based code artifacts.

The pom.xml file contains all of the remote deployment operations.