# Lab 05: Adding a Host-Only Adapter to Kali

## Setup
- Adapter 1: NAT (internet access), address 10.0.2.15
- Adapter 2: Host-only (private lab network)

## Addresses (lab-only, private)
- Kali eth1: [your address]
- Windows host-only adapter: [your address]

## Tests
- ping google.com from Kali: worked, 0% packet loss
- ping from Kali to Windows host-only address: [worked / failed]

## What I learned
- One VM can have several network adapters.
- NAT gives internet access while hiding the VM.
- Host-only creates a private network between the laptop and its VMs.
- Ping is the first tool for testing whether two devices can reach each other.
