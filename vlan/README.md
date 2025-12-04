# VLAN Configuration Lab

## Overview
This lab demonstrates how to create VLANs, assign VLAN names, and configure switchports in access mode. The goal is to segment broadcast domains based on department requirements.

## Tasks
1. Create the following VLANs:
   - VLAN 10: sales  
   - VLAN 20: mrkt  
   - VLAN 30: finance  
   - VLAN 40: IT  

2. Assign IP ranges:
   - VLAN 10 → 192.168.10.0/27  
   - VLAN 20 → 192.168.20.0/26  
   - VLAN 30 → 192.168.30.0/27  
   - VLAN 40 → 192.168.40.0/28  

3. Assign VLANs to switch interfaces as per the topology.
4. Configure PCs with the correct IP addresses based on their VLAN.

## Files
- `configuration.txt` – IOS configuration
- `verification.txt` – Show commands for validation
