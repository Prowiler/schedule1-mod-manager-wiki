# Mod Manager & Phone App

Welcome to the **Mod Manager & Phone App** repository for the game **Schedule I**! 🎮

This repository primarily hosts the **Developer Documentation Wiki** for mod creators looking to integrate their mods with the **Mod Manager & Phone App**.

---

## 📚 Documentation & Guides (For Mod Developers)

All detailed documentation, including integration steps, handling dynamic settings updates, API details, and known issues, is available in the **[GitHub Wiki](../../wiki)**.

### 👉 **[Visit the Developer Wiki](../../wiki)**

The Wiki covers essential information for ensuring your mod's settings are correctly displayed and configurable using this tool.

---

## 🌟 Core Features
The Mod Manager & Phone App provides:
- **Main Menu Management**:
    - **Mods Tab**: Enable/disable mods (.dll <-> .dll.disabled). *Requires game restart.*
    - **Config Tab**: View and configure settings for **all** registered mods, or filter by a specific mod, directly from the main menu. Includes Save/Reset functionality.
- **In-Game Phone App**: A dedicated phone app interface ("Settings") for users to configure compatible mod settings interactively *during* gameplay.
- **Expanded Settings Support**: Includes UI controls for common types like Booleans, Numbers, Strings, KeyCodes, Enums (Dropdowns), and Colors (Sliders/Input/Preview).
- **Separate Save Events**: Distinct events are fired when saving from the Phone App vs. the Main Menu Config panel, allowing mods to react accordingly.
- **Dynamic Update Support**: An event system allows mods to apply setting changes live without requiring a game restart (if implemented by the mod).

---

## 📜 License
This mod is distributed under a **custom license**. Please review the [LICENSE.md](LICENSE.md) file for full terms and conditions.

---

## 🔗 Quick Links
- **[Developer Wiki](../../wiki)**: Essential for mod integration.
- **[Nexus Mods Page](https://www.nexusmods.com/schedule1/mods/397)**: Download the mod, user discussions, and official releases.
- **[LICENSE](LICENSE.md)**: Usage terms.

For user support, feedback, or bug reports related to the Mod Manager & Phone App itself, please use the [Nexus Mods Page](https://www.nexusmods.com/schedule1/mods/397). For issues related to the developer documentation or integration API, feel free to open an issue in this repository.

Happy modding! 🚀
