# S02 · Data Center Perimeter Firewall HA

**Sector:** Defense, Bangladesh (central data center, Dhaka)
**Role:** Planned, designed and implemented

## Security objective
Remove the perimeter firewall as a single point of failure for the data center, without weakening the security policy.

## Security controls delivered
| Control | Implementation |
|---|---|
| Perimeter NGFW | Pair of Palo Alto **PA-3060** firewalls |
| High availability | **Active/passive HA**: one firewall forwards traffic, the peer stands by with the same configuration |
| Session continuity | Session state synchronised so existing connections survive a failover |
| Failover triggers | Link and path monitoring on the data-plane interfaces |
| Validation | Controlled failover tests before handover to the customer |

## Platforms
Palo Alto PA-3060 · PAN-OS HA
