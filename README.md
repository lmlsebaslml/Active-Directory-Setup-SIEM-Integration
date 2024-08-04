# Cybersecurity Lab: Active Directory Setup & SIEM Integration

## Overview
This repository contains resources and documentation for setting up a cybersecurity lab environment focusing on Active Directory setup, SIEM integration, and practical exercises using Splunk, Kali Linux, and Atomic Red Team.

![AD diagram drawio](https://github.com/lmlsebaslml/Active-Directory-Setup-SIEM-Integration/assets/84816463/ff452708-cc12-472f-8a68-4a4b5a81ffb1)


## Table of Contents
1. [Introduction](#introduction)
2. [Setup Instructions](#setup-instructions)
3. [Lab Exercises](#lab-exercises)
4. [Resources](#resources)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction
In this lab, we aim to simulate a real-world scenario by setting up an Active Directory environment at home. By doing so, we'll explore how domain environments work, learn to ingest events into a SIEM (Splunk), and generate telemetry related to attacks seen in the wild to enhance our detection capabilities.

## Setup Instructions
Follow these steps to set up your cybersecurity lab environment:

1. **Hardware Requirements**: Ensure your system meets the lab environment's hardware requirements.
   
-Kali:
      
      4GB ram
   
      8 Processors
   
      Hard Disk 80GB

-Windows 10 Pro: **(It needs to be Pro, Education, or Enterprise version because it is the only way this machine can join the AD domain)**
   
      6GB ram
   
      6 Processors
   
      Hard Disk 60GB
   
  -Splunk server:
   
      16 GB ram
   
      12 Processors
   
      Hard Disk 20 GB
   
  -AD server:
   
      8GB ram
   
      8 Processors
   
      Hard Disk 60GB
   
3. **Software Requirements**: Install necessary software including VMware, Splunk, Kali Linux, etc.
   VMware Workstation:
      https://www.youtube.com/watch?v=4DtIgDuPgdc
   
    Windows 10:
      https://www.microsoft.com/en-ca/software-download/windows10
   
   Kali ISO:
      https://www.kali.org/get-kali/#kali-virtual-machines
   
   Windows Server 2022:
      https://www.microsoft.com/es-es/evalcenter/download-windows-server-2022
   
   Ubuntu sever:
      https://ubuntu.com/download/server
   
   Splunk forwarder:
      https://www.splunk.com/en_us/download.html
   
5. **Active Directory Setup**: Step-by-step guide to setting up an Active Directory domain controller.
      https://www.youtube.com/watch?v=1XeDht_B-bA&list=RDCMUCWoH3f-Yx6TxJfO2O_ezJUw&index=2
6. **Splunk Installation**: Instructions for installing and configuring Splunk for event ingestion.
      https://www.youtube.com/watch?v=uXRxoPKX65Q&list=RDCMUCWoH3f-Yx6TxJfO2O_ezJUw&index=1
7. **Kali Linux Setup**: Guidance on setting up Kali Linux for penetration testing.
     https://www.youtube.com/watch?v=U0AMu3rznc4 
8. **Atomic Red Team Integration**: Integration steps for Atomic Red Team to simulate real-world attacks.
     https://github.com/redcanaryco/invoke-atomicredteam/wiki/Installing-Invoke-AtomicRedTeam 

## Lab Exercises
This section contains a series of practical exercises to perform in your lab environment. Each exercise focuses on a specific aspect of cybersecurity and helps you develop practical skills:

1. **Exercise 1**: Basic Active Directory Administration
2. **Exercise 2**: Ingesting Events into Splunk
   ### SIEM
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Sentinel-0078D4?&style=for-the-badge&logo=Microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-Splunk-000000?&style=for-the-badge&logo=Splunk&logoColor=white" />
    <img src="https://img.shields.io/badge/-Elastic-005571?&style=for-the-badge&logo=Elastic&logoColor=white" />
</div>

4. **Exercise 3**: Conducting Penetration Tests with Kali Linux
5. **Exercise 4**: Simulating Real-World Attacks with Atomic Red Team
   ### Endpoint
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Defender_for_Endpoint-00A4EF?&style=for-the-badge&logo=Microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-Velociraptor-4B275F?&style=for-the-badge&logo=Velociraptor&logoColor=white" />
</div>


6. **Exercise 5**: Analyzing Telemetry Data in Splunk


1. [Example](#Example MITRE ATT&CK)

## Resources
- Additional reading materials, tutorials, and references to deepen your understanding.
- Links to relevant tools and software.

## Contributing
We welcome contributions to enhance this lab environment and its documentation. If you have suggestions, improvements, or new exercises to add, feel free to submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
