# Firewall

This directory contains scripts and configuration for setting up `ufw` (Uncomplicated Firewall) on `web-01`.

## 0-block_all_incoming_traffic_but

This file lists the `ufw` commands used to block all incoming traffic on `web-01`, except for the following TCP ports:

- `22` (SSH)
- `80` (HTTP)
- `443` (HTTPS)
