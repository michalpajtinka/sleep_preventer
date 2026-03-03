# Sleep Preventer

A lightweight PowerShell utility to prevent your monitor from turning off the display or entering sleep mode. This is particularly useful for media players or long-running processes that fail to correctly signal the OS to stay awake.

## 📝 Description

This script is meant to be cross-platform (although only Windows environment has been tested so far).

### Key Features:
* **Prevents Display Dimming/Sleep:** Keeps the monitor on indefinitely.
* **Prevents System Sleep:** Keeps the CPU active for background tasks.

---

## 🚀 How to Use

1. **Save the Script:** Save as `sleep_preventer.ps1`.
2. **Run with PowerShell:**
   * Right-click `sleep_preventer.ps1` and select **Run with PowerShell** or start the script directly from command line.
   * *Note:* If prompted by execution policies, try to run the following sequence of commands:
     ```powershell
     Set-ExecutionPolicy Bypass -Scope Process
     ".\\sleep_preventer.ps1"
     ```
     or run directly:
     ```powershell
     powershell.exe -ExecutionPolicy Bypass -File ".\\sleep_preventer.ps1"
     ```
3. **To Stop:** Simply close the PowerShell window or press `Ctrl + C` inside the console.

---


## 🛡️ Requirements

* **OS:** Windows7/8/10/11, Linux or Mac
* **PowerShell:** PowerShell 5.1+
* **Permissions:** Standard user.

---

## ⚠️ Disclaimer

This script will not keep your Slack/MS Teams/any other communicator status green!
This script will prevent your account from automatic locking, it is a serious security issue if you leave the device unguarded!
This script overrides your power settings while running; ensure your laptop is plugged into a power source if you plan to leave it running for extended periods to avoid battery drain.
