1.The most popular hypervisors for infrastructure virtualization:
VMware vSphere / ESXi.(The leader in the Tier-1 hypervisors is VMware with their vSphere/ESXi product – available in a free edition and 5 commercial editions. VMware led the market in developing innovative features such as memory overcommitment, vMotion, Storage vMotion, Fault Tolerance, and more. Previously, VMware called their free hypervisor “Free ESXi” as ESXi Server is what is loaded directly on the physical server. However, VMware calls the “suite” of features “vSphere”, available in various editions. Today, even the free hypervisor is called “The VMware vSphere Hypervisor“. While the free vSphere hypervisor does have a graphical interface (the vSphere Client) and memory over-commitment, it doesn’t offer features like vMotion, svMotion, high availability, or centralized management. The free version also has the limitation of supporting up to 32GB of RAM per physical server. The commercial versions of vSphere include features like:

Memory over commitment
High availability (called vSphere HA)
vMotion
Storage vMotion (svMotion)
vSphere Data Protection (for backup and recovery)
vSphere Replication
vShield Endpoint protection (the option to use agentless anti-virus solutions)
Hot add of memory and hot plug for CPU
Fault tolerance (FT) for availability
Distributed resource scheduler (DRS) for VM “load balancing” (effectively)
Distributed power management (DPM), consolidates VMs with vMotion and shuts down hosts to save power
Distributed virtual switch (dvSwitch)
Storage I/O control (SIOC) and network I/O control (NIOC)
Host profiles
Autodeploy
Storage distributed resource scheduler (SDRS)
Profile-driven storage
Single root I/O virtualization (SR-IOV)
Web-based management and new vCenter virtual appliance deployment
vCenter Single Sign On (SSO)
vCenter Operations Manager Foundation Edition
Optional features include Site Recovery Manager (SRM) for disaster recovery, vCenter Operations Manager Std/Adv, vCloud Director, vCloud Suite, VMware Horizon Suite, and more
Scale up to 512 VMs per host, up to 2048 vCPUs per host, up to 64 vCPUS and 1TB of vRAM per VM
)
####################################################################################
Microsoft Windows Server 2012 Hyper-V (or the free Hyper-V Server 2012).(Along with XenServer and vSphere (next on the list), Hyper-V is one of the top 3 Tier-1 hypervisors (frequently flip/flopping between 2nd and 3rd place with XenServer). First released with Windows Server, Hyper-V has now been greatly enhanced with Windows Server 2012 Hyper-V. Hyper-V is available in both a free edition (with no GUI and no virtualization rights) and 4 commercial editions – Foundations (OEM only), Essentials, Standard, and Datacenter. Hyper-V offers:

Live migration
Storage migration
VM Replication (Replica)
Dynamic memory
Extensible virtual switch
High availability
Scale up to 320 logical processors, 4TB of memory, 2,048 virtual CPUs per host, 64 vCPUs per VM, 1TB of memory per VM, and 64 nodes / 8000 VMs per cluster
Virtualization rights to run a specific number of Windows VMs without purchasing additonal licenses (2 Windows OS rights are included in Standard edition and an unlimited number are included in datacenter)
)
####################################################################################
Xen / Citrix XenServer. (Xen is a type-1 bare-metal hypervisor. Just as Red Hat Enterprise Virtualization uses KVM, Citrix uses Xen in the commercial XenServer. In 2007 Citrix bought XenSource, Inc, who supported Xen. Today, the Xen open source projects and community are at Xen.org. Today, XenServer is a commercial tier-1 hypervisor solution from Citrix, offered in 4 editions. Confusingly, Citrix has also branded their other proprietary solutions like XenApp and XenDesktop with the Xen name. XenServer offers features such as:

Conversion tools
Integration System Center Virtual Machine Manager
Snapshot and revert
XenCenter Management Console (even in the free edition)
Live migration (even in the free edition)
Live storage migration
Distributed virtual switch
High availability
Power management
Memory optimization
Monitoring and alerting)
##############################################################################
Red Hat Enterprise Virtualization (RHEV). (is a commercial implementation of the KVM Type-1 hypervisor. Red Hat Enterprise Virtualization uses SPICE protocol and VDSM (Virtual Desktop Server Manager) with a RHEL-based centralized management server. RHEV offers support the following advanced features:

Network bonding, VLAN, and 10GB
Live migration, policy-based workload balancing, high availability, power saving, cluster maintenance, image management, templating, thin-provisioning, and event monitoring
Hosts support up to 160 cores and 2 TB of RAM. Guests support up to 64 vCPUs and 512 GB of RAM
Self Service user portal
Reporting and monitoring, detailed historical reporting capabilities, monitor historical usage, trending, quality of service)
#############################################################################
KVM.(Kernel-Based Virtual Machine) is a Linux-based type-1 hypervisor that can be added to a most Linux operating systems including Ubuntu, SUSE, and Red Hat Enterprise Linux. It supports most common Linux operating systems, Solaris, and Windows. Most hypervisors that offer KVM offer additional management tools on top such as Red Hat’s Virtual Machine Manager.)
