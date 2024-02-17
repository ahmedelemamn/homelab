# Homelab

My Homelab Services/tools implementaion that is hosted behind traefik
full docker compose files ( needs some editing in some certain cases such as DB credentials )

My Gear:
- Dell T7810 Chassis > Proxmox Node 1 - 44/88 Cores/Threads - 256GB RAM - 5TB NVME - 12TB HDD - 240GB SSD
- HP Z420 > Proxmox Node 2 - 8/16 Cores/Threads - 56GB RAM - 8TB HDD - 500GB SSD
- 1 x Mikrotik access switch > CRS305-1G-4S+
- 1 x QNAP Access Switch > QSW-M408S
- 1 x Mikrotik Core Switch > CRS326-24G-2S+
- 1 x pFsense FW 

Services & Tools:
| Sevice/Tool      | Type                                                       |
| ---------------- | ---------------------------------------------------------- |
| Traefik          | Container                                                  |
| Portainer        | Container                                                  |
| Graphana         | Container                                                  |
| Promethues       | Container                                                  |
| Node Exporter    | Container                                                  |
| LOKI             | Container                                                  |
| Promtail         | Container                                                  |
| influx DB 2      | Container                                                  |
| influx DB 1.8    | Container                                                  |
| checkmk          | Container                                                  |
| uptime kuma      | Container                                                  |
| speedtest tracke | Container                                                  |
| Restyaboared     | Container                                                  |
| Postgres DB      | Container                                                  |
| Heimdall         | Container                                                  |
| fileexplorer     | Container                                                  |
| Truenas Scale    | 2 x standalone VMs - Replicated                            |
| PLEX             | 2 x containers on trunas scale                             |
| Homebridge       | 1 x Standalone VM                                          |
| PI-HOLE          | 2 x Standalone VMs - 1 Main and 1 BKP ( using keepalived ) |
| EVE-NG           | 1 x Standalone VM                                          |
