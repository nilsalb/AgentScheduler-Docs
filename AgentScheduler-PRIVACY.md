# AgentScheduler — Privacy Policy

**Effective date:** April 16, 2026  
**Developer:** Nils Albertsen  
**App:** AgentScheduler (macOS)

---

## Summary

AgentScheduler does not collect, transmit, store, or share any personal data. All functionality runs entirely on your device.

---

## Data We Collect

**None.**

AgentScheduler does not collect any data — not analytics, not crash reports, not usage statistics, not identifiers of any kind.

---

## Data Stored on Your Device

AgentScheduler stores one preference locally on your Mac using the standard macOS `UserDefaults` mechanism:

| Setting | What it stores | Where |
|---|---|---|
| "Keep Mac awake after execution" | A single boolean (`true` or `false`) | `UserDefaults` (local, on-device only) |

This value never leaves your device and is not accessible to anyone other than you.

---

## Permissions Used

### Accessibility Access
AgentScheduler requests Accessibility permission solely to simulate the Enter key via the macOS `CGEventPost` API. This is the app's core feature: pressing a key at a scheduled time.

- The app does **not** read, record, or transmit any keyboard input, screen content, or accessibility data.
- The permission is used only to send a single synthetic keystroke (the Return key) at the time you schedule.

### Notifications
AgentScheduler requests permission to send local notifications to confirm that the scheduled action has executed. Notifications are generated entirely on-device and are never sent to a server.

---

## Network Access

AgentScheduler makes **no network requests** of any kind. The app has no server, no backend, no analytics endpoint, and no third-party SDKs.

---

## Third-Party Services

None. AgentScheduler uses no third-party libraries, SDKs, or services.

---

## Children's Privacy

AgentScheduler does not collect any data from anyone, including children under 13. There is nothing to collect.

---

## Changes to This Policy

If this policy ever changes, the updated version will be distributed with the app update and the effective date above will be revised.

---

## Contact

Questions about privacy?  
**Email:** nilsalb@gmail.com
