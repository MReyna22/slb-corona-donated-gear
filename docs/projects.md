# Project roadmap

This roadmap separates completed work from planned uses of the donated equipment. Last reconciled October 5, 2026.

| Project | Related repository | Candidate gear | Next milestone |
|---|---|---|---|
| Home network expansion | [secure-home-network-lab](https://github.com/MReyna22/secure-home-network-lab) | AP-001–004, SW-001–003, compatible power equipment; GW-001 for possible isolated lab use | Verify power, test equipment, and document a proposed topology |
| Active Directory lab | [AD_HL_1](https://github.com/MReyna22/AD_HL_1) | PC-001 as a candidate VM host; PC-002 for possible supporting services | PC-001 initial setup complete by operator confirmation; assess capacity and plan VMs before deployment |
| R36S toolkit | [R36S-Lite-Cyberdeck](https://github.com/MReyna22/R36S-Lite-Cyberdeck) | The donated lab network as a controlled test environment | Recheck diagnostics and report exports against lab devices |
| Local AI agents using Hermes | Repository not created | PC-003 as a candidate local AI workstation; spare mini PC capacity for supporting services | Inspect RAM and graphics, establish local inference, and test one agent workflow |
| USG Revival / OpenWrt | [USG-Revival](https://github.com/MReyna22/USG-Revival) | GW-001 and PWR-004; PC-001 as wired test client | Revival and basic routing/DNS/browsing validation complete; wider deployment remains separate |
| Gear inspection and deployment | Tracked in this repository | All 19 inventory entries | Document baseline condition, tests, required resets, setup, and configuration |

The R36S itself is an existing project device and is not part of the 19-item donation inventory.

## USG Revival / OpenWrt

The [completed USG Revival project](https://github.com/MReyna22/USG-Revival) documents the investigation, original USB preservation, filesystem analysis, installation decisions, and basic validation. This donation repository tracks the equipment and acknowledgment.

The original internal USB was imaged and verified before reuse; the raw image remains private. OpenWrt 25.12.5 booted on GW-001 using the stock drive. The hostname survived a restart, the administrator password was changed and verified with a fresh login, and a configuration archive was kept private.

PC-001 served as the wired LAN client. Retained evidence shows a 1 GbE LAN link, a WAN DHCP lease, four successful Internet ping replies without loss, and DNS resolution. The operator also confirmed example.com loaded in Edge. Visible firewall-zone policies were reviewed; inbound enforcement, throughput, and a full security audit were not tested. See the [GW-001 device record](devices/GW-001.md) and the [USG evidence index](https://github.com/MReyna22/USG-Revival/tree/main/evidence).

Planned learning areas include firewall rules, NAT, DHCP, DNS, VLAN isolation, VPN access, logging, and assessment of IDS/IPS feasibility. These are project goals, not completed capabilities. pfSense/OPNsense is no longer the planned route, so PC-001 and PC-002 remain available for other lab roles. The household router remains the upstream router. GW-001's validated test setup does not establish that it has replaced the household gateway.

## Work order

1. Complete PC-001's remaining Windows/Wi-Fi and BIOS-view evidence after publishing the two recovered BIOS photographs, then assess its VM capacity; inspect the remaining computers and verify compatible power sources for network gear.
2. Build on the validated GW-001 / PC-001 wired test setup and plan a small lab network using tested equipment.
3. Advance Active Directory and R36S testing.
4. Pilot local inference and one useful Hermes agent workflow.
5. Record actual deployments and expand from tested results.

## Referencing the donation

When a project uses this gear, add an acknowledgment linking to the root of this repository and list the item IDs it uses. Link only to evidence and repositories that exist. A project plan becomes actual use after installation and testing are documented.

### Project dedication

For ongoing or future projects, use a brief dedication that links to the full message here:

> Dedicated to Antonio Corona, whose support helped me turn continued learning into hands-on IT and cybersecurity projects. Read the [dedication and donation record](https://github.com/MReyna22/slb-corona-donated-gear#dedication-to-antonio-corona).

### Equipment acknowledgment

When a project uses donated equipment:

> This project uses equipment donated by Antonio Corona. The donation inventory and acknowledgment are maintained in [SLB Corona Donated Gear](https://github.com/MReyna22/slb-corona-donated-gear). Equipment used: list the confirmed item IDs.

Replace the final sentence with the actual item IDs before publishing it in a project.
