
# Netdata Monitoring - TASK 7

## Objective
Install Netdata and visualize system and application performance metrics in real-time using Docker.

## Tools Used
- Netdata (Dockerized)
- Docker

## Setup Instructions

1. Run Netdata in Docker:
   ```bash
   docker run -d --name=netdata -p 19999:19999 netdata/netdata
