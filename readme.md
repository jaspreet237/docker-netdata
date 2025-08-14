## Monitor System Resources Using Netdata

## Objective
Install and run Netdata using Docker to monitor system and application performance in real-time.

## Tools
- **Netdata** (open-source monitoring tool)
- **Docker**

## Steps
1. **Run Netdata**
   ```bash
   docker run -d --name=netdata \
     -p 19999:19999 \
     --cap-add SYS_PTRACE \
     --security-opt apparmor=unconfined \
     netdata/netdata
