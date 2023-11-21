# JMeter Ultimate Virtual Thread Group Plugin

<h1 align="center"><img src="https://jmeter.apache.org/images/logo.svg" alt="Apache JMeter logo" /></h1>

The JMeter Ultimate Virtual Thread Group Plugin is a Fork from https://github.com/undera/jmeter-plugins.

The goal of this repo is implements the New schema of threads introduced in Java 21 on the Stepping Thread Group and The Ultimate Thread Group.

## Java 21 Virtual Threads: ##  

Java Virtual Threads (Project loom), introduced in Java 21, are lightweight threads provided by the Java platform. Unlike traditional threads, virtual threads are managed by the Java Virtual Machine (JVM) and are intended to be more efficient and scalable.

## JDK 21 Dependency

This project requires **JDK 21 or higher**. Before proceeding, make sure you have JDK 21 installed on your system.

All this lab was performed using AWS Corretto, you can downloaded from: https://docs.aws.amazon.com/corretto/latest/corretto-21-ug/downloads-list.html

Or downloaded it from the official Oracle website or use an OpenJDK distribution.