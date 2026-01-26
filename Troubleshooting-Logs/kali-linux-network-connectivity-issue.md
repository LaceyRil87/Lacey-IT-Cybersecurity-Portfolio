# Kali Linux Network Connectivity Issue

## Problem
Kali Linux VM did not have network connectivity and was not receiving an IP address as expected.

## Symptoms
- No or incorrect IP address assignment
- Unable to reach other systems in the lab environment
- Network tests failing

## Environment
- Kali Linux virtual machine
- VMware Workstation
- Dual network interfaces
- DHCP configuration

## Troubleshooting Steps
- Checked active interfaces and current IP address status
- Updated the network interfaces configuration to ensure DHCP was enabled for the correct interfaces
- Restarted the networking service
- Verified IP address assignment after restart
- Re tested connectivity

## Resolution
After correcting the interface configuration and restarting networking, the VM successfully obtained an IP address and connectivity was restored.

## Lessons Learned
A structured approach helps prevent missing simple configuration issues. Verifying interface settings and confirming IP assignment after changes saves time.
