# SLB Corona Donated Gear

## Dedication to Antonio Corona

I dedicate this repository, along with my ongoing and future projects, to Antonio Corona, who gave me an opportunity to demonstrate my knowledge and potential in IT and cybersecurity.

Antonio, thank you for donating this gear and for believing in me. Before we met, I was feeling lost in my journey into this field. I would watch networking and AI videos on YouTube and think, “When I can afford more gear, I’ll build projects like these.” I was stuck in a constant “one day” mentality.

Your donation means more to me than you may realize. It has given me the opportunity to turn what I’ve learned into practical experience and move forward with projects I had been putting off. Just as much, I appreciate that you saw potential in me while I was struggling to see a path forward.

The late nights and continued learning, despite the challenges I was facing, now have somewhere to go. I look forward to sharing what I build and learn with this equipment, and I hope to make you proud along the way.

I admire the brother, father, and man you are. One day, I hope to give someone else the encouragement and opportunity you have given me.

Thank you, Antonio.

— Misael Reyna

This repository keeps the donation acknowledgment, inventory snapshots, and inspection records in one place. As the equipment is tested and assigned to projects, I will update its planned and actual use.

Maintained by **Misael Reyna**.

## Current status

The initial inventory contains **19 individual entries**:

- 4 wireless access points
- 3 switches
- 2 PoE injectors and 5 power adapters
- 1 security gateway
- 2 mini PCs and 1 all-in-one PC
- 1 Ethernet patch cable

Hardware inspection, power compatibility checks, resets where appropriate, configuration, and functional testing remain pending. An inventory entry does not mean a device has been tested or deployed.

## Inventory

The working inventory is maintained in a Google Sheet. This repository contains dated public snapshots; it does not automatically sync with that sheet.

- [Inventory snapshot: October 3, 2026](inventory/2026-10-03-inventory.csv)
- [Inventory and update instructions](inventory/README.md)
- [Project plans and related repositories](docs/projects.md)
- [Inspection and deployment checklist](docs/inspection-and-deployment.md)
- [Change log](CHANGELOG.md)

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

## Projects this gear can support

The first planned uses are expanding the home network lab, supporting the Active Directory lab, providing a controlled testing environment for the R36S toolkit, and exploring local AI agents using Hermes.

Computer assignments are provisional until CPU, RAM, storage, graphics, and virtualization capability are inspected. Actual use will be recorded after setup and testing.

## A living record

Corrections and changes are expected as inspections continue. Stable item IDs connect inventory records, inspection notes, and project documentation. Completed work should include the test result and supporting evidence.

Public files exclude credentials, serial numbers, Service Tags, full MAC addresses, and exact private network details. Device photos will be added only after they are redacted and reviewed.

Antonio is credited as the hardware donor. Project design, configuration, testing, and documentation are my responsibility.
