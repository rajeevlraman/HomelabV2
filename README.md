<!-- homelan V2 -->

# HomelabV2: A Comprehensive Home Lab Environment

# Topics Overview


Welcome to "HomelabV2," my upgraded or fully equipped home lab environment designed to delve deeply into various facets of modern IT infrastructure. This setup provides a robust platform for learning and experimentation in networking, containerization, cloud service integration, security monitoring, and incident response. With a focus on both practical applications and theoretical understanding, HomelabV2 represents a significant step in my journey to mastering these technologies. While the lab is a work in progress, it has already proven to be an invaluable learning tool.

## Hardware and Network Configuration

- **Host PC**: A repurposed gaming PC, upgraded with 64GB of RAM and a 2TB M.2 SSD for enhanced performance, serving as the cornerstone of the lab.
- **Network Segmentation**: The lab network is divided into internal and external segments. I employ SPAN (Switch Port Analyzer) ports to mirror network traffic to my monitoring systems, allowing comprehensive analysis and security testing.
- **Raspberry Pis**:
  - **Raspberry Pi 1**: Hosts Nessus for vulnerability scanning.
  - **Raspberry Pi 2**: Runs Home Assistant, managing home automation.
  - **Raspberry Pi 3**: Dedicated to Pi-Hole, providing DNS services with ad-blocking capabilities.

## Virtual Machines

The virtualized environment extends the capabilities of HomelabV2, running on Windows 11 as the host operating system. The VM lineup includes:

- **Firewall/IDS**: PfSense with the Wazuh extension for intrusion detection and firewall management.
- **External Attack Machine**: Kali Linux for ethical hacking and penetration testing.
- **Windows Domain Controller**: Windows Server 2022, managing the network domain.
- **Client Machines**: Windows 10 and Windows 8, simulating end-user environments.
- **Vulnerable Machines**: Four intentionally vulnerable systems, serving as targets for security testing and practice.
- **Monitoring and Security**:
  - **Wazuh**: For real-time monitoring and log management.
  - **Nessus**: Continues as a key vulnerability assessment tool.
  - **Security Onion**: Integrates with PfSense to monitor all network traffic for potential threats.

## Cloud and Containerization

HomelabV2 leverages Docker extensively, providing isolated environments for various applications and services. Additionally, the lab integrates cloud services to simulate hybrid cloud/on-premises scenarios and is accessible via a VPN, ensuring secure remote access.

## Incident Response and Automation

- **TheHive Project**: Central to my incident response learning, offering a collaborative platform for threat investigation and response.
- **Cortex**: Enhances TheHive with automated analysis and response capabilities.
- **Ansible**: Planned for use in automating and managing configurations across the lab.
- **Kubernetes**: Under consideration for container orchestration, aiming to manage and scale containerized applications efficiently.

## Purpose and Learning Objectives

HomelabV2 is crafted to support a wide range of learning and development goals:

- **Networking**: Explore and understand advanced networking concepts and technologies.
- **Monitoring and Security**: Practice real-time monitoring, prevention, and administrative techniques using industry-standard tools.
- **Home Automation**: Experiment with home automation technologies via Home Assistant.
- **Incident Response**: Develop skills in handling and responding to security incidents using TheHive Project and associated tools.
- **Vulnerability Assessments**: Conduct thorough vulnerability assessments with Nessus and other tools.
- **Security Testing**: Test and validate security measures and configurations in a controlled environment.
- **Cloud Integration**: Explore and integrate cloud services, learning to manage hybrid environments effectively.
- **Automation and Orchestration**: Experiment with Ansible for automation and plan for Kubernetes to manage containers at scale.<br><br>

<img align="center" src="https://i.imgur.com/oBdDYAA.png" /><br/>

## Future Directions

As HomelabV2 evolves, I aim to further enhance its capabilities, potentially incorporating more advanced cloud services, expanding the use of Kubernetes for container orchestration, and deepening my expertise in Security and automation with Ansible.

# Topics Overview

[**Docker**](./Lab/Docker/docker.md) | [**Domain Controller**](./Lab/DomainController/DomainController.md) | [**Kali**](./Lab/Kali/KaliLinux.md) | [**Metasploit**](./Lab/Metasploit/metasploit.md) | [**Nessus**](./Lab/Nessus/Nessus.md)  
[**pfSense**](./Lab/PfSense/pfsense.md) | [**Security Onion**](./Lab/SecurityOnion/assets/SecurityOnion.md) | [**Splunk**](./Lab/Splunk/Splunk.md) | [**TheHive Project**](./Lab/TheHiveProject/TheHive-cortex.mdoject.md) | [**Wazuh**](./Lab/Wazuh/Wazuh.md) | [**Windows**](./Lab/Windows/windows.md) | [**MAC-OS**](./Lab/Macos/MacOS.md) | [**MAC-OS-Architecture**](./Lab/Macos/MacOS_Architecture.md) | [**MAC-OS-NAvigation**](./Lab/Macos/MacOS_Navigation.md)


I look forward to the continued growth and learning that HomelabV2 will facilitate. This setup not only challenges my current hardware but also pushes my understanding and skills to new heights.<br><br>

***The Idea and setup is inspired from various blogs and videos, especially from Gerard Obrien, Christaian , Cyberwox academy, and the Community.***


<!--


Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
