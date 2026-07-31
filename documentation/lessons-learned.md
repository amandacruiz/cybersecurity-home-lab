# Lessons Learned

This document tracks important lessons, observations, challenges, and improvements from my cybersecurity home lab practice.

## Linux

### Case Sensitivity and Spacing Matter

While practicing Linux commands, I learned that Linux is case-sensitive and that spacing matters when entering commands.

For example:

- `Documents` and `documents` are treated as different names.
- Commands entered with incorrect spacing may not execute as expected.

This was a reminder that accuracy and attention to detail are important when working in a command-line environment. Small mistakes can affect the outcome of a command and require careful troubleshooting.

### Key Takeaway

Linux requires precision. Developing good command-line habits early will help when working with security tools, system administration tasks, and future automation.

## Virtualization

### Planning Resources Before Building the Lab Matters

When creating my home lab, I learned that virtual machines require careful planning of available resources such as RAM, storage, and CPU allocation.

Running multiple virtual machines on a laptop requires balancing performance needs with the limitations of the host system.

### Key Takeaway

Before expanding a lab environment, it is important to consider available hardware resources and design the environment around those limitations.

## Networking

### Understanding Isolation Through Host-Only Networking

When configuring my VirtualBox lab, I learned the importance of separating cybersecurity practice environments from my personal network.

Using a Host-Only Network allows virtual machines to communicate with each other while keeping the lab isolated.

### Key Takeaway

Network design is an important part of cybersecurity. Understanding how systems communicate and how to isolate environments helps create safer testing environments.

## Documentation

### Organization Makes Troubleshooting Easier

As the home lab expanded, I learned that keeping documentation, screenshots, and notes organized is important for tracking changes and troubleshooting issues.

Separating documentation, notes, and screenshots makes it easier to understand the current state of the lab and identify improvements.

### Key Takeaway

Clear documentation is a technical skill. Being able to explain what was built, why it was configured a certain way, and what was learned is valuable in cybersecurity roles.

## Overall Reflection

Building this home lab has shown me that cybersecurity requires more than learning individual tools. It requires understanding how systems are built, how they communicate, how problems are diagnosed, and how technical information is documented.

Each challenge has helped me improve my troubleshooting process and develop a stronger foundation for future cybersecurity projects.
