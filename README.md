# Monster Hunter World: Iceborne Save Editor (PS4/PC)
A save editor for *Monster Hunter World: Iceborne* on PS4 and PC. Rewritten from the ground up in C# and WPF (.NET 4.7.2), this tool offers a comprehensive suite for managing character progression, inventory, equipment, and more across multiple save slots on both platforms.

## 🚀 Key Features

### 📂 Multi-Slot Management
The editor automatically detects and supports up to **three independent save slots** found in a standard MHW save file.
* **Platform Detection:** Automatically identifies whether the save file is from PS4 or PC and handles decryption/encryption accordingly.
* **Slot Selection:** Easily switch between different characters in the same save file.
* **Safety First:** Automatically generates a `.bak` backup of your save file before any write operation.

### 📈 General Stats (Tab 1)
Edit your core hunter and palico profile:
* **Hunter Info:** Name, Gender, Hunter Rank (HR) & Master Rank (MR) with XP values, and Playtime.
* **Palico Info:** Palico Name and XP.
* **Economy:** Set Zenny, Research Points, and Steamworks Fuel to any amount.
* **Decoration Unlock:** Toggle the Set Decorations unlock flag.
* **Steam ID:** View, copy, and paste your Steam ID directly (PC saves only).
* **Max Buttons:** One-click max buttons for all rank and currency fields.

### 🎒 Inventory Editor (Tab 2)
Manage every inventory container with a searchable item database:
* **Item Pouch** (24 slots) and **Ammo Pouch** (16 slots) for your active loadout.
* **Item Box** (200 slots), **Ammo Box** (100 slots), **Material Box** (1,250 slots), and **Deco Box** (500 slots).
* **Add / Remove / Max:** Search and add specific items, clear individual slots, or max all quantities in one click.
* **Bulk Fill:** Instantly populate entire boxes with all Consumables, Ammo, Materials, or Decorations at max quantity.

### ⚔️ Equipment Editor (Tab 3)
View and manage your full equipment box (2,500 slots):
* Browse all stored weapons, armor, charms, kinsects, tools, decorations, augments, advanced augments, awakened abilities, bowgun mods, and pendants.
* Search by name from the embedded CSV database for precise item selection.

### 🐱 Palico Equipment (Tab 4)
Dedicated editor for your Palico's gear:
* Manage Palico weapons, armor, and full equipment box entries (1,250 slots).

### 🔧 Miscellaneous (Tab 5)
One-click utility actions for your current slot:
* **Add All Endemic Life:** Set all endemic life collected counts to 999.
* **Unlock All Mantles:** Unlock the full set of mantles and boosters.
* **Upgrade All Mantles:** Apply all Mantle+ upgrades instantly.
* **Max Palico Gadget Proficiencies:** Set all gadget proficiency values to 99,999,999.

### 📋 Slot Manager (Tab 6)
Duplicate an entire character slot:
* Select any source and destination slot from a dropdown.
* Preview both slots before committing.
* Full in-memory copy with PS4 extra-block preservation — no data corruption.

### 🎽 Current Loadout (Tab 7)
View and edit what gear your hunter and palico currently have equipped:
* **Hunter Slots:** Weapon, Head, Chest, Arms, Waist, Legs, Charm, and Kinsect — populated live from your equipment box.
* **Tool Slots:** Tool 1 and Tool 2 — select any unlocked mantle or booster.
* **Palico Slots:** Palico Weapon, Head, Chest, and Gadget.

### 🔄 Converter (Tab 8)
Seamlessly convert save files between platforms without losing data:
* **PS4 → PC:** Transplant all three character slots from a PS4 save into a PC save wrapper.
* **PC → PS4:** Transplant all three character slots from a PC save into a PS4 save wrapper.
* Original files are never modified.

## 📝 How to Use
1. **Open:** Select your PS4 (`memory.dat`) or PC (`SAVEDATA1000`) save file.
2. **Select Slot:** Choose which of your three characters to edit.
3. **Edit:** Navigate the tabs to modify stats, inventory, equipment, loadout, or use the utility actions.
4. **Save:** Click **Save Changes** to write back to the file. PS4 saves are re-encrypted automatically.

---

## 🙏 Credits
This project wouldn't have been possible without the research and work of the following people:
* **[LEGENDFF](https://github.com/LEGENDFF/)** — Reference implementation for decrypting and encrypting PC save files.
* **[Marcus101RR](https://www.nexusmods.com/monsterhunterworld/users/58495681)** — Cheat table that helped map out the save file structure.
* **[Ahmed](https://github.com/alfizari)** — Cracked the second-layer encryption used in the save format.

---

*Created By ArsaModz*
