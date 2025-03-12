---
layout: post
title: "Port Scanner"
date: 2025-03-11 22:49:00 +0000
categories:
  - projects
tags:
  - python
  - networks
  - cyber security
---

After spending hours exploring TryHackMe and working through hands-on labs, I’ve taken my learning and applied it to a real-world scenario: port scanning. 

In this project, I created a simple Python script to scan for open/closed ports on a network (IP address) and calculate a vulnerability score depending on the port open.

If the port is 22, 80 or 443 (there are more IRL) - I altered the risk amount for these ports to be HIGHER:

Port 22 (SSH): High risk if exposed because it can lead to unauthorized access and server compromise. <br>
Port 80 (HTTP): Moderate risk due to the lack of encryption, making it susceptible to interception and manipulation of data. <br>
Port 443 (HTTPS): Lower risk compared to the others, but still vulnerable to misconfigurations and weak encryption practices.


It is always fun playing around with Python and being able to create with my own 10 fingers 
