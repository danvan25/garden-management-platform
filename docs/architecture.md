# Initial Architecture

## Overview

The Garden Management Platform is planned as a Raspberry Pi based home lab infrastructure for managing and automating a hobby garden.

The first version of the system will focus on secure remote access, basic service hosting, monitoring and future IoT integration.

---

## High-level Architecture

```text
Internet
   |
WireGuard VPN
   |
Home Network
   |
Raspberry Pi Server
   |
   +-- Docker
   |     |
   |     +-- Web Application
   |     +-- Database
   |     +-- Monitoring
   |
   +-- NAS / Storage
   |
   +-- Future IoT Communication
          |
          +-- Pump Control
          +-- Lighting Control
          +-- Weather Station
          +-- Security Cameras