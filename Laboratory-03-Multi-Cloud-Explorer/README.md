# Linux Environment Investigation

## Operating System

The Linux environment is running *Ubuntu 24.04.4 LTS (Noble Numbat)*.

## CPU

The system uses an *Intel Xeon E312xx (Sandy Bridge, IBRS update)* processor.

- Architecture: x86_64
- CPU(s): 1
- Core(s) per socket: 1
- CPU frequency: 2.0 GHz
- Virtualization: KVM

## Memory

The system has *1.9 GiB of total memory*.

- Total: 1.9 GiB
- Used: 412 MiB
- Free: 872 MiB
- Available: 1.5 GiB
- Swap: 1.0 GiB

## Disk Space

The main filesystem is /dev/vda1.

- Total: 19 GB
- Used: 5.4 GB
- Available: 13 GB
- Usage: 30%

## Cloud Services That Could Host This Linux Server

| Cloud Provider | Service | Purpose |
|---|---|---|
| AWS | Amazon EC2 | Amazon EC2 can host Ubuntu Linux as a virtual machine with configurable computing resources. |
| Microsoft Azure | Azure Virtual Machines | Azure Virtual Machines can host Ubuntu Linux servers with configurable CPU, memory, and storage. |
| Google Cloud | Compute Engine | Compute Engine can host Ubuntu Linux virtual machines with configurable CPU, memory, and storage. |

## Linux Environment Summary

The investigation used a KillerCoda Ubuntu Linux environment to examine the operating system, CPU, memory, and disk resources. The environment runs Ubuntu 24.04.4 LTS with an x86_64 Intel Xeon processor, 1.9 GiB of memory, and a 19 GB main filesystem.

The Linux server could be hosted on any of the three major cloud platforms. AWS can use Amazon EC2, Microsoft Azure can use Azure Virtual Machines, and Google Cloud can use Compute Engine. These services allow organizations to deploy and manage Linux-based virtual machines in the cloud.

## Investigation Commands

The following Linux commands were used during the investigation:

```bash
cat /etc/os-release
lscpu
free -h
df -h
