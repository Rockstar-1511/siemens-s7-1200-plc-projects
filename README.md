# Siemens S7-1200 PLC and Ignition SCADA Projects

Self-directed training projects built with a **Siemens S7-1200 PLC (TIA Portal)**, simulated in **Factory I/O**, and integrated with **Ignition SCADA**. All plant behavior is **simulated**; no physical plant hardware was used.

| # | Project | Focus |
|---|---------|-------|
| 1 | [AC Motor Control](01-ac-motor-control) | Start/stop, jog, seal-in, interlocks, overload trip, fault latch/reset |
| 2 | [Box-Sorting Line](02-box-sorting-line) | Sensor-based sequencing, conveyor control, diverter actuation |
| 3 | [Paint-Production Process](03-paint-production) | Batch sequencing, valve/pump control, level monitoring, timers |
| 4 | [Ignition SCADA Integration](04-ignition-scada-integration) | Tags, HMI screens, alarms, trends |

## Tools
- Siemens TIA Portal, S7-1200 (ladder logic)
- Factory I/O (simulated plant)
- Ignition SCADA (supervisory control and HMI)

## Repository layout
Each project folder contains `README.md` (overview, I/O list, sequence), `tia-project/` (TIA Portal archive) and `screenshots/` (ladder, simulation, HMI).

## Disclaimer
Training projects in simulation. Not validated for use on real equipment.
