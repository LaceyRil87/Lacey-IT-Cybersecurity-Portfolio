# Kali Linux Network Troubleshooting Lab

## Overview
This lab focused on configuring and troubleshooting network connectivity within a Kali Linux virtual machine.

## Objective
The goal of this lab was to ensure proper network configuration and connectivity between virtual machines in a controlled lab environment.

## Tools Used
- Kali Linux virtual machine
- VMware Workstation
- Terminal
- Nano text editor
- Networking service commands

## Issues Encountered
Initially, the virtual machine did not have proper network connectivity. IP addresses were not assigning as expected, and communication between machines was inconsistent.

## Troubleshooting Process
I began by checking the current network configuration and verifying which interfaces were active. I edited the network interfaces configuration file using nano and ensured both interfaces were set to use DHCP. After saving the changes, I restarted the networking service and verified IP address assignment. Connectivity was tested to confirm the issue was resolved.

## Resolution
After correcting the network interface configuration and restarting the networking service, the system successfully obtained an IP address and network connectivity was restored.

## What I Learned
This lab reinforced the importance of understanding network interface configuration and methodical troubleshooting when resolving connectivity issues in Linux environments.
