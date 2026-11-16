# S01 · Regional Defense WAN: Secure HA Edge for 18 Sites

**Sector:** Defense, Bangladesh (regional network upgrade project)
**Role:** Planned, designed and implemented

## Security objective
Connect 18 sites in a regional zone securely back to central headquarters. The regional edge must stay available if any single router, switch or firewall fails.

## Security controls delivered
| Control | Implementation |
|---|---|
| Next-generation firewall | Palo Alto **PA-820** at the regional hub |
| Firewall high availability | **Active/passive HA** pair, with active/passive HA also across the edge router (MX-104) and core switch (EX-4300-32F) |
| Access control | ACLs on the PA-820 limiting traffic between sites and HQ |
| Threat prevention | **UTM bundle** (threat prevention subscriptions) enabled on the PA-820 |
| Encrypted transport | **GRE over IPsec VPN** to headquarters, so dynamic routing runs inside encrypted tunnels |
| Site security | Juniper SRX-345 / SRX-550 at the sites |
| Resilient routing | BGP and OSPF, so traffic reconverges around failures |

## Platforms
Palo Alto PA-820 · Juniper SRX-345, SRX-550 · Juniper MX-104 · Juniper EX-4300 / EX-4200 / EX-2200
