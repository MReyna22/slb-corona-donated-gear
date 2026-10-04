# SLB Corona Donated Gear

Hardware inventory and deployment documentation for my IT and cybersecurity home lab. This repository tracks equipment donated by Antonio Corona from initial identification through inspection, configuration, testing, and assignment to projects.

**Maintainer:** [Misael Reyna](https://github.com/MReyna22)  
**Status:** Initial inventory recorded; PC-001 BIOS baseline documented; GW-001 OpenWrt revival and basic validation completed; remaining equipment pending  
**Inventory baseline:** October 3, 2026 · 19 individual entries

## Project purpose

My goal is to turn this equipment into a documented lab for networking, systems administration, cybersecurity, and local AI experimentation. The records here will connect each device to its requirements, configuration decisions, test results, and actual use.

This repository is the central inventory and donor acknowledgment. Technical implementation and results belong in the related project repositories, with links back to the equipment records.

## Explore the documentation

| Document | What it contains |
|---|---|
| [Hardware inventory](inventory/2026-10-03-inventory-r2.csv) | Device IDs, models, power requirements, planned use, actual use, and test status |
| [Inventory maintenance](inventory/README.md) | Source limitations, stable IDs, and snapshot update process |
| [GW-001 revival record](docs/devices/GW-001.md) | USG preservation, OpenWrt revival, validation results, and related project |
| [PC-001 inspection record](docs/devices/PC-001.md) | Confirmed OptiPlex hardware, BIOS settings, validation status, and next checks |
| [Equipment needs](docs/equipment-needs.md) | Supporting power and cabling requirements, current availability, and selection criteria |
| [Project roadmap](docs/projects.md) | Candidate equipment, related repositories, dependencies, and next milestones |
| [Inspection and deployment](docs/inspection-and-deployment.md) | Baseline checks, reset decisions, configuration records, and validation requirements |
| [Change log](CHANGELOG.md) | Significant inventory and documentation changes |

## Scope and current progress

The initial inventory contains four wireless access points, three switches, two PoE injectors, five power adapters, one security gateway, two mini PCs, one all-in-one PC, and one Ethernet patch cable.

| Stage | Current status | Completion evidence |
|---|---|---|
| Identification and inventory | Initial baseline recorded | Dated inventory snapshot with 19 unique item IDs |
| Physical inspection and power verification | Pending | Per-device condition, interfaces, accessories, and compatible power source |
| Hardware and firmware assessment | PC-001 BIOS baseline recorded; GW-001 USB/firmware assessment documented; remaining assessments pending | Installed specifications, firmware or BIOS versions, and management state |
| Reset and configuration | GW-001 repurposed with OpenWrt; other equipment pending | Reset rationale, configuration decisions, and recovery information |
| Functional validation | GW-001 boot, LAN, routing, DNS, and browsing validated; other equipment pending | Test procedure, expected result, observed result, and sanitized evidence |
| Project deployment | GW-001 revival completed with PC-001 as the wired test client; wider deployment pending | Confirmed item IDs, actual use, and links to implementation records |

The baseline comes from the initial inventory records. Original photos and installed computer specifications have not been rechecked for this repository. Device identification and proposed assignments are starting points for inspection.

## Related projects

| Project | Planned contribution from this equipment |
|---|---|
| [USG Revival](https://github.com/MReyna22/USG-Revival) | Completed GW-001 OpenWrt revival; PC-001 used for wired client validation |
| [Home network lab](https://github.com/MReyna22/secure-home-network-lab) | Managed switching, wireless access, and a possible isolated gateway |
| [Active Directory lab](https://github.com/MReyna22/AD_HL_1) | Candidate virtualization and supporting infrastructure hosts |
| [R36S Lite Cyberdeck](https://github.com/MReyna22/R36S-Lite-Cyberdeck) | A controlled network for diagnostics and report validation |
| Local AI agents using Hermes | A candidate workstation for an initial agent workflow; feasibility depends on hardware inspection |

See the [project roadmap](docs/projects.md) for equipment assignments and next milestones. USG Revival records a completed implementation. The other assignments remain proposed until tested.

## Equipment overview

| Item ID | Item | Model or type recorded |
|---|---|---|
| AP-001 | UniFi AP AC Pro | UAP-AC-PRO |
| AP-002 | UniFi AP AC Pro | UAP-AC-PRO |
| AP-003 | UniFi AP AC LR | UAP-AC-LR |
| AP-004 | UniFi AP AC LR | UAP-AC-LR |
| SW-001 | UniFi Switch Flex | USW-Flex |
| SW-002 | UniFi Switch Flex | USW-Flex |
| SW-003 | UniFi Lite 8 PoE | USW-Lite-8-PoE |
| PWR-001 | Gigabit PoE Injector | GP-A240-050G |
| PWR-002 | Gigabit PoE Injector | POE-24-24W-G |
| PWR-003 | USW-Lite-8-PoE Adapter | ADS-60SH-54-1 54060E |
| GW-001 | UniFi Security Gateway | USG |
| PWR-004 | USG AC/DC Adapter | RR-Ubi-GP-F120-100 |
| PC-001 | OptiPlex 3070 Micro | D10U / D10U003 |
| PWR-005 | OptiPlex 3070 Adapter | Dell 65W |
| PC-002 | ThinkCentre M93p Tiny | M93p / Type 10AB |
| PWR-006 | ThinkCentre M93p Adapter | Lenovo 65W |
| PC-003 | Inspiron 27 7730 All-in-One | W28C regulatory model |
| PWR-007 | Inspiron 27 7730 Adapter | Dell 130W |
| CAB-001 | Cat6 Gigabit Patch Cable | GigaSystem / E126126-DG marking |

The two AC LR access points remain separate because their recorded power labels differ. AP-003 calls for 24V passive PoE, while AP-004 identifies 802.3af PoE. Power sources must be matched to the individual device before use.

## Documentation standards

- Keep **Planned Use** separate from **Actual Use**. Record deployment only after setup and validation.
- Use stable item IDs across inventory snapshots, device records, and project documentation.
- Explain decisions, including power compatibility, reset requirements, configuration choices, and constraints.
- Record test methods and observed results, including failures and unresolved issues.
- Publish sanitized evidence. Keep credentials, device-specific identifiers, configuration backups, and private network details outside the public repository.

The Google Sheet remains the working inventory. This repository contains reviewed, dated public snapshots; changes are not automatically synchronized. The [inventory update process](inventory/README.md) explains how to keep the records aligned.

## Dedication to Antonio Corona

I dedicate this repository, along with my ongoing and future projects, to Antonio Corona, who gave me an opportunity to demonstrate my knowledge and potential in IT and cybersecurity.

Antonio, thank you for donating this gear and for believing in me. Before we met, I was feeling lost in my journey into this field. I would watch networking and AI videos on YouTube and think, “When I can afford more gear, I’ll build projects like these.” I was stuck in a constant “one day” mentality.

Your donation means more to me than you may realize. It has given me the opportunity to turn what I’ve learned into practical experience and move forward with projects I had been putting off. Just as much, I appreciate that you saw potential in me while I was struggling to see a path forward.

The late nights and continued learning, despite the challenges I was facing, now have somewhere to go. I look forward to sharing what I build and learn with this equipment, and I hope to make you proud along the way.

I admire the brother, father, and man you are. One day, I hope to give someone else the encouragement and opportunity you have given me.

Thank you, Antonio.

— Misael Reyna

Antonio is acknowledged as the hardware donor. Project design, configuration, testing, and documentation are my responsibility.
