# S06 · Two-Campus Zone-Based Security and VPN

**Sector:** Government mapping agency, Bangladesh (two office campuses)
**Role:** Designed and implemented

## Security objective
Secure two office campuses and connect them over an encrypted link.

## Security controls delivered
| Control | Implementation |
|---|---|
| Campus firewalls | Juniper **SRX-220** at each campus |
| Segmentation | **Zone-wise security policy** separating user, server and external zones |
| Access control | ACLs |
| Threat inspection | **UTM** |
| Encrypted inter-campus link | **Site-to-site IPsec VPN** between the two campuses |
| LAN | L2/L3 network on EX-2200, EX-4300, Brocade VDX-6740 and HP 1920-48G |

## Platforms
Juniper SRX-220 · Juniper EX series · Brocade VDX-6740 · HP 1920
