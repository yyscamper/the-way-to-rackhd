## IPMI & BMC

* Intelligent Platform Management Interface
* IPMI is a specifications that provides standardized hardware interfaces and abstraction

* 1998 v1.0, 2001 v1.5, 2004 v2.0

* The primary IPMI features include:

  * Monitoring \(supervision of the hardware\)
  * Recovery Control \(Recover/Restart the server\)
  * Logging \(protocol "out-of-range" states for the hardware\)
  * Inventory \(list of hardware inventory\)

* Avaiable even if system is powered down and no OS loaded

* IPMI Components

  * BMC \(Baseboard Management Controller\): The heart of IPMI
  * IPMB \(Intelligent Platform Management Bus\)
  * ICMB \(Intelligent Chassis Management Bus\)

* Some Data Types

  * SEL \(System Event Logging\)
  * SDR \(Sensor Data Record\)
  * Sensor
  * FRU \(Field Replaceable Unit\)

* System Interfaces

  * KCS
  * Lan
  * Others \(Serial, ...\)

* SOL \(Serial Over LAN\): Redirect data traffic to BMC serial port through an IPMI session

* Disadvantage

  * Insecure

  * Lots of OEM commands

  * Scability problems

* Reference

  * [https://www.cern.ch/it-dep-fio-ds/Presentations/2004/ipmi\_server\_management.ppt](https://www.cern.ch/it-dep-fio-ds/Presentations/2004/ipmi_server_management.ppt)

  * [https://www.thomas-krenn.com/en/wiki/IPMI\_Basics](https://www.thomas-krenn.com/en/wiki/IPMI_Basics)

![](/assets/ipmi-architecture.png)

## Redfish

* An open industry standard specifiction that provide simple, modern and secure management of scalable platform hardware.
* RESTful interface over HTTPs in JSON format bases on OData v4
* A secure, multi-node capable replacement for IPMI-over-LAN.
* Resource Map:![](/assets/redfish-resource-map.png)

* Reference

  * [https://www.dmtf.org/sites/default/files/Introduction\_to\_Redfish\_2015.pdf](https://www.dmtf.org/sites/default/files/Introduction_to_Redfish_2015.pdf)



