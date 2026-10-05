# Inventory snapshots

The Google Sheet is the working inventory. These CSV files are dated public snapshots so changes can be reviewed in Git.

The current snapshot is [2026-10-05-inventory-r2.csv](2026-10-05-inventory-r2.csv), reconciled from the working sheet on October 5, 2026. Revision 2 adds the photographed Dell DW1810 wireless card, Toshiba KBG40ZNS128G 128 GB SSD, and empty 2.5-inch drive caddy. The earlier October 5 snapshot also remains unchanged. It contains 37 working-inventory columns and 19 unique item IDs. Earlier 20-column snapshots remain unchanged as historical baselines.

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

The October 5 snapshot updates PC-001 and GW-001 from subsequent project evidence and operator confirmations. PC-001 Windows 11 setup, current Windows updates, and Wi-Fi functionality are operator-confirmed; the corresponding Windows/Wi-Fi screenshots have not been archived. Two BIOS photographs were recovered, permanently redacted, and published with the [PC-001 device record](../docs/devices/PC-001.md). Other BIOS settings remain earlier transcriptions. Two additional redacted component photographs show the cooling shroud/empty caddy and wireless/SSD labels; published manufacturer capabilities are distinguished from observed tests. Ethernet ping/DNS and USG status screenshots are linked to the public [USG Revival](https://github.com/MReyna22/USG-Revival) evidence.

GW-001 revival and basic bench validation are complete. Throughput, sustained stability, inbound firewall enforcement, and backup restoration remain untested. Other device rows retain their prior status. Planned VM roles remain separate from actual Windows client use.

This snapshot is a reviewed copy of Inventory!A1:AK20, not an automatic synchronization. Update dates reflect when records were reconciled, rather than the original photo capture dates.

Power ratings and adapter associations are inventory observations. They do not replace checking voltage, polarity, connector fit, PoE mode, and available power before connection.

The snapshot keeps published model or regulatory-type labels, but excludes device-specific serial numbers, MAC addresses, Service Tags, QR codes, and private location fields.
