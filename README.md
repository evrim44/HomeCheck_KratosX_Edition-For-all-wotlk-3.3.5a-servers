# HomeCheck_KratosX_Edition !!FOR-ALL-Wotlk-3.3.5a-servers!!

> [!WARNING]
> **PLEASE NOTE:** You can use this version on any WOTLK 3.3.5a server that does not natively reset your cooldowns after a boss kill or a raid wipe.
> 
> If you want the **Whitemane Frostmourne Server Version** (with automatic DBM reset), you have to download the other version instead [here](https://github.com/evrim44/HomeCheck_KratosX_Edition-ONLY-for-Whitemane-Frostmourne-3.3.5a)

<img width="622" height="560" alt="WoWScrnShot_092326_210208" src="https://github.com/user-attachments/assets/dcd1dbb4-506c-4f65-ab61-702d3c06651d" />



Welcome to the KratosX Edition of HomeCheck. This version introduces crucial performance optimizations, automated tank filtering, dynamic talent tracking, and visual raid status indicators.

Features & Enhancements

# 1. Performance Loop Optimization
- The core background loop for range checks and frame updates has been optimized.
- The Benefit: This dramatically reduces CPU utilization and eliminates micro-stutters during heavy raid encounters while still offering precise tracking.

# 2. Dynamic Hammer of Justice (HoJ) Tracking
- Full support added for the *Improved Hammer of Justice
- 0/2 Points:  **60 Seconds**
- 1/2 Points:  **50 Seconds**
- 2/2 Points:  **40 Seconds**

# 3. Lay on Hands (LoH) Overhaul
- Dedicated Visibility Button: Added a dedicated toggle button specifically for *Improved Lay on Hands*, allowing users to filter and show only this specific tracker if desired.
- Fixed CD Timers & Glyph Support: Completely fixed the LoH cooldown calculation. The addon now natively tracks the Holy talent tree and properly includes the *Glyph of Lay on Hands* for accurate cooldown tracking.

<img width="1465" height="949" alt="1 1" src="https://github.com/user-attachments/assets/5fa767c9-9e82-458b-be8b-16da8c699f46" />


# 4. Dual Spec Talent Desync & Tank Cooldown Sync Button
- Automated Profile Sync: Added a brand-new custom action button to fully resolve talent caching issues caused by swapping specs via Dual Specialization system.
- The Benefit: Clicking this button forces an instant, hard reset of the local talent cache. It immediately synchronizes your personal *Lay on Hands* cooldown timer based on your newly activated talent tree and completely refreshes/resets all active "Tank-only" frames to prevent ghost bars or incorrect mitigation trackers after changing specs.

  <img width="892" height="600" alt="1 2" src="https://github.com/user-attachments/assets/fe3cc4cf-ca4e-420d-95e4-156c34f764d8" />


# 5. New Tank Cooldowns & "Tanks Only" Filtering
- Expanded Spell Database: Added full tracking support for essential defensive Tank cooldowns across multiple classes:
- **Warrior**: Shield Block
- **Druid**: Survival Instincts
- **Death Knight**: Unbreakable Armor
- Tanks Only Filter: Integrated these newly added defensive abilities, with the "Tanks only Toggle"


# 6.  Dead Player Indicators & Desaturation
- Raid Status Sync: Whenever a tracked raid member dies, their respective cooldown frame is automatically desaturated (grayed out) on your interface.
- Visual Anchor: A Skull icon is displayed directly before the name of the deceased player, giving you a immediate visual confirmation that the cooldown is currently unusable due to death of the Player.

<img width="805" height="523" alt="3" src="https://github.com/user-attachments/assets/ca6d237d-571d-41e3-b892-6a3d5ec985e9" />


# 6. Visuall changes

<img width="869" height="586" alt="2" src="https://github.com/user-attachments/assets/849b7b95-85be-494b-a890-6adf5306244b" />


## 🛠️ Installation

1. Download this repository as a `.zip` file.
2. Extract and only drag the "Homecheck" folder into your World of Warcraft directory: `Interface\AddOns\`.
3. Crucial: Ensure the folder is named exactly HomeCheck
4. If you had previous versions installed try deleting settings file: WTF\Account\\<ACCOUNT_NAME\>\SavedVariables\HomeCheck.lua

# Credits & License
Based on the original Author Homerocker *HomeCheck*  core functionality. Modified by Kratosx, optimized, and heavily expanded with advanced tracking mechanics and server-side fixes. All bundled libraries (Ace3, LibGroupTalents) belong to their respective authors.
