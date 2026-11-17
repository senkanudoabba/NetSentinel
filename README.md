# NetSentinel

NetSentinel is a modular network security monitoring platform
designed to collect, analyse and correlate network traffic and
security events in a controlled lab environment.

## Objectives

- Capture and inspect network traffic.
- Detect suspicious network activity using Suricata.
- Analyse packet data using TShark.
- Process and correlate security events with Python.
- Generate useful security reports and alerts.

## Architecture

Network Traffic
      |
      v
Packet Capture and Analysis
      |
      +---- TShark
      |
      +---- Suricata
      |
      v
Python Processing Engine
      |
      v
Security Reports and Dashboard

## Technology Stack

- Python 3
- Suricata
- TShark / Wireshark
- Docker
- Git

## Project Structure

- configs/  - Application and tool configurations
- docs/     - Technical documentation
- logs/     - Generated security logs
- pcaps/    - Packet capture files
- scripts/  - Utility and automation scripts

## Development Roadmap

1. Development environment and project foundation.
2. Network traffic capture and inspection.
3. Suricata integration and alert collection.
4. Python log processing and event correlation.
5. Security reporting and dashboard.
6. Testing and documentation.

## Project Status

Under active development.

## Disclaimer

NetSentinel is intended for defensive security research,
education and monitoring in authorised environments only.
