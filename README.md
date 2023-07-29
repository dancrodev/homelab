# Project XenLab

[![license](https://img.shields.io/github/license/khuedoan/homelab?style=flat-square&logo=gnu&logoColor=white)](https://www.gnu.org/licenses/gpl-3.0.html)
[![stars](https://img.shields.io/github/stars/dancrodev/homelab?logo=github&logoColor=white&color=gold&style=flat-square)](https://github.com/dancrodev/homelab)

### Overview

Project Status: **Planning**

This repo will include my current Homelab stack, resources, provisioning scripts, etc.
Please view the `CHANGELOG.md` file for more information on changes to the project.

> **What is a Homelab?**
>
> Homelab is a laboratory at home where you can self-host, experiment with new technologies, practice for certifications, and so on. For more information about homelab in general, see the [r/homelab introduction](https://www.reddit.com/r/homelab/wiki/introduction).

I want to thank [@khuedoan](https://github.com/khuedoan) for inspiring me to present my homelab progress and journey pubilcally. He has an amazing repo of his setup/progress which can be found [here](https://github.com/khuedoan/homelab).

### Hardware

![setup](https://user-images.githubusercontent.com/2058413/257009553-1d8cb00e-daba-4811-8a7c-ddade5d381d7.jpg)

- Omnimount Design 27U Network Cabinet
- 3 × Dell SFF `OptiPlex 7040`:
  - CPU: `Intel Quad Core i7-6700 @ 4.0GHz`
  - RAM: `16GB`
  - SSD: `512GB`
- 1 × Raspberry `Pi 4 Model B`
- 1 × Raspberry `Pi 2 Model B`
- Apple Mac Mini `Early 2009`
- Ubiquiti `EdgeRouter X`
  - Ports: `5`
  - Speed: `1000Mbps`
- MokerLink 24 Port PoE Gigabit Managed Switch:
  - Ports: `24 + 4 GE Uplink + 4 Combo SFP`
  - Speed: `1000Mbps`
- Synology DS1515+:
  - CPU: `Intel Atom C2538 @ 2.4GHz`
  - RAM: `8GB`
  - HDD: `30TB` (20.9TB Usable)

### Basic Topology

![topo-v1](https://user-images.githubusercontent.com/2058413/257009377-67ae1e33-06e0-4547-aa19-cc537a5303d9.png)

### Current Tech Stack

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/2678585?s=200&v=4"></td>
        <td><a href="https://www.proxmox.com">Proxmox</a></td>
        <td>Server Virtualization Platform (Debian)</td>
    </tr>
    
</table>

### Planned Tech Stack

<table>
    <tr>
        <td><img width="32" src="https://simpleicons.org/icons/ansible.svg"></td>
        <td><a href="https://www.ansible.com">Ansible</a></td>
        <td>Automated bare metal/VM  provisioning and configuration</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/9289019?s=200&v=4"></td>
        <td><a href="https://letsencrypt.org/">Let's Encrypt</a></td>
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
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/kubernetes/icon/color/kubernetes-icon-color.svg"></td>
        <td><a href="https://kubernetes.io">Kubernetes</a></td>
        <td>Container Orchestration System</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/1412239?s=200&v=4"></td>
        <td><a href="https://www.nginx.com">NGINX</a></td>
        <td>Reverse Proxy / HTTP Sever</td>
    </tr>
    <tr>
        <td><img width="32" src="https://simpleicons.org/icons/vault.svg"></td>
        <td><a href="https://www.vaultproject.io">Vault</a></td>
        <td>Secrets and encryption management system</td>
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
    <tr>
        <td><img width="32" src="https://github.com/dancrodev/homelab/assets/2058413/e7d92189-1116-472c-827e-bff10be52cef"></td>
        <td><a href="https://www.scrypted.app/">Scrypted</a></td>
        <td>Home Video Integration and Automation Platform.</td>
    </tr>
     <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/4604537?s=200&v=4"></td>
        <td><a href="https://ubuntu.com">Ubuntu</a></td>
        <td>Debian based Linux Distro</td>
    </tr>
</table>

### Goals / To-Do List

- [x] Move components to server rack
- [x] Acquire network hardware for VLAN / PXE support
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

If I missed you from this list, please reach out so I can correct it.
