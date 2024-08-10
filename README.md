# Project XenLab

[![license](https://img.shields.io/github/license/khuedoan/homelab?style=flat-square&logo=gnu&logoColor=white)](https://www.gnu.org/licenses/gpl-3.0.html)
[![stars](https://img.shields.io/github/stars/dancrodev/homelab?logo=github&logoColor=white&color=gold&style=flat-square)](https://github.com/dancrodev/homelab)

### Overview

Project Status: **In Progress**

This repo will include my current Homelab stack, resources, provisioning scripts, etc.
Please view the `CHANGELOG.md` file for more information on changes to the project.

> **What is a Homelab?**
>
> Homelab is a laboratory at home where you can self-host, experiment with new technologies, practice for certifications, and so on. For more information about homelab in general, see the [r/homelab introduction](https://www.reddit.com/r/homelab/wiki/introduction).

I want to thank [@khuedoan](https://github.com/khuedoan) for inspiring me to present my homelab progress and journey pubilcally. He has an amazing repo of his setup/progress which can be found [here](https://github.com/khuedoan/homelab).

### Hardware

![setup](https://github.com/user-attachments/assets/d4ad2afd-b896-4e8a-83d6-1426497ceed8)

- Omnimount Design 27U Network Cabinet
- 3 × Dell SFF `OptiPlex 7040`:
  - CPU: `Intel Quad Core i7-6700 @ 4.0GHz`
  - RAM: `16GB`
  - SSD: `512GB`
- 1 × Rasbperry `Pi 5`
- 3 × Raspberry `Pi 4 Model B`
- Apple `Mac Mini M2`
- Ubiquiti `Dream Machine Special Edition`
  - Ports: `(8) GbE w/ PoE (2 w/ PoE+), (2) 10G SFP+, (1) 2.5 GbE WAN Port` 
- Ubiquiti `Switch Pro 24`
  - Ports: `24x GbE RJ45, 2x 10G SFP+`
- Ubiquiti `UniFi Cable Internet`
  - Ports: `(1) DOCSIS 3.1, (1) 2.5 GbE`
- Synology DS1515+:
  - CPU: `Intel Atom C2538 @ 2.4GHz`
  - RAM: `8GB`
  - HDD: `30TB` (20.9TB Usable)
- Tripp Lite `SMART1500LCD Smart Battery Backup`

### Basic Topology

![topo-v1](https://github.com/dancrodev/homelab/assets/2058413/448de288-9811-4736-a1e3-87d58a74aebc)

### Current Tech Stack

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/4604537?s=200&v=4"></td>
        <td><a href="https://ubuntu.com">Ubuntu</a></td>
        <td>Debian based Linux Distro</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/2678585?s=200&v=4"></td>
        <td><a href="https://www.proxmox.com">Proxmox</a></td>
        <td>Server Virtualization Platform (Debian)</td>
    </tr>
    <tr>
        <td><img width="32" src="https://github.com/dancrodev/homelab/assets/2058413/e7d92189-1116-472c-827e-bff10be52cef"></td>
        <td><a href="https://www.scrypted.app/">Scrypted</a></td>
        <td>Home Video Integration and Automation Platform.</td>
    </tr>
    
</table>

### Planned Tech Stack

<table>
    <tr>
        <td><img width="32" src="https://raw.githubusercontent.com/loganmarchione/homelab-svg-assets/main/assets/ansible-red.svg"></td>
        <td><a href="https://www.ansible.com">Ansible</a></td>
        <td>Automated bare metal/VM  provisioning and configuration</td>
    </tr>
    <tr>
        <td><img width="32" src="https://raw.githubusercontent.com/loganmarchione/homelab-svg-assets/main/assets/letsencrypt.svg"></td>
        <td><a href="https://letsencrypt.org/">Let's&nbsp;Encrypt</a></td>
        <td>Automated Open Certificates</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/314135?s=200&v=4"></td>
        <td><a href="https://www.cloudflare.com">Cloudflare</a></td>
        <td>DNS and Tunnel</td>
    </tr>
     <tr>
        <td><img width="32" src="https://grafana.com/static/img/menu/grafana2.svg"></td>
        <td><a href="https://grafana.com">Grafana</a></td>
        <td>Operational dashboards</td>
    </tr>
    <tr>
        <td><img width="32" src="https://raw.githubusercontent.com/loganmarchione/homelab-svg-assets/main/assets/kubernetes.svg"></td>
        <td><a href="https://kubernetes.io">Kubernetes</a></td>
        <td>Container Orchestration System</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/1412239?s=200&v=4"></td>
        <td><a href="https://www.nginx.com">NGINX</a></td>
        <td>Reverse Proxy / HTTP Sever</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/107880645?s=200&v=4"></td>
        <td><a href="https://infisical.com/">Infisical</a></td>
        <td>Open Source Secrets management system</td>
    </tr>
    <tr>
        <td><img width="32" src="https://github.com/dancrodev/homelab/assets/2058413/d14a5113-bee4-459e-9eb5-299ac2cab111"></td>
        <td><a href="https://www.terraform.io/">Terraform</a></td>
        <td>Automation / IaC (Infrastructure as code)</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/22105643?s=200&v=4"></td>
        <td><a href="https://www.gitlab.com">Gitlab</a></td>
        <td>Git Repos / DevOps Toolkit</td>
    </tr>
    <tr>
        <td><img width="32" src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png"></td>
        <td><a href="https://www.docker.com">Docker</a></td>
        <td>Build/Run/Deploy Containers</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/18517161?s=200&v=4"></td>
        <td><a href="https://www.pivpn.io/">PiVPN</a></td>
        <td>Raspbery Pi-based VPN Server (Wireguard)</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/22225832?s=200&v=4"></td>
        <td><a href="https://www.portainer.io/">Portainer</a></td>
        <td>Container Management</td>
    </tr>
</table>

### Goals / To-Do List

- [x] Move components to server rack
- [x] Acquire network hardware for VLAN / PXE support
- [x] Upgrade to Unifi Router/Hardware Stack
- [ ] Selfhost Gitlab & develop CI/CD pipelines
- [ ] Automated MaaS / PXE BARE METAL PROVISION
- [ ] Automated Terraform VM provisioning
- [ ] Automated Ansible/Packer Configuration Management
- [ ] Kubernetes Installation & Management
- [ ] Develop Custom 'Control Plane' to manage homelab
- [ ] Self Hosted Gitlabs, GitLab/Github Runners & CI/CD Pipelines
- [ ] Private Container Repo
- [ ] Utilize Synology NAS (implement automated off-site backups)
- [ ] Dashboards, consolidated logging, monitoring and alerts
- [ ] Expose VM to the internet securely (web app)
- [ ] Utilize RaspPi Pi for piVPN
- [ ] Utilize RaspPi for piKVM
- [ ] Establish Automated Updates w/ alerts
- [ ] Establish Hybrid Cloud (On-Prim <-> Cloud) Architecture
- [x] Create Github Pages hosted MkDocs site for documentation / tutorials
- [x] Upgrade small Switchs to Rackmount Switch
- [ ] Cable Management

### License

Distributed under the GPLv3 License.
See `LICENSE.md` file for more information.

### Acknowledgements

Here is a list of some of the great people who have directly or indirectly contributed to this project:

- ![](https://github.com/khuedoan.png?size=24) [@khuedoan](https://github.com/khuedoan)
- ![](https://github.com//techno-tim.png?size=24) [@techno-tim](https://github.com//techno-tim)
- ![](https://github.com//loganmarchione.png?size=24) [@loganmarchione](https://github.com/loganmarchione/homelab-svg-assets)


If I missed you from this list, please reach out so I can correct it.
