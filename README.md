# HST WINDOWS UTILITY

![HST Interface](./HST.png)

---

## 📋 Overview

HST WINDOWS OPTIMIZER is a **powerful Windows optimization script** designed to maximize system performance through registry tweaks, service management, and system cleanup. Perfect for gamers and power users seeking maximum hardware efficiency.

### ⚠️ WARNINGS

> **🛡️ Always create a restore point before using this tool**

> **☁️ OneDrive Removal**: Disable all OneDrive backup features before removal to prevent data loss

> **❗ If issues occur** run it again as administrator and check antivirus isn't blocking it

![BLOCK](./BLOCK.png)

---

## ✨ Features

### General Optimization
* **[1] Create Restore Point:** Safely creates a system restore point named 'HST-WINDOWS-OPTIMIZER'.
* **[2] Full Optimization:** Automatically runs a complete optimization sequence, including:
    * Creating a restore point.
    * Applying all registry and visual tweaks.
    * Optimizing task scheduler and services.
    * Disabling Windows Updates.
    * Adding the custom power plan.
    * Running a full system cleanup.

### Registry Optimizations (500+ Tweaks)
* **[3] Optimize Registry:** Applies a massive collection of registry tweaks focused on:
    * Performance (Hibernation, Fast Startup, Throttling).
    * Game Mode & DVR (Disables GameBar).
    * Network & Latency (System Responsiveness).
    * GPU & Power Latency settings.
    * NTFS, Keyboard, and Mouse optimizations.
    * Privacy (Disables Telemetry, Ad-ID, Activity History).
    * Search & Notification settings.
    * Disables Content Delivery Manager & Windows Spotlight.
* **[4] Lower Visual Effects:** Adjusts Windows settings for best performance (disables animations, transparency, etc.).
* **[5] Enable Dark Mode:** Switches both System and App modes to Dark.

### System Management
* **[6] Optimize Scheduler:** Disables over 60 unnecessary scheduled tasks (Telemetry, CEIP, Defrag, Defender scans, etc.).
* **[7] Disable Windows Updates:** Stops and disables Windows Update services (wuauserv, UsoSvc, BITS).
* **[8] Optimize Services:** Provides a menu to disable 100+ services deemed unnecessary for most users, categorized into:
    * Recommended (80 services)
    * Bluetooth (4 services)
    * Hyper-V (11 services)
    * Xbox (4 services)
    * All of the above (99+ services)
* **[9] Add Custom Powerplan:** Imports and activates a custom `HST.pow` power plan (requires the file to be in the same folder).

### Debloat
* **[10] Remove MS Apps:** Removes 48 pre-installed Microsoft apps (Clipchamp, News, Weather, GetHelp, Solitaire, People, etc.).
* **[11] Remove Xbox Apps:** Removes all Xbox-related apps (GameBar, Identity Provider, etc.).
* **[12] Remove Store Apps:** Removes the Microsoft Store and its purchase components.
* **[13] Remove Edge:** Forcefully removes Microsoft Edge by deleting its files and registry keys.
* **[14] Remove OneDrive:** Uninstalls and removes all traces of OneDrive.

### Cleanup
* **[15] Clean Temp Files:** Clears User temp, Windows temp, Prefetch, and Local AppData temp folders.
* **[16] Clean Cache Files:** Clears Chrome cache, Edge cache, and the Windows Update Download cache.
* **[17] Clean Event Logs:** Clears all Application, System, Security, and Setup event logs.
* **[18] Clean Power Plans:** Deletes the default Windows "Balanced," "Power saver," and "High performance" plans.
* **[19] Clean Recycle Bin:** Force-empties the Recycle Bin.
* **[20] Full Cleanup:** Runs all cleanup options (15-19) sequentially.