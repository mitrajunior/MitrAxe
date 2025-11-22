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

## 🟦 1. Board Model Selection via WebUI
Mitr4xe introduces a configurable system that allows users to:

- Select the **board model** directly from the WebUI  
- Store the selected board in NVS permanently  
- Dynamically adjust firmware behavior based on the chosen board  

💡 *In the official NerdAxe, board selection is compile-time only.*

---

## 🟦 2. Static IP Configuration via WebUI
Mitr4xe includes fully dynamic network configuration:

- Set a **static IP address**
- Define **subnet mask**
- Define **gateway**
- Configure **DNS**
- All configurable directly through the WebUI

No firmware recompilation required.

💡 *The official NerdAxe does not provide advanced network configuration via WebUI.*

---

## 🟦 3. Manual Configuration of Chip **Quantity** via WebUI
This fork lets users specify:

- The **number of chips** being used  
- Set and change the amount through WebUI  
- Store the configuration in NVS  
- Dynamically affect hardware logic, system tasks, and UI  

💡 *NerdAxe performs automatic chip handling only; it does not allow manual quantity selection.*

---

# 🔍 Summary of Differences (NerdAxe vs. Mitr4xe)

| Feature | NerdAxe (Official) | Mitr4xe (This Fork) |
|--------|----------------------|---------------------|
| Select board model | ❌ Compile-time only | ✅ WebUI selectable |
| Configure static IP | ❌ Not available | ✅ WebUI configurable |
| Set chip **quantity** | ❌ Automatic only | ✅ WebUI configurable |
| Core system, UI, tasks, drivers | ✔ Included | ✔ Inherited & extended |

---

# 📂 Project Structure Overview

