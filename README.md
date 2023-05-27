# Portable Minecraft BDS
A short guide on how to create a slim portable virtual environment to host a MC BDS anywhere with automatic backup (*GDrive*).

### DISCLAIMER
This repo is for the sake of education mainly.
Will probably make a dockerfile to fully create the env. when I have time. Happy Mining.

**Table of Contents**

[TOCM]

[TOC]

## Tools Utilized
 - [Alpine Linux](https://alpinelinux.org/downloads/)
 - Docker
 - [Docker Minecraft BDS by itzg](https://github.com/itzg/docker-minecraft-bedrock-server)
 - [ZeroTier Docker](https://github.com/zyclonite/zerotier-docker)
 - Cron (for scheduled backup run)
 - Local.d
 - [Google Drive CLI](https://github.com/glotlabs/gdrive)
 - Your favorite Hypervisor or native machine

## Work Diagram
![Diagram](/img/diagram_2.png)
