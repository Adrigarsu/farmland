<p align="center">
  <img src="banner.svg" alt="Farmland Banner" width="100%"/>
</p>
<p align="center">
  <!-- Engine -->
  <img src="https://img.shields.io/badge/Godot-4.3-478cbf?style=flat-square&logo=godotengine&logoColor=white"/>
  <!-- Language -->
  <img src="https://img.shields.io/badge/GDScript-ready-68c038?style=flat-square&logo=gnubash&logoColor=white"/>
  <!-- Status -->
  <img src="https://img.shields.io/badge/Status-In%20Development-f8c820?style=flat-square"/>
  <!-- Platform -->
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20Mac-a8d870?style=flat-square"/>
  <!-- License -->
  <img src="https://img.shields.io/badge/License-Educational-78c8b8?style=flat-square"/>
</p>
---
 
## 🌿 About
 
**Farmland** is a 2D top-down farming game built with **Godot 4.3 + GDScript**, following the tutorial series *"How to Build a Complete 2D Farming Game"* by [Rapid Vectors](https://www.youtube.com/@rapidvectors).
 
The project follows a **Test Scene First** methodology — each system is built and tested independently before being integrated into the main world scene.
 
---
 
## 🎮 Screenshots
 
<table>
  <tr>
    <td align="center" width="50%">
      <img src="screenshot_exterior.png" alt="Exterior world" width="100%"/>
      <sub><b>🌍 Exterior world</b> — grass, water, dirt paths and nature objects</sub>
    </td>
    <td align="center" width="50%">
      <img src="screenshot_interior.png" alt="House interior" width="100%"/>
      <sub><b>🏠 House interior</b> — full tilemap with furniture</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="assets\game\characters\character_sprites.png" alt="Character spritesheet" width="100%"/>
      <sub><b>🧑‍🌾 Character spritesheet</b> — all movement & tool animations</sub>
    </td>
    <td align="center" width="50%">
      <img src="assets\game\objects\basic_grass_biom_things.png" alt="Nature assets" width="100%"/>
      <sub><b>🌳 Nature assets</b> — trees, bushes, flowers and more</sub>
    </td>
  </tr>
</table>

---
 
## 🚜 Progress
 
 
| System | Feature | Status |
|---|---|:---:|
| 🗺️ **World** | Water tilemap layer | ✅ |
| 🗺️ **World** | Grass tilemap layer | ✅ |
| 🗺️ **World** | Dirt tilemap layer | ✅ |
| 🗺️ **World** | Nature objects (trees, rocks, flowers...) | ✅ |
| 🏠 **House** | Interior tilemap + furniture | ✅ |
| 🧑‍🌾 **Player** | Character + movement | ✅ |
| 🎭 **Player** | Walk & idle animations | ✅ |
| 💾 **Player** | Idle direction saved on state change | ✅ |
| ⛏️ **Player** | Chopping animation | ✅ |
| 💧 **Player** | Watering animation | ✅ |
| 🌱 **Player** | Tilling animation | ✅ |
| 🪓 **Tools** | Tool state system | 🔜 |
 
---
 
## 📁 Structure
 
```
farmland/
├── banner.svg
├── README.md
├── project.godot
├── assets/          # Sprites, tilesets, audio
├── scenes/
│   ├── test/        # Isolated test scenes per system
│   └── world/       # Main world scenes
└── scripts/         # GDScript (.gd)
```
 
---
 
## 🎨 Credits
 
### 🖼️ Art Assets
 
All visual assets are from the **Sprout Lands Asset Pack** by [**cupnooble**](https://cupnooble.itch.io/), used under their free distribution terms.
 
> 🌾 [**Sprout Lands – Asset Pack (Free version)**](https://cupnooble.itch.io/sprout-lands-asset-pack) — *cupnooble on itch.io*
 
Huge thanks to **cupnooble** for making these gorgeous pixel art assets freely available to the community! 🙏
 
### 🎓 Tutorial
 
> 📺 [**How to Build a Complete 2D Farming Game – All 25 Episodes · Godot 4.3**](https://www.youtube.com/watch?v=it0lsREGdmc)
> by [**Rapid Vectors**](https://www.youtube.com/@rapidvectors) on YouTube
 
---
 
## 🚀 Getting Started
 
**Requirements:** [Godot Engine 4.3+](https://godotengine.org/download)
 
```bash
git clone https://github.com/YOUR_USERNAME/farmland.git
# Open Godot → Import → select project.godot
```
 
---
 
<p align="center">
  <i>🌻 Made with love, GDScript and a lot of virtual soil 🌻</i>
</p>