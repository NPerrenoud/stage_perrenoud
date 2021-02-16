##Telco Cloud: Connectivity, VLAN and IP Addresses 

VLAN : all the VLAN can be brought to the serveur

**Data Plane**

Base on two physical interfaces 10Gbit/s, dual attachement toward the two infra switch, 

Bonded  in mode 1: "Active Passiv" https://doc.ubuntu-fr.org/bonding

Ports x and y of the Machines,

Q. How is spanning trees managed on the nodes

- IP: 160.98.36.0/24 -> VLAN 436 -> Interne OpenStack + API Network (Horizon)
- IP: 160.98.37.0/24 -> VLAN 437 -> Interne CEE
- IP: 160.98.50.0/24 -> VLAN 450  -> DMZ OpenStack
- IP: 160.98.51.0/24 -> VLAN 451 -> DMZ CEE
- IP : 10.40.0.0 / 16 -> VLAN 1140 -> Private  Openstack Network 



**Control Plane**

Dedicated Interface for each Management pour chaque Management

IP: 160.98.45.0/23 -> VLAN 45 -> Management, interface **ILO** ( HPE Integrated Lights-Out de HP, host BIOS access, Maas access to the basic physical fonction : 

- Power on / Power off
- Setup of the PXE Interfaces
- BIOS Access

IP : 10.20.20.0/ 24 -> VLAN 1120 -> réseau PXE (**P**re-boot e**X**ecution **E**nvironment) MaaS Deployement Interfaces, , Interface has to be declared as PXE , from LILO. This VLAn is forwarde to teh V



**Maas Deployment Process**

https://docs.openstack.org/project-deploy-guide/charm-deployment-guide/latest/install-openstack.html



Maas , Juju and Juju GUI Instance running in the WMware Cluster, via VLAN 1120,

