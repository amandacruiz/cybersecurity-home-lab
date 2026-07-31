# Cybersecurity Home Lab

Part of my cybersecurity portfolio:  
[amanda-c-ruiz portfolio](https://github.com/amandacruiz/amanda-c-ruiz)

## Overview

I built a VirtualBox-based cybersecurity home lab to develop hands-on experience with Linux administration, networking, offensive security concepts, and defensive monitoring in an isolated environment.

The lab consists of three virtual machines:

- **Kali Linux** — Attack machine used for reconnaissance, scanning, and security testing.
- **Ubuntu-Target** — Target machine used to host services and simulate vulnerable systems.
- **Ubuntu-SOC** — Security monitoring environment used for log analysis, detection, and defensive security practice.

The lab uses a Host-Only network to allow communication between systems while keeping the environment isolated from my personal network.

## Lab Goals

- Build confidence with Linux environments
- Practice networking concepts
- Learn cybersecurity tools and techniques
- Develop hands-on troubleshooting skills
- Document my progress, configurations, and lessons learned
- Practice both offensive and defensive security workflows

## Current Environment

### Host Machine
- Lenovo Yoga 2-in-1
- Windows 11 Pro
- 16GB RAM
- 1TB storage

### Virtualization
- VirtualBox

### Virtual Machines

- **Kali Linux** - offensive security learning environment used for reconnaissance, scanning, and security testing
- **Ubuntu-Target** - target machine used for hosting services and simulating vulnerable systems
- **Ubuntu-SOC** - security monitoring environment used for log analysis, detection, and defensive security practice

### Networking

- Host-only network configured for isolated communication between lab machines
- NAT adapters used when systems require internet access for updates or software installation
- Lab traffic remains separated from my personal network

## Lab Architecture

```text
                VirtualBox Host
                       |
               Host-Only Network
                       |
        --------------------------------
        |              |               |
     Kali Linux    Ubuntu-SOC    Ubuntu-Target
      Red Team      Blue Team     Lab Target
```

This three-machine design allows me to simulate security scenarios by generating activity from Kali, monitoring events through the SOC environment, and analyzing activity on the target system.

## Documentation

Detailed documentation for this home lab:

- [Lab Setup](documents/lab-setup.md)  
  - Virtual machine configuration
  - Network design
  - Three-VM architecture
  - Lab evolution

- [Linux Basics](documents/linux-basics.md)  
  - Linux command-line fundamentals
  - Kali Linux and Ubuntu exploration
  - Initial Linux exercises

- [Current Skills](documents/current-skills.md)  
  - Technical skills currently being developed
  - Hands-on experience gained through lab practice

- [Lessons Learned](documents/lessons-learned.md)  
  - Troubleshooting experiences
  - Challenges encountered
  - Improvements made to the lab environment

## Current Learning Activities

- Cybersecurity coursework through the EFSC BAS Cybersecurity program
- Hack The Box practice
- TryHackMe exercises
- Linux command-line fundamentals
- Networking fundamentals
- Virtual machine administration

## Skills Demonstrated

- VirtualBox virtualization and lab management
- Kali Linux and Ubuntu administration
- Host-only network configuration
- Basic Linux command-line usage
- IP addressing and network configuration
- Cybersecurity lab documentation
- Security-focused troubleshooting

## Future Additions

- Deploy SIEM tools for centralized log collection and analysis
- Perform vulnerability scanning and assessment exercises
- Practice attack-and-defense scenarios between Kali and target systems
- Analyze security events and create detection documentation
- Expand into digital forensics exercises
- Continue documenting security tools and techniques
