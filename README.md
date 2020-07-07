# Awesome FIWARE [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="logo.png" align="right" width="162">](https://www.fiware.org/)

A curated list of FIWARE related projects and resources.

[FIWARE](https://www.fiware.org/) is an open source initiative driving the definition of a universal set of standards for context data management which facilitate the development of Smart Solutions.

The [FIWARE Catalogue](https://github.com/FIWARE/catalogue) is a curated framework of open source platform components which can be assembled together and with other third-party platform, components to accelerate the development of Smart
Solutions.

- This list requires your input for its continuous improvement. Read the [contribution guide](CONTRIBUTING.md) for instructions on how you can contribute.
- For more awesome lists, see [awesome](https://github.com/sindresorhus/awesome).

## Contents

- [Tutorials](#tutorials)
  - [Official FIWARE Courses](#official-fiware-courses)
  - [Useful Third Party Courses](#useful-third-party-courses)
- [Swagger Specifications](#swagger-specifications)
- [NSGI DataModels](#nsgi-datamodels)
- [FIWARE Catalogue](#fiware-catalogue)
  - [Core Context Management](#core-context-management)
  - [IoT Agents](#iot-agents)
  - [Interface to Robotics](#interface-to-robotics)
  - [Security](#security)
  - [Context Data Publication and Monetization](#context-data-publication-and-monetization)
  - [Processing](#processing)
- [Open-Source FIWARE from third parties](#open-source-fiware-from-third-parties)
  - [Security](#security-1)
  - [Robotics](#robotics)
- [Other useful FIWARE sites](#other-useful-fiware-sites)
- [Legacy FIWARE Components](#legacy-fiware-components)

## Tutorials

### Official FIWARE Courses

- [FIWARE Getting Started](https://github.com/FIWARE/tutorials.Getting-Started) - FIWARE 101: An Introduction to the FIWARE Platform.
- [FIWARE Step-by-Step Tutorials](https://fiware-tutorials.readthedocs.io/en/latest/) - Complete collection of tutorials for the FIWARE ecosystem.
- [FIWARE Tour Guide](https://fiwaretourguide.readthedocs.io/en/latest/) - Guided Tour of FIWARE Generic Enablers.
- [FIWARE Academy](https://github.com/FIWARE/academy) - Video tutorials, slide decks and other training materials.

### Useful Third Party Courses

- [FIWARE Zone](https://github.com/FIWAREZone/IoT_Course) - Connecting an Arduino device to FIWARE (in Spanish).
- [IoT Tutorial](https://github.com/rahul606/FIWARE-IoT-Tutorial) - Connecting a Raspberry Pi to FIWARE.
- [FIWARE-interactive](https://github.com/GernotBoege/FIWARE-interactive) - Source code behind the Smart Cities academy course.
- [Temperature Controllers](https://github.com/jmcanterafonseca/fiware-examples) - Connecting several Raspberry Pi controllers via an IoT Agent.
- [FIWARE-Edison](https://github.com/telefonicaid/fiware-edison) - Code examples explaining how to persist Intel Edison sensor data into the Telefónica FIWARE IoT Stack cloud service.
- [FIWARE-Arduino](https://github.com/telefonicaid/fiware-arduino) - Code examples explaining how to persist Arduino data into the Telefónica FIWARE IoT Stack cloud service.
- [FIWARE-ROS](https://github.com/Raffa87/ROS_FIWARE_Tutorial) - Code examples for a simple configured version of FIROS.

## Swagger Specifications

- [NGSI v2 Specification](https://swagger.lab.fiware.org/?url=https://raw.githubusercontent.com/Fiware/specifications/master/OpenAPI/ngsiv2/ngsiv2-openapi.json) - The Swagger specification for the Context Broker.
- [IoT Agent Specification](https://swagger.lab.fiware.org/?url=https://raw.githubusercontent.com/Fiware/specifications/master/OpenAPI/iot.IoTagent-node-lib/IoTagent-node-lib-openapi.json) - The Swagger specification for provisioning IoT
  devices.
- [WireCloud Specification](https://swagger.lab.fiware.org/?url=https://raw.githubusercontent.com/Fiware/specifications/master/OpenAPI/apps.Wirecloud/Wirecloud-openapi.json) - The Swagger specification for the WireCloud Visualization
  enabler.
- [Keyrock Specification](https://swagger.lab.fiware.org/?url=https://raw.githubusercontent.com/Fiware/specifications/master/OpenAPI/security.Idm/Idm-openapi.json) - The Swagger specification for the Keyrock Identity Management enabler.

## NSGI DataModels

- [FIWARE Data Models](https://github.com/FIWARE/dataModels) - Standard NGSI datamodels in the Smart Cities and Agrifood domains.

## FIWARE Catalogue

The FIWARE Catalogue holds the list of official curated contributions to the FIWARE Ecosystem.

### Core Context Management

- [Orion](https://github.com/telefonicaid/fiware-orion) - A context broker which holds information about the current context.
- [Cygnus](https://github.com/telefonicaid/fiware-cygnus) - A data persistence component based on Apache Flume - a means of managing the history of context which is created as a stream of data and can be injected into multiple data sinks.
- [Draco](https://github.com/ging/fiware-draco) - A data persistence component based on Apache NiFi and is a dataflow system based on the concepts of flow-based programming.
- [STH-Comet](https://github.com/telefonicaid/fiware-sth-comet) - A means for storing a short-term history of context data using Mongo-DB.
- [QuantumLeap](https://github.com/smartsdk/ngsi-timeseries-api) - A mechanism for supporting the storage of NGSI data into a time series database (CrateDB).
- [Scorpio Broker](https://github.com/ScorpioBroker/ScorpioBroker)  is a NGSI-LD Broker which can also be used in federated environments.
- [Stellio Context Broker](https://github.com/stellio-hub/stellio-context-broker) is a  NGSI-LD Broker which embeds a property graph database as well as a timeseries historical storage.

### IoT Agents

- [IoT Agent Node Lib](https://github.com/telefonicaid/iotagent-node-lib) - A library for developing your own IoT Agent.
- [IoT Agent for JSON](https://github.com/telefonicaid/iotagent-json) - A bridge between HTTP/MQTT messaging (with a JSON payload) and NGSI.
- [IoT Agent for LWM2M](https://github.com/telefonicaid/lightweightm2m-iotagent) - A bridge between the [Lightweight M2M](https://www.omaspecworks.org/what-is-oma-specworks/iot/lightweight-m2m-lwm2m/) protocol and NGSI.
- [IoT Agent for Ultralight](https://github.com/telefonicaid/iotagent-ul) - A bridge between HTTP/MQTT messaging (with an UltraLight2.0 payload) and NGSI.
- [IoT Agent for LoRaWAN](https://github.com/Atos-Research-and-Innovation/IoTagent-LoRaWAN) - A bridge between the [LoRaWAN](https://www.thethingsnetwork.org/docs/lorawan/) protocol and NGSI.
- [IoT Agent for OPC-UA](https://github.com/Engineering-Research-and-Development/iotagent-opcua) - A bridge between the [OPC Unified Architecture](http://www.opcua.us/) protocol and NGSI.
- [IoT Agent for Sigfox](https://github.com/telefonicaid/sigfox-iotagent) - A bridge between the [Sigfox](https://www.sigfox.com/en) protocol and NGSI.
- [OpenMTC](https://github.com/OpenMTC/OpenMTC) - An implementation of the [OneM2M](http://onem2m.org/) standard with an NGSI northbound interface to the Context Broker.

### Interface to Robotics

- [Fast-RTPS](https://github.com/eProsima/Fast-RTPS) - The default middleware in [ROS2](https://index.ros.org/doc/ros2/) which interfaces with NGSI.
- [Micro-XRCE-DDS](https://github.com/eProsima/Micro-XRCE-DDS) - A robotics publish-subscribe messaging pattern which can be used with a Context Broker.
- [FIROS](https://github.com/iml130/firos) - A translator between the robotics doman and the cloud, transforming [ROS](https://www.ros.org/) messages into NGSI v2 and vice versa.

### Security

- [Keyrock](https://github.com/ging/fiware-idm) - An Identity Manager which support to secure and private OAuth2-based authentication of users and devices.
- [Wilma](https://github.com/ging/fiware-pep-proxy) - A PEP Proxy which can be used to secure NGSI endpoints. Integrates with Keyrock and Authzforce.
- [Authzforce](https://github.com/authzforce/fiware) - Addon which implements PDP/PAP functions within an access control schema based on the XACML standard.
- [APInf](https://github.com/apinf/platform) - An API Management Framework which can be placed in front of NSGI endpoints.

### Context Data Publication and Monetization

- [CKAN extensions](https://github.com/conwetlab/FIWARE-CKAN-Extensions) - Add-on which enables NGSI to offer CKAN open datasets.

- [Biz Framework](https://github.com/FIWARE-TMForum/Business-API-Ecosystem) - An extension which adds backend support for context data monetization.

- [Idra](https://github.com/OPSILab/Idra) - A federator for discovering open datasets across disparate Open Data Management Systems such as CKAN, SOCRATA, DKAN etc.

### Processing

- [Wirecloud](https://github.com/Wirecloud/) - An application mashup platform which integrates NGSI data models and can read from context data sources.
- [Knowage](https://github.com/KnowageLabs/) - A Business Intelligence platform which links to NSGI.
- [Kurento](https://github.com/kurento/) - A compoment which allows for the extratction of context data via media stream processing.
- [Cosmos](https://github.com/ging/fiware-cosmos) - Enabler for simpler Big Data analysis over context.
- [FogFlow](https://github.com/smartfog/fogflow) - A distributed execution framework to support dynamic processing flows over cloud and edges.
- [Perseo](https://github.com/telefonicaid/perseo-core/) - A Complex Event Processing (CEP) component enabling you to fire events which send HTTP requests, emails, tweets, SMS messages etc. as context data changes.

## Open-Source FIWARE from third parties

- [Telefónica FIWARE Connectors](https://github.com/telefonicaid/fiware-connectors) - A set of Python scripts for integrating visualization tools with NSGI Context Brokers.
- [FIWARE Device Simulator](https://github.com/telefonicaid/fiware-device-simulator) - A tool which mimics Ultralight and JSON IoT Agent interactions.
- [FIWARE ArcGIS](https://github.com/esri-es/Fiware-ArcGIS) - A tool which allows you to add sensor information received from a Context Broker into an ArcGIS Online or ArcGIS Server account.
- [CEPWare](https://github.com/AnotherCodeArtist/CEPWare) - An integration of Apache Flink as a Complex Event Processing Unit into FIWARE.
- [SmartSDK recipies](https://github.com/smartsdk/smartsdk-recipes) - A repository containing recipes to deploy different FIWARE Generic Enablers on Docker Swarm clusters.
- [Waste4think NGSI Connector API](http://dev.waste4think.eu/waste4think/NgsiConnector) - This tool is a part of backend implementation of NGSI v2 standard, providing interface for large entities operations coming from various sources such
  as files, legacy systems etc.
- [FIWARE Node-Red](https://github.com/FIWARE/node-red-contrib-FIWARE_official) - An integration of [Node-Red](https://nodered.org/) with FIWARE which supports NGSI-LD.
- [FIWARE Meteoroid](https://github.com/OkinawaOpenLaboratory/fiware-meteoroid) - Meteoroid realizes integrating Function as a Service(FaaS) capabilities in FIWARE.
- [AMQP 1.0 converter](https://github.com/RoboticBase/amqp10-converter) - A protocol converter which bridges between AMQP 1.0 Broker and FIWARE IoTAgent JSON.

### Security

- [Telefónica Steelskin](https://github.com/telefonicaid/fiware-pep-steelskin) - An alternative PEP proxy to secure NGSI endpoints.
- [Telefónica Keystone](https://github.com/telefonicaid/fiware-keystone-scim) - An OpenStack Keystone extension for Identity Management.
- [Telefónica sPassword](https://github.com/telefonicaid/fiware-keystone-spassword) - An OpenStack Keystone extension that enables some extra security checks over user passwords.
- [Telefónica Keypass](https://github.com/telefonicaid/fiware-keypass) - An XACML Authorization Server with PAP and PDP endpoints for securing IoT Platforms.
- [Secure FIWARE](https://github.com/m4n3dw0lf/SecureFiware) - Proposed security measures and security analysis for FIWARE IoT environments.

### Robotics

- [eProsima FIROS2](https://github.com/eProsima/FIROS2) - A [ROS2](https://index.ros.org/doc/ros2/) integrable tool focused in the intercommunication between ROS2 and FIWARE.
- [Tech Sketch FIWARE-ROS Turtlesim](https://github.com/tech-sketch/fiware-ros-turtlesim) - A [ROS](https://www.ros.org/) package acting as a bridge between FIWARE and ROS through MQTT.
- [Robotic Base Core](https://github.com/RoboticBase/core) - A robot management platform based on FIWARE and Kubernetes.

## Other useful FIWARE sites

- [Let's FIWARE](https://www.letsfiware.jp/) - Documentation, Architecture and other FIWARE Information (in Japanese).
- [Let's FIWARE (GitHub)](https://github.com/lets-fiware) - [FIWARE GEs on Raspberry Pi](https://github.com/lets-fiware/fiware-pi), WireCloud widgets and so on.
- [Smart SDK](https://www.smartsdk.eu/) - A “cookbook” for developing smart applications in the FIWARE.
- [Thinking Cities](https://thinking-cities.readthedocs.io/en/latest/) - Telefónica's powered by FIWARE platform.
- [Smart Data Wien](https://smartdata.wien/) - Vienna's Open Data portal powered by FIWARE.

## Legacy FIWARE Components

The following repositories contain code which was at one time part of FIWARE and may still be used by legacy FIWARE systems. Support may be limited, but they may still prove useful for some systems.

- [Telefónica Figway](https://github.com/telefonicaid/fiware-figway) - An obsolete IoT Agent connector, no longer supported. Use the existing IoT Agents instead.
- [Orange Cepheus](https://github.com/Orange-OpenSource/fiware-cepheus) - A complex event processing component for NGSI v1, no longer supported. Use Perseo instead.
- [GING Cloud Portal](https://github.com/ging/fiware-cloud-portal) - The previous Cloud Portal enabler which was replaced by Openstack Horizon, no longer supported. Use Keyrock instead.
- [Chiru POI Data Provider](https://github.com/Chiru/FIWARE-POIDataProvider) - A Point of Interest Data Provider.
- [Telefónica Cloto](https://github.com/telefonicaid/fiware-cloto) - A security FIWARE component for policy management.
- [Telefónica Aiakos](https://github.com/telefonicaid/fiware-aiakos) - A security FIWARE component which acts as a server to manage ssh/gpg keys for users.

## Contributing

Contributions are very welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first. Also, please feel free to report any error.

---

## License

[CC-BY-4.0](LICENSE)
