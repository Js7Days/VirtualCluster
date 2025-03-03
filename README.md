Case Study (Current and Proposed Infrastructure)
Albert & Allen Logistics (AA) is a private business that provides passenger transport and freight services for Australian-wide clients and businesses. Various upgrades to the organisation’s network were installed on servers that were purchased in 2014 and before, so their warranties are no longer valid. Some servers are prone to unexplained failures requiring additional time and effort for maintenance.
Management is requesting proposals for the improvement and expansion of its technology infrastructure. The intention of this RFP (Request for Proposal) is to invite vendors to submit a plan to supply a server virtualisation solution which will include hardware, software, installation, and documentation. The scope of this RFP will cover the improvement and expansion of the existing server infrastructure and will include servers, network storage, and reconfiguration of the current network.
AA has 12 physical servers from which IT services are provided to staff and clients. They use a range of operating systems including Linux and Windows Server 2008 / 2012 R2. Critical data is backed up to network attached storage (NAS) devices. One of the primary goals for this project is to improve the infrastructure by reusing existing hardware where possible, combined with new hardware and using cost effective solutions which would provide geographically separated data redundancy through high-speed network connectivity. The solution that you provide should support consolidation, scalability, and disaster recovery, continued centralised management and high availability.
Shawn Long, the organisation’s director of IT, said that they had had a server crash and spent 24 hours rebuilding the system and repairing the network. That experience prompted Shawn to re-evaluate the availability of email, databases, user information and other business workloads in the organisation. The company currently has 510 employees at the central office (including the ten IT staff). He has also proposed that additional redundancy and load balancing measures should be introduced to the AA network to ensure greater high availability of network services. Therefore, in addition to the primary VM hosts, two additional VM hosts will replicate the primary VM hosts in real time using a hot standby setup.
All servers are located in their own climate controlled central data centre which also contains the local and wide area network switch and NBN modems. The network room switch then connects via fibre-optic cable to 1Gb managed network switches located in the management (10 computers), administration (15 computers), call centre (70 computers), logistics (150 computers and devices), and maintenance (10 computers) departments that are located in different parts of the organisations complex. All desktop computers are running either Microsoft Windows 8.1 or 10 Pro.
The organisation is considering using server virtualisation by purchasing new servers, installing hypervisors on them, then building new virtual servers and migrating data from physical servers to the virtual environment as the obsolete servers are replaced. The organisation has purchased two Dell PowerEdge R750 servers with the following configuration:
•	2 x Intel 3.2Gb CPU
•	16GB RAM
•	PERC H755 RAID controller
•	2 x 1.2TB SAS HDD – configured for RAID 1
•	4 x 1.2TB SAS HDD – configured for RAID 10
•	1 x 1.2TB SAS HDD as a universal hot spare
•	DVD+/-RW 
•	Quad port 10GbE Base-T network adapter
•	Microsoft Windows Server 2019 Standard
•	5-year ProSupport Plus 4-hour critical response 

The existing physical servers consist of:
•	Seven servers running various Windows Server operating systems which provide:
	Active Directory Domain Services (AD DS)
	Windows Deployment Services (WDS)
	File and print servers
	Email server
	Application servers
	Monitoring services
•	Three Linux based servers for web services, security, and network services administration, including:
	Dynamic Host Configuration Protocol (DHCP) using dhcpd
	Domain Name System (DNS) using BIND
	Apache web server using httpd
	Samba file server
•	Two other Linux/BSD servers provide firewall and routing services.
