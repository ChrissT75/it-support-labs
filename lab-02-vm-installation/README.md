# Lab 02 – Virtual Machine Installation

## Objective
Install and configure a virtual machine (VM) to create a safe environment for cybersecurity practice on macOS.

## Host Machine
- MacBook (Apple Silicon)
- macOS version: [your macOS version]

## Hypervisor
- UTM installed
- Version: [UTM version]

## Guest OS
- Kali Linux
- Version: [Kali version]
- Architecture: ARM64

## Installation Steps
1. Open UTM on macOS and create a new VM.
2. Select architecture: ARM64.
3. Choose Kali Linux ISO as the installation media.
4. Allocate RAM, CPU, and storage for the VM.
5. Start the VM and follow the Kali installation wizard.
6. Enable SSH for remote access.
7. Verify the VM is running and connected to the network.

## Verification
- Check system info in Kali: `uname -a`
- Check network interfaces: `ip a`
- Test SSH access: `ssh username@vm-ip`

## Outcome
Kali Linux VM installed successfully on Mac, ready for hands-on labs: Linux commands, networking, users, and security exercises.


