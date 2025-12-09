# Quake 3 Arena RTX Mod Demo

![Banner](images/banner.jpg)

<p align="center">
  <img src="https://img.shields.io/badge/Engine-Quake3e-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/RTX%20Remix-1.2.4-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Textures-Upscaled%20%2B%20Remastered-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Demo-yellow?style=for-the-badge" />
</p>

This project is a visual enhancement mod for **Quake 3 Arena**, created using  
**RTX Remix 1.2.4**, **Quake3e**, **imgupscaler.ai**, and **Photopea**.  
It brings modern PBR-style textures and ray-tracing compatible materials to the game while keeping original gameplay completely intact.

> **Note:** Only textures are remastered — **no models** have been modified yet.

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

## 📸 Screenshots (Preview)


---

## 📥 Installation (START HERE — IMPORTANT!)

### 1️⃣ Go to your Quake 3 installation directory (Steam)

`Steam/steamapps/common/Quake 3 Arena/baseq3`

---

### 2️⃣ Copy the mod files

Copy **everything** from this mod’s `baseq3` folder into your own:
`Quake 3 Arena/baseq3`


Let Windows overwrite files if it asks — this is correct.

---

### 3️⃣ Change the screen resolution (optional)

Open:
`baseq3/autoexec.cfg`


Look for the following lines:

r_customWidth "xxxx"
r_customHeight "xxxx"

Replace `xxxx` with your resolution.  
The default included in this mod is:

`r_customWidth "1920"`
`r_customHeight "1080"`


---

### 4️⃣ DO NOT CHANGE ANY IN-GAME GRAPHIC SETTINGS

This is extremely important.

RTX Remix and Quake3e require specific settings already included in the config.  
Changing graphics or game options can break:

- lighting  
- reflections  
- material PBR properties  
- texture assignments  

Just launch and play.

---

## 🛠 Tools Used

### Engines & Rendering
- **NVIDIA RTX Remix 1.2.4**
- **Quake3e (latest build)**

### Texture Workflow
- **imgupscaler.ai** — AI enhancement and detail restoration  
- **Photopea** — manual cleanup, corrections, and texture prep  

---

## 📌 Known Limitations

- 3D objects / Models have not been remastered yet
- Textures dont have animations
- Some textures might not be remastered or have strange roughness effects
- RTX might not hook / work if a different: Quake3e.exe, opengl32.dll or RTX Remix version is used
- Playing Q3DM1 or Q3DM6 without "devmap" might have sky issues (playing over normal singleplayer)
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
**Download:** https://github.com/whisperglen/Quake3e](https://github.com/whisperglen/QindieGL/releases/tag/v1.1.7c

### **Quake3e**
Enhanced Quake III engine fork with modern improvements.  
**Download:** https://github.com/whisperglen/Quake3e/actions/runs/18887629438

---

## 📜 License

This is a **non-commercial fan remaster project**.  
Textures are based on original id Software assets and may not be used commercially.

---



## 🙏 Special Thanks

A huge thank-you to the following people from the official NVIDIA RTX Remix Discord server for their help, guidance, and support during development:

- **saintMath**  
- **Ferdam**

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



