# Project roadmap

These are planned uses of the donated equipment. They do not claim that the gear has been deployed.

| Project | Related repository | Candidate gear | Next milestone |
|---|---|---|---|
| Home network expansion | [secure-home-network-lab](https://github.com/MReyna22/secure-home-network-lab) | AP-001–004, SW-001–003, compatible power equipment; GW-001 for possible isolated lab use | Verify power, test equipment, and document a proposed topology |
| Active Directory lab | [AD_HL_1](https://github.com/MReyna22/AD_HL_1) | PC-001 as a candidate VM host; PC-002 for possible supporting services | Inspect computer resources and plan the lab VMs |
| R36S toolkit | [R36S-Lite-Cyberdeck](https://github.com/MReyna22/R36S-Lite-Cyberdeck) | The donated lab network as a controlled test environment | Recheck diagnostics and report exports against lab devices |
| Local AI agents using Hermes | Repository not created | PC-003 as a candidate local AI workstation; spare mini PC capacity for supporting services | Inspect RAM and graphics, establish local inference, and test one agent workflow |
| USG Revival / OpenWrt | Standalone repository planned; not yet created | GW-001 and PWR-004 | Inspect the preserved OEM image, establish a recovery path, and validate OpenWrt before network deployment |
| Gear inspection and deployment | Tracked in this repository | All 19 inventory entries | Document baseline condition, tests, required resets, setup, and configuration |

The R36S itself is an existing project device and is not part of the 19-item donation inventory.

## USG Revival / OpenWrt

This is a separate investigation and rebuild project. The donation repository tracks the equipment and acknowledgment; the future USG repository will hold the technical work.

Original boot-media preservation is complete according to the supplied FTK Imager screenshots: a raw physical image was acquired, MD5 and SHA-1 verification matched, and an independent SHA-256 result was recorded. Firmware and filesystem analysis, recovery testing, OpenWrt installation, and network validation remain pending. Keep the raw firmware image and identifying evidence private.

Planned learning areas include firewall rules, NAT, DHCP, DNS, VLAN isolation, VPN access, logging, and assessment of IDS/IPS feasibility. These are project goals, not completed capabilities. pfSense/OPNsense is no longer the planned route, so PC-001 and PC-002 remain available for other lab roles. The XR1000 remains the current household router while the USG is investigated.

## Work order

1. Inspect the computers and verify compatible power sources for network gear.
2. Build a small lab network using tested equipment.
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

