# Nyvia Projects

An assortment of custom software and IT projects, including tailored applications, educational content, and a network lab with specified functionalities.

### Nyvia Projects(LAB)

The project encompasses a sophisticated home network infrastructure integrated with DNS servers, cloud storage, VPN services, password management system, an IDE, as well as communication and search capabilities. Lab facilitates local deployment and testing of all tailored applications and open-source initiatives. Key services are deployed across renowned cloud platforms like AWS and DigitalOcean, secured by VPN tunnels.

- Hardware used: [Protectli Vault](https://protectli.com/), Mini PCs, SSDs, [Raspberry Pi](https://www.raspberrypi.com/), Network Switch, Access Point
- Software used: [pfSense](https://www.pfsense.org/), [Ubuntu Server](https://ubuntu.com/download/server), [Docker](https://ubuntu.com/download/server), [WireGuard](https://www.wireguard.com/), [NGINX Reverse Proxy](https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/)
- Services: [Portainer](https://www.portainer.io/), [BitWarden](https://bitwarden.com/), [Pi-Hole](https://pi-hole.net/), [Orbital-Sync](https://github.com/mattwebbio/orbital-sync), [GitLab](https://about.gitlab.com/install/), [TrueNAS](https://www.truenas.com/), [VSCode-Server](https://github.com/coder/code-server), [NextCloud](https://nextcloud.com/install/), [Brave-Sync](https://github.com/brave/go-sync), [Apache Guacamole](https://guacamole.apache.org/)

#### If you'd like to chat or collaborate, please reach me at [friend@nyvia-projects.com](mailto:friend@nyvia-projects.com)

## Active Projects

Projects can be tracked in [here](https://github.com/users/nyvia-projects/projects/1).

#### **Building and shining through [nyvia.io](https://nyvia.io)**

- Personal portfolio
- Freelance IT and Software services advertisement
- Initially built with React.js, but now Next.js 13

#### **Sharing knowledge through [nyvia-academy](https://github.com/nyvia-projects/nyvia-academy)**

- Public repository with personal notes on various CS and IT topics
- Taken throughout obtaining my bachelors and coding journey since 2015
- Markdown on GitHub for now, but soon a website

#### **Bringing [Techmetrica](https://techmetrica.org) to life**

- Innovative research platform for CSU, Northridge
- Deployed in the cloud([DigitalOcean](https://www.digitalocean.com/))
- [(more here)](https://github.com/techmetrica)

#### **Developing [nyps](https://github.com/nyvia-projects/nyps-v0) to share**

- CLI package manager and utility tool built with Go
- Mastering wonderful golang

## News and Updates

Date: 09/01/23

I have launched a new project, [nyvia-academy](https://github.com/nyvia-projects/nyvia-academy).

I've been gathering valuable coding resources and notes since 2015 and plan to curate them into a repository for public access, with potential expansion into video lessons, while aiming to create an accessible webpage using tools like **[Nextra.js](https://nextra.site/)** or **[Obsidian Vault](https://obsidian.md/)**.

Date: 09/24/23

One of my crucial servers experienced an SSD failure, resulting in the loss of significant data. I am in the process of rebuilding and taking measures to prevent such an incident in the future by transitioning all configurations to a separate NAS.

## Notes and My Honest Opinions

#### [Docker](https://www.docker.com/)

- Opinion: Best technology of the decade.
- Reasoning: Enables efficient, scalable, and secure application deployment.

#### [Ansible](https://www.ansible.com/)

- Opinion: Essential for task automation.
- Usage: Helps manage my home lab by automating tasks.

#### [Ubuntu 22.04](https://releases.ubuntu.com/jammy/)

- Opinion: An amazing Linux distributive for developers.
- Benefits: Extensive community and documentation support.

#### [Java](https://java.com)

- Opinion: Great for robust enterprise and cross-platform applications.
- Benefits: Provides platform independence, strong memory management, and high performance for large-scale applications.

#### [TypeScript](https://typescriptlang.org/)

- Opinion: My new favorite language!
- Benefit: Ensures a less painful and fast development experience.

#### [Nextjs 13](https://nextjs.org/)

- Opinion: Amazing full-stack web application framework.

#### [Bun.sh](https://bun.sh)

- Opinion: Super fast Javascript Runtime and package manager!
- Impact: Ensures rapid development.

#### [Turborepo](https://turbo.build/)

- Purpose: Tool for managing multiple projects from a single codebase.
- Usage: Helps manage and share code to multiple projects from single repository.

## More Lab Info

#### Network Topology coming soon

### Servers currently being build

**Hypervisor host**

Pretty capable server that I plan to virtualize with [proxmox](https://www.proxmox.com/en/) hypervisor and
host [FileCloud](https://www.filecloud.com/) on my zfs NAS built on [TrueNAS](https://www.truenas.com/), as well as Home Media Server([Jellyfin](https://github.com/jellyfin/jellyfin)).

Hardware:

- Ryzen 5600G on B550 motherboard with 16GB RAM
- 8 TB of SSD storage

**[PiKVM](https://pikvm.org/)** - KVM over IP solution

### Services currently being worked on

- Making NextCloud, vscode-server public facing along with one of my Pi-hole DNS servers
- Hosting guacamole on either AWS or DigitalOcean to allow VNC and RDP to my servers
