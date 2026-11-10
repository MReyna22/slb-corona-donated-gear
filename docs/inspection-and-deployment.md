# Inspection and deployment

Use one record per item ID. Start by observing and documenting the device. Decide on a reset after recording the baseline and any configuration that needs to be preserved.

## Current checkpoints — November 10, 2026

| Device | Verified or documented | Remaining before next setup/deployment milestone |
|---|---|---|
| PC-001 | Initial Windows setup and separate Ethernet/Wi-Fi basic checks | Workload planning and any explicitly selected extended checks |
| PC-002 | Startup/BIOS access, hardware baseline, CPU and memory quick passes, five storage passes / one Not Applicable | Supported OS selection, authorized erase, installation and networking checks |
| PC-003 | Ubuntu installed on encrypted internal NVMe; NVIDIA driver/VRAM and zero failed system units recorded; Hermes setup complete; Windows recovery retained as history | Hermes provider/model, first response and tool validation; suspend/remote access; Checkmk/Obsidian; firmware and Linux network/peripheral checks |
| GW-001 | OpenWrt revival and basic wired validation | Wider deployment remains a separate project milestone |

A diagnostic pass applies only to the shown test selections. A firmware-reported successful wipe is recorded as that result, not independent forensic validation. A Windows Update success display does not establish the latest OEM BIOS or every driver version. A detected network adapter is not itself a network functionality test.

## Inspection checklist

- Confirm the item ID, model, visible condition, ports, and included accessories.
- Verify the correct power source and compatibility before connecting it.
- Record a power-on result.
- For computers, record CPU, RAM, storage, BIOS, graphics, network interfaces, and virtualization support.
- For network devices, record firmware, adoption or management state, port operation, and support status.
- Record faults, missing accessories, and unresolved questions.

## Reset and setup checklist

- Record whether a reset is needed and why.
- Preserve needed configuration or recovery information privately before resetting.
- Record the reset procedure and result when performed.
- Install or configure the chosen operating system or management software.
- Record configuration changes without publishing credentials or private network details.
- Test the intended function and document the result.
- Update Actual Use, related project, and the inventory date after deployment.

## Device record template

Copy this template into a separate Markdown file named for the item ID when inspection begins.

| Field | Entry |
|---|---|
| Item ID | |
| Inspection date | |
| Model | |
| Physical condition | |
| Included accessories | |
| Power verification | |
| Installed hardware or firmware | |
| Power-on result | |
| Test objective and procedure | |
| Expected result | |
| Observed result and pass/fail status | |
| Limitations or failed tests | |
| Reset needed and reason | |
| Reset performed and result | |
| Setup and configuration | |
| Configuration decisions and rationale | |
| Recovery or rollback plan (sanitized) | |
| Planned use | |
| Actual use | |
| Related project | |
| Sanitized evidence links | |
| Open issues and next step | |

Record what happened, including failed tests. Leave unknown fields open rather than treating them as successful checks.


