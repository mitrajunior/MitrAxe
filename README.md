<p align="center">
  <img src="Demo/default_dark.png" width="600">
</p>


# Mitr4xe — Custom NerdAxe Build

**Mitr4xe** is a customized fork of the official **NerdAxe** project, designed to expand configuration flexibility directly through the WebUI.  
This fork does **not** replace the original NerdAxe — it builds upon it, adding features that improve usability and dynamic configuration.

---

## 📌 Official NerdAxe Repository
The original and official project can be found here:

👉 **https://github.com/BitMaker-hub/NerdAxe**

All base functionality, project architecture, and design belong to the NerdAxe team.

---

# 🔧 Key Features Added in Mitr4xe

These are the **exclusive enhancements** provided by the Mitr4xe fork — features that the original NerdAxe does **not** include:

---

🟦 1. Board Model Selection via WebUI

Mitr4xe allows the user to:

Select the board model directly through the WebUI

Store the selected model persistently in NVS

Automatically adjust firmware behavior based on the chosen board

💡 In the official NerdAxe, board selection is only possible at compile time.

🟦 2. Static IP Configuration via WebUI

(Added because this feature does not exist in the official NerdAxe)

Full network configuration is now available directly in the WebUI:

Set a static IP address

Subnet mask

Gateway

DNS

All settings are saved in NVS and applied immediately — no recompilation required

💡 The official NerdAxe does not support static IP configuration via WebUI.

🟦 3. Manual Chip Type & Quantity Configuration

This fork allows users to:

Manually define the chip type

Choose the number of chips being used

Save and update both values in NVS

Dynamically adjust hardware logic, system tasks, and UI based on the selected quantity

💡 The official NerdAxe performs automatic detection only and does not allow manual configuration.

🟦 4. Improved Wi-Fi Auto-Reconnect System

New and enhanced Wi-Fi reconnection logic:

Much more stable automatic reconnection

Safe reentry into the boot flow

Better detection of network loss

More consistent behavior when switching between manual Wi-Fi / AP mode / SmartConfig

💡 More robust than the default reconnection system used in the official NerdAxe.

🟦 5. Enhanced Boot Behavior

The boot process has been reworked to match all new features introduced in this fork:

Boot is now optimized by taking into account:

The selected board model

The configured chip type and quantity

The active network mode and IP configuration

This results in:

A more predictable and organized initialization process

Fixes to flows that previously could behave inconsistently after changes made through the WebUI

💡 These improvements make Mitr4xe more dynamic than the original NerdAxe, which relies on fixed compile-time configurations.

🔍 Summary of Differences (NerdAxe vs. Mitr4xe)
Feature	NerdAxe (Official)	Mitr4xe (This Fork)
Select board model	❌ Compile-time only	✅ WebUI selectable
Configure static IP	❌ Not available	✅ WebUI configurable
Manual chip type/quantity setup	❌ Not available	✅ WebUI configurable
Wi-Fi auto-reconnect	🔸 Basic	✅ Advanced reconnect system
Boot behavior	🔸 Default	✅ Adjusted & optimized
Core system, UI, tasks, drivers	✔ Included	✔ Inherited & extended


# 🖥️ User Interface Screenshots

![Init Screen](https://raw.githubusercontent.com/mitrajunior/MitrAxe/main/Demo/initscreen2.png)
![Mining Screen](https://raw.githubusercontent.com/mitrajunior/MitrAxe/main/Demo/miningscreen2.png)
![Portal Screen](https://raw.githubusercontent.com/mitrajunior/MitrAxe/main/Demo/portalscreen.png)
![Settings Screen](https://raw.githubusercontent.com/mitrajunior/MitrAxe/main/Demo/settingsscreen.png)
![Splash Screen](https://raw.githubusercontent.com/mitrajunior/MitrAxe/main/Demo/splashscreen2.png)

![WebUI](https://raw.githubusercontent.com/mitrajunior/MitrAxe/main/Demo/Screenshot_20251122-213346.png)
![Web_UI](https://raw.githubusercontent.com/mitrajunior/MitrAxe/main/Demo/Screenshot_20251122-213411.png)




# 📂 Coming Soon.

