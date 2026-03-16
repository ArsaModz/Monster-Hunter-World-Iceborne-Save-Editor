# Monster Hunter World: Iceborne Save Editor (PS4/PC)
A save editor for *Monster Hunter World: Iceborne* on PS4 and PC. Built with Python and PyQt6, this tool offers a comprehensive suite for managing character progression, currency, and entire item boxes across multiple save slots.
## 🚀 Key Features
### 📂 Multi-Slot Management
The editor automatically detects and supports up to **three independent save slots** found in a standard MHW save file.
* **Platform Detection:** Automatically identifies whether the save file is from PS4 or PC and handles decryption accordingly.
* **Slot Selection:** Easily switch between different characters in the same save file.
* **Character Info:** View and edit Character Name, Palico Name, Gender, and Playtime.
### 📈 Hunter Progression
Skip the grind by directly modifying your rank and resources:
* **Rank Control:** Edit Hunter Rank (HR) and Master Rank (MR) along with their respective XP values.
* **Economy:** Set Zenny, Research Points, and Steamworks Fuel to your desired amounts.
### 🎒 Comprehensive Box Editor
Manage every aspect of your inventory with a built-in search system linked to external CSV databases:
* **Item & Ammo Pouch:** Modify your active loadout on the fly.
* **Vault Management:** Full access to the Item Box, Material Box, and Decoration Box.
* **Searchable Database:** Use the **ItemSearchDialog** to quickly find specific IDs for items, armor, and weapons from the massive Iceborne library.
## 🖥 User Interface
The application provides a clean, native-feeling interface optimized for data entry:
* **Tabbed Navigation:** Categorized sections for Character Stats, Pouches, and various Boxes.
* **Dynamic Loading:** Tables populate in real-time based on the selected save slot.
* **Safety First:** Automatically generates a `.bak` backup of your save file before any write operation.
## 📝 How to Use
1. **Open:** Select your PS4 or PC save file (`.dat` for PS4, `SAVEDATA1000` for PC).
2. **Select Slot:** Choose which of your three characters you wish to edit.
3. **Search & Edit:** Use the search dialogs to swap items or simply adjust the quantities in the tables.
4. **Save:** Apply changes to commit them to the file. PS4 saves will be re-encrypted automatically if they were originally encrypted on disk.

---

## 🙏 Credits
This project wouldn't have been possible without the research and work of the following people:
* **LEGENDFF** — Reference implementation for decrypting and encrypting PC save files.
* **Marcus101RR** — Cheat table that helped map out the save file structure.
* **Ahmed** — Cracked the second-layer encryption used in the save format.

---

*Created by ArsaModz*
