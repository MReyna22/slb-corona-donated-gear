# Inventory snapshots

The Google Sheet is the working inventory. These CSV files are dated public snapshots so changes can be reviewed in Git.

The current snapshot is [2026-10-05-inventory-r4.csv](2026-10-05-inventory-r4.csv), reconciled from the working sheet on October 5, 2026. Revision 4 records PC-001's eight new verification screenshots, covering Windows version/update, memory, basic storage status, separate Ethernet/Wi-Fi connectivity, and webpage display. It retains PC-002's photographed components and pending DisplayPort check, plus GW-001's completed revival. It contains 37 working-inventory columns and 19 unique item IDs. All earlier snapshots remain unchanged.

The initial snapshot contains 19 entries, one row per physical device or inventoried cable. Item IDs stay the same when equipment moves or changes purpose.

## Update process

1. Update confirmed details in the working sheet.
2. Keep planned use separate from actual deployment.
3. Export a reviewed public snapshot as YYYY-MM-DD-inventory.csv. For another snapshot on the same day, add a revision suffix.
4. Check that identifiers, credentials, private locations, and private network details are excluded.
5. Update the inventory link in the main README and add the meaningful change to CHANGELOG.md.
6. Commit the reviewed changes.

A blank, TBD, Pending, Not recorded, Not reported, or Not tested value indicates missing information or unfinished work. N/A means that field does not apply.

## Source and limits

The October 3 baseline combines the AP inventory and the equipment recorded in the Identify Device Capabilities chat. Model names, label text, and proposed uses are retained from those records.

The October 5 revision 4 snapshot updates PC-001 from eight user-supplied screenshots retrieved for archival review. Windows 11 Pro 25H2 / build 26200.9550, the current Windows Update display, memory, and basic Windows storage status are now retained with separate Ethernet/Wi-Fi ping and DNS evidence. The Wi-Fi test used 2.4 GHz / 802.11n; 5 GHz and Bluetooth remain untested. Link rates are not throughput results, and a browser display alone does not identify its network adapter. Reassembly/startup remains operator-confirmed. Two BIOS photographs and two component photographs were previously redacted and published with the [PC-001 device record](../docs/devices/PC-001.md); other BIOS settings remain earlier transcriptions. Comprehensive drive diagnostics and VM workload assessment remain untested. Historical USG client checks remain linked to the public [USG Revival](https://github.com/MReyna22/USG-Revival) evidence.

GW-001 revival and basic bench validation are complete. Throughput, sustained stability, inbound firewall enforcement, and backup restoration remain untested. PC-002's two redacted internal photographs are linked in its [inspection record](../docs/devices/PC-002.md). Its drive label identifies a Seagate ST500LM021 500 GB 7200 RPM SATA hard drive; two SO-DIMM slots are populated, with capacity and speed still unverified. BIOS, display/startup, OS, storage-health and network checks are pending the DisplayPort cable. Other device rows retain their prior status. Planned VM roles remain separate from actual Windows client use.

This snapshot is a reviewed copy of Inventory!A1:AK20, not an automatic synchronization. Update dates reflect when records were reconciled, rather than the original photo capture dates.

Power ratings and adapter associations are inventory observations. They do not replace checking voltage, polarity, connector fit, PoE mode, and available power before connection.

The snapshot keeps published model or regulatory-type labels, but excludes device-specific serial numbers, MAC addresses, Service Tags, QR codes, and private location fields.
