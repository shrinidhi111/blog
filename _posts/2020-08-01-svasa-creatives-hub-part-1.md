---
layout: post
title: "What is the Svasa IoT IP Switch"
author: "Shrinidhi"
categories: blog
date: 2020-08-02
---

# Architectue

4 main components. 

1. Cloud
2. Graffer
3. Instrument
4. Agent

## Graffer

The managing module that handles and monitors the local IoT instruments. These IoT devices can be connected to a network or directly to the graffer.

Graffer is not a physical device but a service that can run on a physical device. It can installed on a Windows computer as a GUI application and connect to Arduino based instruments over USB or it can be installed as CLI in raspberry pi controlling devices over the local network.

Support will be soon added for Google Home and iOS Home either to the graffer (preferred) or to the instruments directly.

## Instruments

These are the IoT devices all the way from Arduino based controllers to LAN printers. Simple devices that perform action based on the commands from Graffers.

### Agent

The interface with which end users interact with their devices. Users send commands such as activate and deactive to the desired instrument connected to graffer. Commands can be sent from any location. It can be installed in your phone as an app or simply use the web client.

### Cloud

The one who connects agents to graffers and handles all the authentication and monitoring of it.
<!-- 
#### Agent Interaction

```mermaid!
graph TD;
  Instruments--\>Cloud;
  Grafers--\>Cloud;
``` -->

