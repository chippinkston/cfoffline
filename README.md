# CFOffline
This project is to explore using websockets as a heartbeat between two instances of the same code base.

The goal is to be able to detect when one version is no-longer connected to the master and to toggle where and how it stores and retreives data.

## Goals
The purpose of this project is to figure out how to have a 'modile' version of the application stay in sync with global 'server'.  To this end, there are two (2) machines that will fulfill those roles.  For testing purposes, we need to be able to disable the network connection to the 'server' instance, but still allow for modifications to happen in the 'mobile' version.



## Requirements
* Commandbox 3.0.1
* ColdFusion 11
