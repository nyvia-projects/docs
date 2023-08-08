# Nyvia Projects
The project encompasses a sophisticated home network infrastructure integrated with DNS servers, cloud storage, VPN services, password management system, an IDE, as well as communication and search capabilities. Lab facilitates local deployment and testing of all tailored applications and open-source initiatives. Key services are deployed across renowned cloud platforms like AWS and DigitalOcean, secured by VPN tunnels.

- Hardware used: Protectli Vault, Mini PCs, SSDs, Raspberry Pi, Network Switch, Access Point
- Software used: pfSense, Ubuntu Server, Docker, WireGuard, NGINX Reverse Proxy
- Services: Portainer, BitWarden, Pi-Hole, Orbital-Sync, GitLab, TrueNAS, VSCode-Server, NextCloud, Brave-Sync, Guacamole

### Network Topology and Service details will be updated soon

## Servers currently being built
### Hypervisor host
Pretty capable server that I would like to virtualize with proxmox hypervisor and host FileCloud on my zfs NAS built on TrueNAS, as well as Home Media Server(Jellyfin).

Hardware I am working with
- Ryzen 5600G on B550 motherboard with 16GB RAM
- 4x 2TB SATA SSDs 

### PiKVM 
KVM over IP solution

## Services currently being worked on
- Making NextCloud, vscode-server public facing along with one of my Pi-hole DNS servers
- Hosting guacamole on either AWS or DigitalOcean to allow VNC and RDP to my servers

## Other
- **Developing an securing [nyvia.io](https://nyvia.io)**