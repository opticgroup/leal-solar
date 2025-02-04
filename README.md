# Dormant Solar System Battery Backup Project

This repository documents the project to revive a **dormant solar power system** that was originally installed as a SolarCity system (later acquired by Tesla). The system has been inactive since the grid-tie inverter caught fire 5 years ago, and Tesla never resolved the issue.

The property currently faces a **$1,000/month power bill**, and the homeowner does **not** wish to expand the solar panel array at this time. The goal is to implement a battery backup solution using the existing solar installation while maintaining NEM 2.0 net metering status.

---

## Project Overview

The objectives of this project include:

- **Installing a new battery/charger/inverter system** in the detached garage.
- **Replacing the existing 200A main panel** in the home.
- **Automatically shedding high-load circuits** (e.g., laundry machine, electric hot water heater) during utility outages to conserve energy.
- **Integrating a Honda 3000 generator** (30A, 110V) via a dedicated inlet for supplemental power during prolonged outages.
- **Maintaining NEM 2.0 status:** All upgrades must preserve the current net metering agreement.

---

## Existing System

- **Solar Panels:**  
  - **42 × 200 W panels** (total nominal capacity: 8.4 kWp).  
  - *Note:* These panels are **10 years old**, which typically results in an efficiency decrease of approximately **5–10%** (operating at roughly 90–95% of their original capacity).

- **Configuration:**  
  - Panels are string-tied (high voltage) on the detached garage.
  - The array feeds into a **power cutoff switch**, then runs to the home's **200A main service panel**.

- **Current Status:**  
  - The original grid-tie inverter was destroyed by fire and has not been replaced, leaving the system dormant.

---

## Equipment and System Design

- **Battery/Charger/Inverter System:**  
  - **Battery Options:** Preferred battery option is **Victron**; however, Tesla, Franklin, or other brands will be evaluated based on **cost per amp-hour** and overall system compatibility.  
  - **Inverter:** Open to installer recommendations. A hybrid inverter capable of both grid-tie and battery backup operation is required to integrate the existing solar array and new battery system.

- **Load Shedding:**  
  - The system must automatically disable high-draw circuits (such as the laundry machine and electric hot water heater) during outages to ensure efficient use of backup power.

- **Generator Integration:**  
  - A **Honda 3000 generator** will be connected via a 30A, 110V inlet. The design should allow for manual start to supplement the battery during extended outages.

- **Main Panel Upgrade:**  
  - The existing 200A main service panel will be replaced/upgraded to accommodate the new hybrid system components.

- **No Additional Solar Panels:**  
  - At this time, the homeowner does **not** wish to install any additional solar panels.

- **NEM 2.0 Compliance:**  
  - All modifications must preserve the current NEM 2.0 net metering status.

---

## Installer Requirements

**Note to Installers:**  
Only installers who are **licensed, insured, and bonded** should submit a quote. Proof of licensing, insurance, and bonding must be provided at the time of quoting.

Installers are expected to:

- Provide detailed recommendations for the battery, inverter, and load-shedding configuration.
- Ensure the design meets local electrical codes and maintains NEM 2.0 compliance.
- Evaluate the system’s energy efficiency, taking into account the approximate 5–10% efficiency degradation of the 10-year-old panels.
- Deliver a comprehensive plan that integrates the existing solar infrastructure with the new backup components.

---

## Images

The following images, hosted in this repository, document the current setup. Click on the images for full-size versions.

![Solar Array Overview](https://github.com/opticgroup/leal-solar/raw/main/solar_array.jpg)
![Panel Close-Up](https://github.com/opticgroup/leal-solar/raw/main/panel_closeup.jpg)
![Wiring Diagram](https://github.com/opticgroup/leal-solar/raw/main/wiring_diagram.jpg)

*If the image filenames differ, please refer to the repository at [opticgroup/leal-solar](https://github.com/opticgroup/leal-solar) for the correct image file names.*

---

## Power Bill

- **Monthly Power Bill:** Approximately **$1,000 per month**.  
  This significant utility expense is a driving factor behind the decision to implement a battery backup system that leverages the existing solar array to reduce grid dependency.
