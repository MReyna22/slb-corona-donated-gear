# Inventory snapshots

The Google Sheet is the working inventory. These CSV files are dated public snapshots so changes can be reviewed in Git.

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

This baseline combines the AP inventory and the equipment recorded in the Identify Device Capabilities chat. Model names, label text, and proposed uses are retained from those records. Original photos and installed computer specifications were not rechecked when preparing this snapshot.

Power ratings and adapter associations are inventory observations. They do not replace checking voltage, polarity, connector fit, PoE mode, and available power before connection.

The snapshot keeps published model or regulatory-type labels, but excludes device-specific serial numbers, MAC addresses, Service Tags, QR codes, and private location fields.

