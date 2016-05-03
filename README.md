# RTI Connext DDS RPMS

This repository contains gradle build jobs to create RPMS for the efficient deployment of RTI Connext DDS Professional.

## Building

1. The following packages need to be added to the directory ./packages:
* rti_license.dat
* rti_connext_dds-<VERSION>-basic-src.zip
* rti_connext_dds-<VERSION>-pro-host-x64Linux.run
* rti_connext_dds-<VERSION>-pro-target-x64Linux2.6gcc4.4.5.rtipkg
* rti_connext_dds-<VERSION>-pro-target-x64Linux3gcc4.8.2.rtipkg
* rti_routing_service-<VERSION>-src.zip

2. Open a terminal and start a gradle build:
~~~~
./gradlew clean buildRpm
~~~~
