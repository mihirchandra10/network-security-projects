# Network Security Projects

Production network-security projects I planned, designed and delivered. They cover **Palo Alto, Fortinet and Juniper SRX** next-generation firewalls, IPsec VPNs, IPS/UTM, firewall high availability and DDoS mitigation, for defense, government, telecom and enterprise customers in Bangladesh (2013 to the present).

> 🔒 **Confidentiality:** only scope, security design approach and technologies are described. No IP addresses, rule bases, configurations or topology details from customer networks are published. Defense and government customers are described by sector, not by name.

## ⭐ Major projects

| Project | Customer | What I delivered |
|---|---|---|
| [Data security system: Juniper upgrade & colour BGP](projects/S11-grameenphone-data-security-system.md) | **Grameenphone**, the largest mobile operator in Bangladesh | Planned and implemented the Juniper firmware upgrade and BGP community ("colour") routing for the operator's data security system |
| [Data center perimeter firewall HA](projects/S02-defense-dc-perimeter-ha.md) | Defense data center, Dhaka | Planned, designed and implemented active/passive HA between **Palo Alto PA-3060** firewalls |
| [UTM and threat prevention rollout](projects/S04-fortigate-utm-threat-prevention.md) | **Laugfs Gas Bangladesh** | **FortiGate 100E** integration with IPS, antivirus, threat prevention and site-to-site IPsec VPN |
| [University DMZ firewall](projects/S05-university-dmz-firewall.md) | Science & technology university | **Juniper SRX1500** deployed as DMZ firewall with ACLs and UTM |

## All security projects

| # | Project | Sector | Firewall platform | Security controls delivered |
|---|---|---|---|---|
| S01 | [Regional defense WAN: secure HA edge for 18 sites](projects/S01-defense-wan-secure-ha-edge.md) | Defense | Palo Alto PA-820 · Juniper SRX-345/550 | Active/passive firewall HA, GRE over IPsec, ACL, UTM bundle, BGP/OSPF |
| S02 | [Data center perimeter firewall HA](projects/S02-defense-dc-perimeter-ha.md) | Defense | Palo Alto PA-3060 | Active/passive HA, session sync, failover testing |
| S03 | [Tri-service secure video-conferencing network](projects/S03-tri-service-segmentation.md) | Defense (army, navy, air force) | Juniper SRX-345 / SRX-220 | Service-level segmentation, ACL, UTM |
| S04 | [UTM and threat prevention rollout](projects/S04-fortigate-utm-threat-prevention.md) | Energy / LPG (Laugfs Gas) | FortiGate 100E | IPS, antivirus, threat prevention, site-to-site IPsec |
| S05 | [University DMZ firewall](projects/S05-university-dmz-firewall.md) | Technical university | Juniper SRX1500 | DMZ zone design, ACL, UTM |
| S06 | [Two-campus zone-based security and VPN](projects/S06-two-campus-zone-security-vpn.md) | Government mapping agency | Juniper SRX-220 | Zone-wise security policy, ACL, UTM, site-to-site IPsec |
| S07 | [Port access-control network with secure off-dock VPN](projects/S07-port-access-control-vpn.md) | Seaport authority | Juniper SRX-220 | Dynamic IPsec VPN, L2/L3 segmentation for gate access and UVIS |
| S08 | [Secure enterprise wireless and guest isolation](projects/S08-wireless-security-guest-access.md) | Apparel manufacturing (MAS Intimates) | Ruckus ZD-1200 | Controller HA, SSID authentication, ACL, token-based guest pass |
| S09 | [Carrier gateway security: IIG / ISP](projects/S09-iig-carrier-security-ddos.md) | International Internet Gateway (Earth Telecommunication) | Juniper MX series | Firewalls, intrusion detection, DDoS mitigation, BGP security |
| S10 | [Cloud security: IAM, MFA and secure architecture](projects/S10-cloud-security-iam-mfa.md) | Enterprise customers (Open Communication, RASA Technologies) | AWS / Azure / GCP | IAM roles and policies, MFA, cloud security architecture |
| S11 | [Data security system: Juniper upgrade & colour BGP](projects/S11-grameenphone-data-security-system.md) | Mobile operator (Grameenphone) | Juniper | Firmware upgrade of the security system, BGP community traffic steering |

## Security controls by project

| Control | S01 | S02 | S03 | S04 | S05 | S06 | S07 | S08 | S09 | S10 | S11 |
|---|---|---|---|---|---|---|---|---|---|---|---|
| NGFW / zone-based policy | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | | ✅ | | |
| Firewall / controller HA | ✅ | ✅ | | | | | | ✅ | | | |
| IPS / IDS / threat prevention | ✅ | | | ✅ | | | | | ✅ | | |
| Antivirus / UTM | ✅ | | ✅ | ✅ | ✅ | ✅ | | | | | |
| IPsec VPN | ✅ | | | ✅ | | ✅ | ✅ | | | | |
| ACL / segmentation | ✅ | | ✅ | | ✅ | ✅ | ✅ | ✅ | | | |
| DDoS mitigation | | | | | | | | | ✅ | | |
| Identity / authentication (IAM, MFA, wireless auth) | | | | | | | | ✅ | | ✅ | |
| Security platform upgrade / traffic steering | | | | | | | | | | | ✅ |

## Security responsibilities by role

| Period | Company | Security scope |
|---|---|---|
| 2025 – now | Synesis IT PLC | Firewalls, VPN solutions for secure connectivity, monitoring and troubleshooting of security systems |
| 2024 – 2025 | RASA Technologies | Cloud security with IAM, MFA and secure architecture |
| 2020 – 2024 | Open Communication Ltd. | **Manager, Network Solutions & Security:** oversaw the robustness of network and security solutions, designed cloud security architectures and policies, IAM roles and MFA |
| 2016 – 2019 | Biometrics-BD Ltd. | Implemented and maintained firewalls, security zones, VPNs and intrusion detection/prevention; security incident management |
| 2013 – 2016 | Earth Telecommunication (IIG) | Network security for an international gateway: firewalls, intrusion detection, DDoS mitigation |

## Platforms

**Palo Alto** PA-3060, PA-820 (PAN-OS) · **Fortinet** FortiGate 100E (FortiOS) · **Juniper** SRX1500, SRX-550, SRX-345, SRX-220 (Junos) · **Ruckus** ZoneDirector 1200 · **Cloud** AWS, Azure, GCP

## Certifications
AWS Certified Solutions Architect – Associate · Palo Alto ACE · Fortinet NSE 1 & 2 · JNCIA-Junos · JNCIA-Cloud · JNCIS-Cloud · CCNA R&S · HCNA R&S

## Related
- [network-projects-portfolio](https://github.com/mihirchandra10/network-projects-portfolio): network engineering career and projects
