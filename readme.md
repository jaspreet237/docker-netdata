# Monitor System Resources Using Netdata

## Objective
Install and run Netdata using Docker to monitor system and application performance in real-time.

## Tools
- **Netdata** (open-source monitoring tool)
- **Docker**

## Steps
1. **Run Netdata**
 
docker run -d --name=netdata -p 19999:19999 netdata/netdata
   
Access Dashboard

Open http://localhost:19999 in browser.

Monitor Metrics

CPU, memory, disk usage

Network activity

Docker container metrics

Dashboard - Add charts on Dashboard

Check Logs

docker exec -it netdata bash
cd /var/log/netdata

## Screenshots

<img width="744" height="88" alt="image" src="https://github.com/user-attachments/assets/51051b84-004c-4816-974b-fd32c6233624" />

<img width="631" height="263" alt="image" src="https://github.com/user-attachments/assets/513df05f-c1d5-46d8-b3e8-1ab7bd071907" />

<img width="1361" height="630" alt="image" src="https://github.com/user-attachments/assets/1f5facc8-a4a8-4058-8be1-48b693b27e10" />

<img width="1260" height="404" alt="image" src="https://github.com/user-attachments/assets/8e78de43-18ca-48fb-bf7d-e70d694695c0" />




