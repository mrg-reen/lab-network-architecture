# lab-network-architecture
This project documents my home lab environment, designed to simulate real-world network segmentation, firewall management, and detection engineering in a controlled setting. It’s built on a UDM Pro with VLANs, Class C subnetting, and isolated security zones for structured learning. The home lab will also benefit learning in software development, automation, cloud technologies, and DevOps Methodologies.

**Firewall Zone Policy Examples**
- Blocking Guest (Hotspot) to Internal Zone
- Blocking IoT (Internal) to Internal Zone
- Blocking HoneyPot to Internet
- Blocking LABS to Internal except for certain test hosts
- Allowing Internal to VPN
- Allowing LABS to Internet


**Inside the repo**
- /docs/ -> Subnetting, VLANs, Firewall Design, Detections
- /diagrams/ -> Network topologies and flowcharts
- /configs/ -> Exported UniFi configs & setup instructions
- /threat-model/ -> Attack scenarios and mitigation logic

**Future Work**
- Add VPN jumpbox with MFA
- Deploy ELK stack and forward logs from each VLAN
- Launch attack simulations and validate firewall rules
- Add automated detection via Suricata or Zeek


**Hardware**
- UniFi UDM Pro
- Ubiquiti Switch
- Several lab machines (Linux, Kali, Windows)
- Raspberry Pi 5
- External drive for PCAP/log collection


**Licenses**
- MIT

With this project I will simulate and master core enterprise principles like: segmentation, least privilege, monitoring, attack surface reduction, and more. 
