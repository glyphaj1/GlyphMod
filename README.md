   # 🌟 Glyph Mod – Roblox Experience Enhancer

A powerful yet simple batch-based tool designed to enhance your Roblox experience 
with just a few clicks. Built for both low-end and high-end PCs, Glyph Mod helps you 
unlock your FPS, apply performance-boosting tweaks, and manage settings through 
an easy-to-use terminal interface.

------------------------------
🚀 FEATURES
------------------------------
- Unlock Roblox’s default FPS cap (go beyond 60 FPS)
- System-Based Optimization Presets (from trash PCs to beasts)
- Lag Reduction Tweaks (lower latency, less stuttering)
- Client sided checkmark next to username
- Automatic backups of your Roblox settings before changes
- Works with both Bloxstrap and Fishstrap

------------------------------
🖥️ REQUIREMENTS
------------------------------
- Windows 10 or 11
- Roblox installed
- Administrator privileges
- Either Bloxstrap or Fishstrap must be installed and set up

------------------------------
📦 INSTALLATION & USAGE
------------------------------
1. Install Bloxstrap or Fishstrap if you haven’t already.
2. Download the `GlyphMod.bat` file from this project.
3. Right-click the file and select “Run as administrator”.
4. Select your Roblox bootstrapper (Bloxstrap or Fishstrap).
5. Choose an option from the menu:
6. The script:
   - Locates the ClientAppSettings file
   - Backs it up
   - Applies your chosen configuration
7. Launch Roblox through Bloxstrap/Fishstrap and enjoy smoother gameplay.

-------------------------------------------
⚡ OPTIMIZATION TIERS                    
-------------------------------------------
| Tier | Label           | Estimated FPS  |
|------|------------------|---------------|
| 1    | Trash PC         | ~80 FPS       |
| 2    | Below Average    | ~120 FPS      |
| 3    | Average          | ~170 FPS      |
| 4    | Above Average    | ~240 FPS      |
| 5    | Really Good      | ~400 FPS      |
| 6    | Insane           | ~1000 FPS     |

------------------------------
📂 File Locations
------------------------------

🔧 Modified Configuration File
Depending on your chosen bootstrapper, the script modifies the following file:

- For **Bloxstrap**:  
  `%USERPROFILE%\AppData\Local\Bloxstrap\Modifications\ClientSettings\ClientAppSettings.json`

- For **Fishstrap**:  
  `%USERPROFILE%\AppData\Local\Fishstrap\Modifications\ClientSettings\ClientAppSettings.json`

This file contains the FastFlags and client settings that control Roblox’s performance.

---
💾 Backup Directory
Before any changes are made, Glyph Mod automatically creates a backup of the original configuration.

Backups are stored in timestamped folders such as:

- `ClientSettingsBackup_FPSUnlock` - previous config before using FPS Unlock
- `ClientSettingsBackup_Optimizer` - previous config before using Optimizer
- `ClientSettingsBackup_Checkmark` - previous config before using Checkmark

📁 These folders are saved in the **same directory** as the `glyphmod.bat` file, making it easy to find and restore previous settings if needed.

------------------------------
🛡️ DISCLAIMER
------------------------------
This tool only applies changes on your local system. It does NOT hack or interact with 
Roblox servers in any way. It is 100% compliant with Roblox’s Terms of Service.

All changes are client-side only and fully reversible via automatic backups.

------------------------------
🙏 Thanks
------------------------------
⚠️ This entire tool is **highly dependent** on the use of **Bloxstrap** (https://bloxstraplabs.com/)
or **Fishstrap** (https://www.fishstrap.app/).

Without these tools, the modifications made by Glyph Mod will not be applied correctly. 
They provide the custom loader infrastructure that makes advanced Roblox optimization possible.

Massive thanks and appreciation to the developers of **Bloxstrap** and **Fishstrap** 
for making projects like this possible.

Please consider supporting their work too!

------------------------------
🙌 CREDITS
------------------------------
- Created by: @glyphaj (https://github.com/glyphaj1)
- Optimization configs from: My Repo (https://github.com/glyphaj1/RobloxOptimizer)

------------------------------
⭐ SUPPORT THIS PROJECT
------------------------------
- Star the GitHub repo if it helped you!
- Share it with a friend!
- Suggest improvements!
