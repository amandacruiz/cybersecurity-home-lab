# Cybersecurity Home Lab

Part of my cybersecurity portfolio:  
[amanda-c-ruiz portfolio](https://github.com/amandacruiz/amanda-c-ruiz)

## Overview

I built a VirtualBox-based cybersecurity home lab to practice offensive security, system administration, and defensive monitoring in an isolated environment.

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

## Current Learning Activities

- Hack The Box
- TryHackMe
- Cybersecurity coursework
- Linux fundamentals
- Networking fundamentals

## Future Additions

- Deploy SIEM tools for centralized log collection and analysis
- Perform vulnerability scanning and assessment exercises
- Practice attack-and-defense scenarios between Kali and target systems
- Analyze security events and create detection documentation
- Expand into digital forensics exercises
- Continue documenting security tools and techniques
