# S05 · University DMZ Firewall

**Sector:** Science and technology university, Bangladesh
**Role:** Implementation

## Security objective
Separate the university's public-facing services from the internal network, and inspect traffic to them.

## Security controls delivered
| Control | Implementation |
|---|---|
| DMZ firewall | Juniper **SRX1500** deployed into the existing network as the DMZ firewall |
| Zone design | Separate DMZ zone for public services, isolated from internal zones |
| Access control | ACLs and security policies that allow only the required services |
| Threat inspection | **UTM** enabled |

## Platforms
Juniper SRX1500 · Junos
