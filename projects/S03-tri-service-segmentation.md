# S03 · Tri-Service Secure Video-Conferencing Network

**Sector:** Defense, Bangladesh (Armed Forces Division: army, navy and air force)
**Role:** Planned, designed and implemented

## Security objective
Build one network for video conferencing between the three services, while keeping each service's network separated and protected.

## Security controls delivered
| Control | Implementation |
|---|---|
| Firewalled core | Juniper **SRX-345** at the core |
| Per-service firewalls | Juniper **SRX-220** for each service |
| Segmentation | Separate security zones per service; only the required video-conferencing flows are allowed between them |
| Access control | ACLs on the core, aggregation and access layers |
| Threat inspection | **UTM** enabled on the SRX firewalls |
| Network design | Three-tier core / aggregation (EX-4200) / access |

## Platforms
Juniper SRX-345, SRX-220 · Juniper EX-4200
