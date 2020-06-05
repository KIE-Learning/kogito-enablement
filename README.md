# Kogito Enablement Labs and Exercises

![Kogito Logo](/modules/00_Environment_Setup/images/logo.png)

This repository contains labs, exercises and another learning material for [Kogito](https://kogito.kie.org/), the cloud-native business automation toolkit.

## [Environment Setup](modules/00_Environment_Setup/00_1_Environment_Setup_Lab.adoc)

In this lab we cover setting up your machine to be able to do the exercises of our labs. Tools that we will install are Visual Studio Code, the Kogito VSCode plugins, GraalVM and cURL.

## [Getting started](modules/01_Kogito_Getting_Started/01_1_Kogito_Getting_Started_Lab.adoc)

The _Getting Started_ lab provides an introduction to Kogito and introduces concepts like process modeling and REST API generation. You will also learn how Kogito, running on the Quarkus cloud-native Java runtime, allows us to hot/live-reload running applications and generate native executables of our application for cloud-native deployments.

## [Rules and RuleUnits](modules/02_Kogito_Rules/02_1_Kogito_Rules_Lab.adoc)

In this lab you will learn about business rules in Kogito implemented using a concept called _Rule Units_. You will learn how the Kogito code-generation engine allows you to directly expose your business rules as a rules microservice for cloud deployments.

## [Decision Model & Notation (DMN)](modules/03_Kogito_DMN/03_1_Kogito_DMN_Lab.adoc)

DMN is a standard by the Object Management Group for decision modeling and implemntation. In this lab you are introduced to DMN in Kogito, showing the power of a cloud-optimized DMN runtime for cloud and container based decisioning.

## [Context & Dependency Injection](modules/04_Kogito_CDI/04_1_Kogito_Service_Task_CDI_Lab.adoc)

Kogito is built on top of open standards. In this exercise you will learn how you can use standards like [Context & Dependency Injection (CDI)](https://www.baeldung.com/java-ee-cdi) to implement logic in your Kogito processes, rules and decisions.

## [Microservices Orchestration](modules/05_Kogito_Service_Orchestration/05_1_Kogito_Service_Orchestration.adoc)
Interaction between microservices can be done in multiple ways. One of there approaches is _Orchestration_. Kogito's process engine provides a powerful approach to microservices orchestration using the BPMN2 standard to describe the orchestration flow. In this lab you will learn how to use the workflow engine to orchestrate microservices, and how to integrate the engine with integration technologies like JAX-RS (REST) Clients and [Apache Camel integration framework](https://camel.apache.org/).
