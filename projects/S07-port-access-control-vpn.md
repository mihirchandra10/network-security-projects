# S07 · Port Access-Control Network with Secure Off-Dock VPN

**Sector:** Seaport authority, Bangladesh (access control project)
**Role:** Network design and implementation

## Security objective
Support a physical-security system (gate access control and UVIS, the under-vehicle inspection system) with a reliable, segmented network, and connect a remote off-dock site securely.

## Security controls delivered
| Control | Implementation |
|---|---|
| Segmented access network | L2/L3 network for gate access on Juniper EX-2200 / EX-4300 |
| Security-system integration | UVIS integrated with the existing network infrastructure |
| Encrypted remote site | **Dynamic IPsec VPN** from the off-dock site on Juniper **SRX-220** |
| Wireless | MikroTik access points at 11 locations |

## Platforms
Juniper SRX-220 · Juniper EX-2200, EX-4300 · MikroTik
