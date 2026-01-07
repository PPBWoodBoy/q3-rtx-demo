# Quake 3 Arena RTX Mod Demo

<div align="center">
  <img src="mod_logo_demo.png" alt="Logo Demo">
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Engine-Quake3e-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/RTX%20Remix-1.2.4-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Textures-Upscaled%20%2B%20Remastered-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Demo-yellow?style=for-the-badge" />
</p>

This project is a visual enhancement mod for **Quake 3 Arena**, created using  
**RTX Remix 1.2.4**, **Quake3e**, **imgupscaler.ai**, and **Photopea**.  
It brings modern PBR-style textures and ray-tracing compatible materials to the game while keeping original gameplay completely intact.

**Intended for Singleplayer gameplay!**

**Made by: WoodBoy (aka PolyPlayBox)**

> **Note:** Only textures are remastered — **no models** have been modified yet.

> [!CAUTION]
> I dont take any responsibility for any hardware damage, VAC bans, any other problems that this mod might cause

> [!CAUTION]
> Please download the mod files from [ModDB](https://www.moddb.com/mods/quake-3-arena-rtx-remix-mod-demo/downloads)
> or from the official github [release](https://github.com/PPBWoodBoy/q3-rtx-demo/releases/tag/rtx%2Cquake3%2Cremix%2Cmod)

---

## 🔥 Remastered Content

### 🗺️ Maps
| Map   | Status |
|-------|--------|
| Q3DM1 | ✔️ Remastered Textures / Custom Lighting |
| Q3DM6 | ✔️ Remastered Textures / Custom Lighting |
| Q3DM10 | ✔️ Remastered Textures / Custom Lighting |

### 🧑‍🚀 Player Textures
| Player | Status |
|--------|--------|
| Doom   | ✔️ |
| Ranger | ✔️ |
| Gorre  | ✔️ |
| Slash  | ✔️ |
| Ranger | ✔️ |
| Sarge | ✔️ |
| Orbb | ✔️ |
| Hossman | ✔️ |
| Daemia | ✔️ |
| Bitterman | ✔️ |
| Grunt | ✔️ |
| TankJr | ✔️ |
| Angel | ✔️ |
| Wrack | ✔️ |


### 🔫 Weapon Textures
| Weapon          | Status |
|-----------------|--------|
| Gauntlet        | ✔️ |
| Machinegun      | ✔️ |
| Shotgun         | ✔️ |
| Rocket Launcher | ✔️ |
| Railgun         | ✔️ |
| Plasmagun       | ✔️ |
| Lightninggun       | ✔️ |

---

## 📥 Installation TL;DR

- **Download:** https://github.com/NVIDIAGameWorks/rtx-remix/releases/tag/remix-1.2.4
  (**remix-1.2.4-release.zip**)
- **Download:** https://github.com/whisperglen/QindieGL/releases/tag/v1.2.0a 
(**QindieGL.zip**, only the `opengl32.dll` is needed)
- **Download:** https://github.com/whisperglen/Quake3e/releases/tag/v1.1 
(**quake3e-windows-msvc-x86.zip**, only the `quake3e.exe` is needed)

- Copy the `quake3e.exe` into your base Quake3 (Q3) folder (example: C:/Program Files/Quake 3 Arena)
- Copy the `opengl32.dll` into your base Q3 folder
- Copy the `QindieGL.ini` into your base Q3 folder
- Copy the `rtx.conf`into your base Q3 folder
- Copy the RTX Remix 1.2.4 runtime into your base Q3 folder:
	- .trex folder
	- d3d8to9.dll
	- d3d9.dll
	- NvRemixLauncher32.exe
- Copy the `autoexec.cfg` into the baseq3 folder (example: C:/Program Files/Quake 3 Arena/baseq3)
- Copy the `q3rtx.pk3` into the baseq3 folder (example: C:/Program Files/Quake 3 Arena/baseq3)
- Run the `quake3e.exe` once and make sure RTX Remix hooks (Message ingame on the top left corner)
- Exit the game
- Copy the whole `Q3RTXDemo` folder into the `rtx-remix/mods` folder in your base Q3 folder (so that the `mod.usda` and the materials & assets folder are in the  `rtx-remix/mods/Q3RTXDemo` folder)
- Have fun

> [!CAUTION]
> If you happen to change a setting and cant get it solved
> here is a list of all ingame settings required to work with RTX:
> - Graphics Settings: Lighting: Vertex
> - Graphics Settings: GL extensions: Off
> - Graphics Settings: Texture detail: Highest (100%)
> - Game Options: Dynamic Lights: Off
> - Game Options: High Quality Sky: On

### 🛠️ Change the screen resolution (optional)

Open:`baseq3/autoexec.cfg`

Look for the following lines:

r_customWidth "xxxx"

r_customHeight "xxxx"

Replace `xxxx` with your resolution.  
The default included in this mod is:

r_customWidth **"1920"**
r_customHeight **"1080"**


---

### ❗ DO NOT CHANGE ANY IN-GAME GRAPHIC SETTINGS

This is extremely important.

RTX Remix and Quake3e require specific settings already included in the config.  
Changing graphics or game options can break:

- lighting  
- reflections  
- material PBR properties  
- texture assignments  

Just launch and play.

> [!CAUTION]
> If you happen to change a setting and cant get it solved
> here is a list of all ingame settings required to work with RTX:
> - Graphics Settings: Lighting: Vertex
> - Graphics Settings: GL extensions: Off
> - Graphics Settings: Texture detail: Highest (100%)
> - Game Options: Dynamic Lights: Off
> - Game Options: High Quality Sky: On

---

## 🛠 Tools Used

### Engines & Rendering
- **NVIDIA RTX Remix 1.2.4**
- **Quake3e (latest build)**
- **opengl32.dll**

### Texture Workflow
- **imgupscaler.ai** — AI enhancement and detail restoration  
- **Upscayl** — AI enhancement and detail restoration  
- **Photopea** — manual cleanup, corrections, and texture prep  

---

## 📌 Known Limitations

- 3D objects / Models have not been remastered yet
- Textures dont have animations (mostly)
- Some textures might not be remastered or have strange roughness effects
- RTX might not hook / work if a different: Quake3e.exe, opengl32.dll or RTX Remix version is used
- UI / HUD textures are not remastered yet
- Texture Quality slider must be maxed (100%) otherwise the enhanced textures wont load!

---

## 🧭 Roadmap

- Remaster all Q3 maps / textures
- High-poly model replacements  
- Remaster UI/HUD textures 

---

## 📄 Credits

**Textures & Materials**  
WoodBoy (PolyPlayBox on YouTube)

**Tools**  
- RTX Remix  
- Quake3e  
- imgupscaler.ai  
- Upscayl
- Photopea  

**Original Game**  
© id Software — Quake III Arena (1999)

---

## 🔗 Required External Tools

This mod uses the following tools, which you must download separately:

> [!CAUTION]
> Using any different version of the following Tools is not supported and might brake the Mod.

### **RTX Remix (1.2.4)**
NVIDIA’s official ray-tracing modding toolkit.  
**Download:** https://github.com/NVIDIAGameWorks/rtx-remix/releases/tag/remix-1.2.4

### **openGL**
openGL32.exe that "converts" openGL calls to D3D9 (DirectX 9), to get RTX Remix to hook.  
**Download:** https://github.com/whisperglen/QindieGL/releases/tag/v1.2.0a

### **Quake3e**
Enhanced Quake III engine fork with modern improvements.  
**Download:** https://github.com/whisperglen/Quake3e/releases/tag/v1.1

---

## 📜 License

This is a **non-commercial fan remaster project**.  
Textures are based on original id Software assets and may not be used commercially.

---



## 🙏 Special Thanks

A huge thank-you to the following people from the official NVIDIA RTX Remix Discord server for their help, guidance, and support during development:

- **saintMath**  
- **Ferdam**
- **Jon**

Your contributions and feedback made this project possible!

---

## 🌐 Socials

- **X (Twitter):** [@WoodBoy2908](https://x.com/WoodBoy2908)
- **Discord:** [WoodBoy2908](https://discord.com/users/woodboy2908)

---

## ⭐ Support the Project

If you enjoy this RTX demo, please consider:

- ⭐ Starring the repository  
- 🖼 Sharing screenshots  
- 📝 Reporting visual issues  

Thanks for trying the demo!
