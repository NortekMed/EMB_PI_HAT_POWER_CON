---
applyTo: '**'
---

# Memory Segments by Topic

## 1. Git & Project Setup
- Analyzed project folder; initial commit created, only tracking source files and omitting generated, backup, and temp files using a tailored KiCad .gitignore.
- Tagged v030226.
- Created and pushed to new GitHub repo NortekMed/EMB_PI_HAT_POWER_CON. Branches: master, RTC3231.

## 2. RTC Components (Hardware & Software)
- Explained that the M41T0M6 RTC is kernel-supported via rtc-m41t80; integration on Pi3 is simple:
  - Enable I2C, use overlay 'dtoverlay=i2c-rtc,m41t80' in /boot/config.txt, connect RTC, reboot.
- M41T0M6 support is built into modern Linux/Raspberry Pi OS; no extra driver needed beyond enabling overlay and I2C.
- Addition of the M41T0M6 to the KiCad project was committed and pushed to branch RTC3231.

## 3. Workflow & Command Guidance
- Provided precise shell/git commands for git auth, repo creation, branches, and tagging.
- Advised on GitHub CLI login/token clarification.
- Covered steps for pushing commits, managing .gitignore, and integrating new components in a collaborative workflow.

---
# Instructions
- To suppress or forget one segment (topic), specify its topic title (e.g., "suppress RTC Components (Hardware & Software)").
- Memory can be updated or expanded in this file as the project or discussion evolves.
