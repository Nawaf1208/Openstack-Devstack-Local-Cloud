# OpenStack DevStack – Local Cloud Simulation

![OpenStack](https://img.shields.io/badge/OpenStack-ED1944?style=for-the-badge&logo=openstack&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=for-the-badge&logo=virtualbox&logoColor=white)

A local cloud infrastructure project built using **OpenStack DevStack** to simulate real-world **Infrastructure-as-a-Service (IaaS)** concepts such as compute, networking, storage, and identity management.

## Features
- Deploy a complete OpenStack cloud using DevStack
- Provision virtual machines using Nova
- Configure private networks, routers, floating IPs, and security groups with Neutron
- Manage images using Glance
- Attach persistent block storage volumes via Cinder
- Access and manage cloud resources through the Horizon Dashboard

## Usage
```bash
git clone https://opendev.org/openstack/devstack
cd devstack
cp samples/local.conf .
./stack.sh
