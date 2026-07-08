# Week 2 — IP Addressing (FLSM & VLSM) and VLAN Configuration

**Institute:** IT-SIMPLERA Institute
**Program:** Network Administration Internship
**Submitted By:** Afaq Tahir
**REG NO:** NETB01-8303
**Submission Date:** 10 July 2026

## What This Week Covers
- Fixed Length Subnet Masking (FLSM) — 10 solved problems
- Variable Length Subnet Masking (VLSM) — 5 design scenarios
- VLAN Configuration on Cisco switches
- Access port and trunk port setup
- Network verification using show vlan brief and show interfaces trunk

## Tools Used
- Cisco Packet Tracer
- GNS3
- Solar-PuTTY

## Files in This Folder
| File | Description |
|---|---|
| Report.pdf | Full weekly report with FLSM, VLSM, VLAN theory and implementation |
| Cisco_Packet_Tracer/ | Packet Tracer topology with VLAN configuration |
| GNS3_Project.zip | GNS3 project file with VLAN topology |
| Screenshots/ | All verification screenshots |

## VLAN Setup Summary
| Device | VLAN | IP Address |
|---|---|---|
| PC1 | VLAN 10 (HR) | 192.168.10.1 |
| PC2 | VLAN 10 (HR) | 192.168.10.2 |
| PC3 | VLAN 20 (IT) | 192.168.20.1 |
| PC4 | VLAN 20 (IT) | 192.168.20.2 |

## Verification Results
- show vlan brief — confirmed VLAN 10 and VLAN 20 created with correct port assignments
- show interfaces trunk — confirmed trunk link active between switches
- Ping same VLAN (PC1 to PC2) — SUCCESS
- Ping different VLAN (PC1 to PC3) — FAILED (confirms VLAN isolation working)
