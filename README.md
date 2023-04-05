# Remote Autonomous Control System 2

This repository contains the documentation for RACS2,
and a binary release. 

RACS2 (Remote Astronomy Control System 2) is a remote astronomical observation control system designed for controlling and automating the observation tasks of astronomical telescopes. RACS2 provides a variety of functions including automated observation planning, telescope and equipment control, data storage and processing, among others.

RACS2 uses a distributed architecture, which allows telescope control and data processing tasks to be distributed across multiple computers, and enables collaboration and joint observation between multiple telescopes. RACS2 also provides various interfaces and tools to integrate with other astronomical software and tools.

The core of RACS2 is an component system. In such a system, each component would be responsible for a specific task, such as data acquisition, processing, analysis, or control. These components would discover and connect to each other automatically using a peer discovery mechanism and would exchange data and commands through a ZeroMQ and protobuf.

RACS2 will also provides auxiliary tools in the near future, such as image processing, astronomical data analysis, telescope status monitoring and alarm functions to facilitate observation and data processing.

This repository is created to help distribute these files. The framework and code will be open source in the near future.
