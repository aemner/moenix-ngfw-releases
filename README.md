# Moenix NGFW Standalone — Releases & Images

Official binary releases, offline `.tar.gz` software update packages, and bare-metal installer ISOs for **Moenix NGFW Standalone** (Debian 13 / Trixie).

> **Note:** This repository hosts **compiled release artifacts only** (no source tree).

## Download & Upgrade

1. **Fresh Bare-Metal / VM Install:** Download the latest `.iso` + `.sha256` from [Releases](../../releases), verify `sha256sum`, and boot/install on x86_64 hardware or Proxmox/KVM.
2. **Offline / 1-Click Firewall Upgrade:**
   - **1-Click Online Check (via Releases):** In the Web GUI go to **System → General Settings → Software Updates → Release Server**, click **Check for Updates**, then **Download & Install**.
   - **Air-Gapped Offline Upload:** Download `moenix-ngfw-<version>-update.tar.gz` and `.sha256`, then upload it under **Offline Package (.tar.gz)**.
