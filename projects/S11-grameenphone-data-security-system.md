# S11 · Grameenphone Data Security System: Juniper Upgrade & BGP Colour Routing

**Customer:** Grameenphone, Bangladesh's largest mobile operator (data security system)
**Role:** Planned and implemented

## Security objective
Upgrade the Juniper platform behind Grameenphone's **data security system** to supported firmware, and implement **BGP community ("colour") routing** so traffic is steered correctly through the security infrastructure. Both had to be done without disrupting a national mobile data network.

## What was delivered
| Area | Implementation |
|---|---|
| Firmware upgrade | Planned and executed the **Juniper firmware upgrade** of the data security system, bringing it to a supported release with current security fixes |
| Upgrade safety | Pre-upgrade baselines (routing, BGP sessions, interfaces), a staged maintenance-window plan and a rollback plan |
| **Colour BGP** | Configured BGP communities ("colours") to tag routes and steer traffic through the security system |
| Validation | Post-upgrade checks of BGP sessions, route tables and traffic flow against the baseline |

## Why it matters
In a carrier network, the security system is only effective if the right traffic reaches it. Colour BGP made that steering policy-based and repeatable, and the upgrade closed the risk of running outdated firmware.

## Platforms
Juniper (Junos) · BGP communities and routing policy · carrier change management
