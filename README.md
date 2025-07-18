# USB PD Voltage and Cable Reform Proposal

## Overview
USB Power Delivery (PD) is a revolutionary standard, but some design choices—especially the omission of 12V as a mandatory step and the inclusion of 15V—deserve reconsideration. This proposal outlines three key reforms to improve usability, safety, and market alignment.

## Proposal Summary
- ✅ **Standardize 12V as a mandatory PD voltage step**
- ❌ **Deprecate 15V due to limited real-world adoption**
- 🔋 **Introduce a “PD Power-Only” Type-C cable specification with clear visual marking**

## Why 12V Matters
- Widely used in routers, HDDs, monitors, LED lighting, and automotive devices.
- Compatible with 3A non-E-Marker cables (up to 36W).
- Already supported by many PD chargers via optional profiles—should be standardized.

## Why 15V Is Problematic
- Rarely used in actual devices (especially in Japan).
- Falls between 12V and 20V with no clear advantage.
- Adds confusion and complexity to PD charger design.

## PD Power-Only Cable Specification
- Minimal wiring: VBUS, GND, CC only.
- No data lines (D+/D-, USB 3.x, SBU, VCONN).
- Visual marking: “PD Only” icon, colored connector, or printed label.
- Benefits: lower cost, improved safety, clear user expectations.

## Impact and Benefits

| Reform                     | Benefit                                      |
|---------------------------|----------------------------------------------|
| 12V Standardization       | Broader device compatibility, fewer AC adapters |
| 15V Deprecation           | Simplified PD charger design, reduced confusion |
| PD Power-Only Cable       | Lower cost, safer charging, clearer UX         |

## Call to Action
USB-IF and device manufacturers should consider these reforms to align PD with real-world needs.  
Community feedback and collaboration welcome.
