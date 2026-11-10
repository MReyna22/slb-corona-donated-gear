# Inventory snapshots

The Google Sheet is the working inventory. These CSV files are dated public snapshots so changes can be reviewed in Git.

The current snapshot is [2026-11-10-inventory-r2.csv](2026-11-10-inventory-r2.csv), reconciled from the working sheet on November 10, 2026. It records PC-003's Ubuntu installation on encrypted internal storage, NVIDIA and system-unit checks, Hermes local responses, command/file reads, verified workspace and Telegram gateway connection; Checkmk and Obsidian remain next. PC-001/PC-002 joint roles remain undecided. It preserves the earlier PC-001/GW-001 work and other device records. There are 19 unique item IDs. Earlier snapshots remain unchanged.

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

GW-001 revival and basic bench validation are complete. Throughput, sustained stability, inbound firewall enforcement and backup restoration remain untested.

PC-002's [device record](../docs/devices/PC-002.md) now documents the i5-4590T, BIOS-recognized 8192 MB / displayed 1600 MHz memory bus speed, BIOS FBKTB9AUS and baseline settings. CPU Quick and Memory Quick passed. The selected storage suite shows five passes and one Not Applicable result. These are not extended memory/stability tests or a full disk surface scan. Wipe authorization is recorded; erase, fresh OS setup and networking tests remain pending.

PC-003's [device record](../docs/devices/PC-003.md) now separates the current Ubuntu/Hermes setup from earlier Windows recovery. Internal-root/LUKS and NVIDIA output, plus a zero-failed-system-unit result, were reviewed privately. Updates/reboot and resolution of the device-code permission error are operator-reported. Hermes now responds locally, runs hostname/pwd and reads project files from its verified workspace. The default profile displays `gpt-6-sol`; actual provider identity is not independently shown. Gateway output shows an active/enabled service connected to Telegram with linger enabled; usability through Telegram is operator-reported. A fresh Telegram workspace test and full contents of agent-reported note edits remain unverified. Checkmk and Obsidian are next; separate host remote access, suspend settings, firmware maintenance and remaining Linux network/peripheral checks are open. Optional Hermes tuning is deferred. No local-model runtime was selected. The new originals remain private; the public record contains reviewed summaries.

Power ratings and adapter associations remain inventory observations. Successful startup does not revalidate every power-label association. Other device rows retain their earlier status; proposed lab roles remain separate from actual inspection/setup use.

This snapshot is a reviewed copy of the working Inventory tab, not an automatic synchronization. Update dates reflect when records were reconciled, rather than the original photo capture dates.

Power ratings and adapter associations are inventory observations. They do not replace checking voltage, polarity, connector fit, PoE mode, and available power before connection.

The snapshot keeps model and regulatory-type labels, but excludes full serial numbers, MAC addresses, Service Tags and private location fields. Public evidence fully hides unrelated private information. A useful device identifier may retain at most roughly its last quarter; credentials, account/network details, UUIDs and identifying QR/barcodes are fully hidden.

