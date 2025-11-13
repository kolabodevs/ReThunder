# **ReThunder**
A community-driven, open-source repository of **Thunderbolt / USB4** hardware design resources -\
created for sharing, learning, and collaborating on next-generation high-speed interface design.

---

## **Project Overview**
ReThunder aims to provide open design resources for hobbyists, makers, engineers, and researchers working with Thunderbolt or USB4 systems.\
The repository includes:
- Reference schematics  
- Layout guidelines  
- EDA symbols & footprints  
- And more…

---

## **Reference Documentation Availability**
Due to policy and legal restrictions, **official vendor documentation cannot be hosted directly on GitHub**.

Each folder under `docs/` contains a JSON file with **direct URLs** to relevant official documents.\
You may also browse them at: **https://static.kolabo.dev/pub/docs/**

Unofficial / community-created documents will be committed to the repository whenever possible.

---

## **Progress Tracker - Device-Side**

| Generation | Vendor | Model | Datasheet | EDA Files | Pinout & Constraint | Prototype | Notes |
|-----------|--------|--------|-----------|-----------|---------------------|-----------|-------|
| TBT5 / USB4 v2 | Intel | JHL9480 | – | Completed | Completed | Pending | Unverified drawings |
| TBT4 / USB4 | Intel | JHL9440 | – | Completed | Completed | Pending | Similar to JHL9480, 40 Gb/s |
| TBT4 / USB4 | ASMedia | ASM2464PDX | Available | – | In Queue | – | - |
| TBT4 / USB4 | ASMedia | ASM2464PD | Available | – | In Queue | – | Non-bifurcation version of PDX |
| USB4 | Realtek | RTS5490 | - | – | – | – | USB, DP Hub - No PCIe PHY |
| USB4 | VIA Labs | VL830 | Available | – | – | – | USB, DP Hub - No PCIe PHY |
| TBT4 / USB4 | Intel | JHL8440 | – | – | – | – | PCIe 3.0 x1 only |
| TBT3 | Intel | JHL7440 | Available | Completed | Completed | – | - |

---

## **Progress Tracker - Host-Side**

| Generation | Vendor | Model | Datasheet | EDA Files | Pinout & Constraint | Prototype | Notes |
|-----------|--------|--------|-----------|-----------|---------------------|-----------|-------|
| TBT5 / USB4 v2 | Intel | JHL9580 | – | – | – | – | - |
| TBT4 / USB4 | ASMedia | ASM4242 | – | – | In Queue | – | - |

---

## **Contributing**
Contributions of all types are welcome — schematics, documentation, footprints, tools, prototype results, and more.

To contribute:

1. Review the project’s contribution & licensing guidelines
2. Fork the repository
3. Create a new branch
4. Submit a Pull Request

> **Important:**\
> Pull requests **containing official documentation** cannot be accepted due to legal restrictions.\
> To share such materials, please contact me via email or Discord DM.

---

## **Disclaimer**
All materials in this repository are provided **for educational and research use only**.

For any **commercial**, **closed-source**, or **product-oriented** projects, please obtain **official reference designs and documentation** from the appropriate vendor.

This project is **not affiliated** with Intel, the USB Implementers Forum, the Thunderbolt organization, or any related entity.\
Thunderbolt and related marks are trademarks or registered trademarks of Intel Corporation.

USB4 is a registered trademark of the USB Implementers Forum.

All other trademarks belong to their respective owners.

---

## **License**
This project is licensed under the **GNU General Public License v3.0 (GPLv3)**.\
See the **[LICENSE](LICENSE)** file for full terms.
