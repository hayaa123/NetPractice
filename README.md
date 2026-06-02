*This project has been created as part of the 42 curriculum by hal-lawa*

# Description:

This project is designed to practice subnetting and routing concepts using an interactive simulation provided by 42.

The goal is to understand how IP networks are structured, how packets are routed between networks, and how subnet masks define network boundaries in a practical environment.

## What is TCP/IP?

TCP/IP stands for Transmission Control Protocol / Internet Protocol.

It is a suite of communication protocols used to connect devices over networks such as the internet.

It consists of two main layers:

- Transmission Control Protocol (TCP):
Ensures reliable, ordered, and error-checked delivery of data between applications.
- Internet Protocol (IP):
Handles addressing and routing of packets across different networks.

## What is a Switch?

A network switch connects devices within the same local network (LAN).

It forwards data frames based on MAC addresses, sending information only to the intended device instead of broadcasting to all devices.

## What is a router?

A router connects multiple different networks together.

It forwards data packets between networks using IP addresses and determines the best path for the data to travel.

## What is a default gateway?

The default gateway is typically a router interface that connects a local network to other networks.

When a device does not know how to reach a destination IP, it sends the packet to the default gateway for routing.

##  What is a subnet?

Subnetting is done by manipulating the subnet mask, which determines how many bits are used for:

- Network portion
- Host portion

By borrowing bits from the host part, a large network can be divided into multiple smaller networks.

This improves:

- Network organization
- Security
- IP address efficiency

# Instructions:
- First, download the file attached to the project’s page
- Then, extract the files into any folder of your choice.
- In this folder, run the  run.sh file. This shell script will launch a web server and
open your preferred web browser to the dedicated page.
- The interface contains two main sections:
    - Training mode 
    - Evaluation mode
- To start training:
    - Click on Training
    - Enter your intra username
    - Click Start
- The exersice will begin from level 0 to 10. For each level, a non-functioning network diagram is displayed, after fixing the current level you can 
    - Click Get my config → export your solution.
    - Click Next level → proceed to the next challenge.

- Click Check again → validate your configuration.
- Refreshing the page resets the level to its original state.

## Submission Requirements:

- The repository must include 10 exported configuration files
- Each file corresponds to one level (0 to 10)
- All files must be located at the root of the repository

# Submission details
This project repository contains 10 exported configuration files, one for each level, located at the root of the project.

# Resources
- [ITDose youtube channle](https://www.youtube.com/@ITDose22)
- [What is TCP/IP?](https://www.techtarget.com/searchnetworking/definition/TCP-IP)
- [Transmission_Control_Protocol-wiki](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)
- [What is a network switch? | Switch vs. router](https://www.cloudflare.com/learning/network-layer/what-is-a-network-switch/)
- [Router-wiki](https://en.wikipedia.org/wiki/Router_(computing))