# Desk display firmware (OTA binaries)

This public repo holds **only the compiled firmware (`firmware.bin`) + `version.txt`** for the warehouse desk display, published automatically by CI.

- The device checks the **latest release** here and self-updates over WiFi (no cable).
- **Source code is NOT here** — it lives in a private repo. These binaries contain no secrets (WiFi/API credentials live in the device NVS, not in the firmware).
