# Site-to-Site-VPN

## Author

- Full Name: Karam Aboul-Hosn

## Overview

The goal of this project is to understand how to implement a site-to-site IPsec VPN on a Cisco firewall. A site-to-site VPN ensures the confidentiality and integrity of data remain intact when connecting two sites over the internet. The components incorporated include two Cisco ASA Firewalls from the 5500-X series.

This particular implementation uses Diffie-Helman for secure key exchange, 3DES encryption to provide confidentiality, and SHA-HMAC hashing to provide integrity and authentication.

This repository contains all of the files and documentation for this design and implementation. 

Under the `docs/` folder, you will find a `.pdf` file containing addressing tables for this particular network design.

## How To Open The Project

Under the `packet.tracer/` folder, find and download the `.pkt` file and open it using Cisco Packet Tracer version 9.0.0.

## Configuration and Verification Files

Under the `configs/` folder, you will find `.txt` files where I have included the configuration IOS commands specific to each step taken during the project implementation. 

Note that all of the devices in the `.pkt` file are *already* configured properly.

## Network Topology

Under the `images/` folder, you will find a `.png` file containing the network topology diagram.

## Exceptions

It is understood that when it comes to setting up a site-to-site IPsec VPN, best-practice in a production environment would likely include IKEv2, AES-256, SHA-256, and DH group 14/90/20. A legacy implementation is functional for lab work here.
