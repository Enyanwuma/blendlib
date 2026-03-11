<div align="center">

<!-- ANIMATED BANNER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=E87D0D&height=200&section=header&text=BlendLib&fontSize=80&fontColor=ffffff&fontAlignY=38&desc=The%203D%20Artist%27s%20Script%20Vault&descAlignY=60&descSize=22&animation=fadeIn" />

<!-- LOGO / TITLE BLOCK -->
<br/>

```
██████╗ ██╗     ███████╗███╗   ██╗██████╗ ██╗     ██╗██████╗
██╔══██╗██║     ██╔════╝████╗  ██║██╔══██╗██║     ██║██╔══██╗
██████╔╝██║     █████╗  ██╔██╗ ██║██║  ██║██║     ██║██████╔╝
██╔══██╗██║     ██╔══╝  ██║╚██╗██║██║  ██║██║     ██║██╔══██╗
██████╔╝███████╗███████╗██║ ╚████║██████╔╝███████╗██║██████╔╝
╚═════╝ ╚══════╝╚══════╝╚═╝  ╚═══╝╚═════╝ ╚══════╝╚═╝╚═════╝
```

<br/>

<!-- BADGES ROW 1 — Status & Quality -->
[![Blender](https://img.shields.io/badge/Blender-4.x%20Compatible-E87D0D?style=for-the-badge&logo=blender&logoColor=white)](https://www.blender.org)
[![Scripts](https://img.shields.io/badge/Scripts%20%26%20Addons-340%2B-FF9A2E?style=for-the-badge&logo=python&logoColor=white)](#-script-library)
[![License](https://img.shields.io/badge/License-MIT-brightgreen?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Open Source](https://img.shields.io/badge/Open%20Source-%E2%9D%A4%EF%B8%8F-red?style=for-the-badge)](https://github.com)

<br/>

<!-- BADGES ROW 2 — Community & Activity -->
[![Stars](https://img.shields.io/github/stars/blendlib/blender-scripts?style=flat-square&color=E87D0D&logo=github)](https://github.com/blendlib/blender-scripts/stargazers)
[![Forks](https://img.shields.io/github/forks/blendlib/blender-scripts?style=flat-square&color=FF9A2E&logo=github)](https://github.com/blendlib/blender-scripts/network/members)
[![Issues](https://img.shields.io/github/issues/blendlib/blender-scripts?style=flat-square&color=E87D0D)](https://github.com/blendlib/blender-scripts/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square&logo=git)](CONTRIBUTING.md)
[![Last Commit](https://img.shields.io/github/last-commit/blendlib/blender-scripts?style=flat-square&color=E87D0D)](https://github.com/blendlib/blender-scripts/commits)
[![Contributors](https://img.shields.io/github/contributors/blendlib/blender-scripts?style=flat-square&color=FF9A2E)](https://github.com/blendlib/blender-scripts/graphs/contributors)

<br/>

> **The largest curated collection of ready-to-install Blender scripts, addons, and asset tools — built for concept artists who move fast.**

<br/>

[**Browse Scripts**](#-script-library) · [**Quick Start**](#-quick-start) · [**Gallery**](#-gallery) · [**Contribute**](#-contributing) · [**Changelog**](CHANGELOG.md)

</div>

---

## 🌟 What is BlendLib?

**BlendLib** is a massive GitHub repository housing **340+ Blender scripts and addons** organized for 3D artists, concept designers, and motion graphics creators who need production-ready tools — not three hours of coding from scratch.

Instead of hunting scattered scripts across the internet, BlendLib is your **single source of truth** — every addon categorized, version-checked, and ready for instant installation into Blender 4.x.

<table>
<tr>
<td width="25%" align="center">

**📦 340+ Scripts**
Pre-built, pre-tested addons ready to drop into any Blender project

</td>
<td width="25%" align="center">

**🎨 Concept Art Ready**
Lighting presets and shaders built for ArtStation-quality renders

</td>
<td width="25%" align="center">

**🔀 Organized**
Sorted into 8 categories — find exactly what you need instantly

</td>
<td width="25%" align="center">

**⚡ One-Click Install**
Every addon ships as a `.zip` — install straight from Blender Preferences

</td>
</tr>
</table>

---

## 🚀 Quick Start

```bash
# Clone the full repository
git clone https://github.com/blendlib/blender-scripts.git

# Or clone only the category you need (shallow + sparse checkout)
git clone --filter=blob:none --sparse https://github.com/blendlib/blender-scripts.git
cd blender-scripts
git sparse-checkout set addons/procedural
```

**Installing an Addon in Blender:**

1. Open Blender → `Edit` → `Preferences` → `Add-ons`
2. Click **Install from Disk…**
3. Select any `.zip` file from the `/addons/` folder
4. ✅ Enable the checkbox — done

> 💡 **Tip:** Running Blender 3.x? Check the [legacy branch](https://github.com/blendlib/blender-scripts/tree/blender-3x) for backwards-compatible versions.

---

## 📁 Repository Structure

```
blendlib/
│
├── 📂 addons/                  # Installable .zip addon packages
│   ├── modeling/               # Hard surface, sculpting, retopo tools
│   ├── procedural/             # Geometry Nodes rigs and generators
│   ├── rigging/                # Auto-riggers, bone tools, IK chains
│   ├── rendering/              # Lighting rigs, camera tools, compositing
│   ├── materials/              # Shader packs and material libraries
│   ├── vfx/                    # Particles, simulations, destruction
│   ├── architecture/           # City builders, structural generators
│   └── export/                 # Batch exporters, format converters
│
├── 📂 scripts/                 # Standalone .py scripts (run via Text Editor)
│   ├── asset_management/       # Library linking, asset tagging
│   ├── automation/             # Batch operations, scene setup
│   └── utilities/              # Misc helpers and shortcuts
│
├── 📂 materials/               # Shareable .blend material libraries
│   ├── metals/
│   ├── organics/
│   ├── scifi/
│   └── environments/
│
├── 📂 previews/                # Render thumbnails for all addons
├── 📂 docs/                    # Extended documentation
├── CHANGELOG.md
├── CONTRIBUTING.md
└── README.md                   # You are here
```

---

## 📦 Script Library

### 🔥 Featured & Most Popular

| # | Name | Category | Description | Version | Downloads |
|---|------|----------|-------------|---------|-----------|
| 01 | **SciFi Hard Surface Kit** | Procedural | 200+ parameter panel generator for hard-surface armor & vehicles via Geometry Nodes | `v2.4` | ![](https://img.shields.io/badge/↓-12.4k-E87D0D?style=flat-square) |
| 02 | **Concept Lighting Rig** | Rendering | Instant dramatic concept art lighting — rim, area shadows, HDRI sphere, one button | `v1.8` | ![](https://img.shields.io/badge/↓-9.8k-E87D0D?style=flat-square) |
| 03 | **Auto Terrain Builder** | Environment | Photorealistic terrains with erosion sim, rock scatter, and biome vegetation | `v3.1` | ![](https://img.shields.io/badge/↓-11.2k-E87D0D?style=flat-square) |
| 04 | **City Block Generator** | Architecture | Procedural city builder — modular buildings, streets, props, zoning rules | `v2.0` | ![](https://img.shields.io/badge/↓-8.7k-E87D0D?style=flat-square) |
| 05 | **Orb Shader Pack** | Materials | 15 magical orb, plasma & energy sphere shaders with animated noise | `v1.5` | ![](https://img.shields.io/badge/↓-7.3k-E87D0D?style=flat-square) |

---

<details>
<summary><strong>🧱 Modeling & Sculpting (42 addons)</strong></summary>

<br/>

| Name | Description | Tags |
|------|-------------|------|
| **Smart UV Unwrap Pro** | Intelligent seam detection by surface curvature — saves hours on complex organic models | `UV` `Workflow` |
| **Boolean Toolkit Pro** | Non-destructive booleans with live modifier stack and auto-cleanup | `Modeling` `Hard Surface` |
| **Curve Extruder** | Extrude complex cross-sections along any Bezier or NURBS path | `Modeling` `Curves` |
| **Symmetry Sculptor** | Radial + mirror symmetry with live mesh sync across any axis combination | `Sculpting` `Organic` |
| **Modular Wall Builder** | Snap-to-grid wall, window, and door assembly system for arch vis | `Architecture` `Modeling` |
| **Edge Flow** | Redistribute edge loops to follow surface curvature smoothly | `Retopo` `Modeling` |
| **Panel Detailer** | Add panel lines, bolts, and surface greeble to any mesh in seconds | `Hard Surface` `SciFi` |
| **Cloth Fold Generator** | Physics-based cloth drape baked to a static mesh | `Organic` `Cloth` |

</details>

<details>
<summary><strong>✨ Procedural & Geometry Nodes (58 addons)</strong></summary>

<br/>

| Name | Description | Tags |
|------|-------------|------|
| **Dungeon Builder GN** | Procedural dungeon room + corridor generator with lighting placement | `Architecture` `Fantasy` |
| **Cable & Pipe System** | Route cables and pipes between any two points with realistic sag | `SciFi` `Industrial` |
| **Asteroid Field** | Scatter realistic asteroid fields around any object with LOD control | `Space` `Scatter` |
| **Ivy Generator GN** | Grow climbing ivy along any surface — fully procedural | `Nature` `Organic` |
| **Crystal Cluster** | Parametric crystal growth system with 12 morphology presets | `Fantasy` `Materials` |
| **Ancient Ruins Kit** | Procedural column, arch, and ruin assembly with moss and erosion | `Architecture` `Fantasy` |

</details>

<details>
<summary><strong>💡 Rendering & Lighting (37 addons)</strong></summary>

<br/>

| Name | Description | Tags |
|------|-------------|------|
| **Concept Art Rig** | 3-point + rim + bounce light setup in one click, fine-tuned for illustration style | `Cycles` `EEVEE` |
| **HDRI Rotator Pro** | Real-time HDRI rotation with shadow catcher and intensity matching | `Rendering` `HDRI` |
| **Fog Volume Kit** | Atmospheric fog, mist, and god-ray volume presets optimized for Cycles | `VFX` `Atmosphere` |
| **Camera Fly Mode** | Unreal Engine-style WASD camera navigation in the viewport | `Camera` `Workflow` |
| **DOF Rig** | Auto depth-of-field rig that tracks focus object with rack-focus animation | `Camera` `Cinematic` |

</details>

<details>
<summary><strong>🎨 Materials & Shaders (61 addons)</strong></summary>

<br/>

| Name | Description | Tags |
|------|-------------|------|
| **Weathering Suite** | Rust, dirt, wear, and water damage overlays driven by mesh position | `Principled` `PBR` |
| **Stylized Toon Pack** | 8 toon shader presets with customizable outlines and halftone patterns | `NPR` `Stylized` |
| **Metal Library Pro** | 40 photorealistic metals — brushed, polished, anodized, galvanized | `PBR` `Materials` |
| **Emissive Neon Kit** | Neon sign, LED panel, and glowing strip light material presets | `SciFi` `Emit` |
| **Subsurface Organics** | Skin, wax, jade, and leaf materials tuned for subsurface scattering | `Organic` `Skin` |
| **Displacement Rocks** | 20 procedural rock and cliff materials with adaptive displacement | `Landscape` `Environment` |

</details>

<details>
<summary><strong>💥 VFX & Simulations (44 addons)</strong></summary>

<br/>

| Name | Description | Tags |
|------|-------------|------|
| **Particle FX Library** | 30+ particle presets: fire, sparks, magic, smoke, rain, snow, explosions | `Particles` `VFX` |
| **Destruction Toolkit** | Real-time Voronoi fracture with physics and glue constraint setup | `Simulation` `Physics` |
| **Water Shader GN** | Procedural ocean, lake, and river water with foam and caustics | `Fluid` `Materials` |
| **Smoke Greeble** | Animated billowing smoke column generated entirely in Geometry Nodes | `VFX` `Atmosphere` |

</details>

<details>
<summary><strong>🏗️ Architecture & City (28 addons)</strong></summary>

<br/>

| Name | Description | Tags |
|------|-------------|------|
| **City Block Generator** | Procedural city with modular buildings, streets, and zoning | `City` `Procedural` |
| **Facade Detailer** | Add window arrays, balconies, and surface detail to any building box | `Architecture` `Modeling` |
| **Interior Room Kit** | Parametric room generator with furniture scattering and lighting | `Interior` `Architecture` |
| **Bridge Builder** | Suspension, arch, and truss bridge generator with structural accuracy | `Civil` `Modeling` |

</details>

<details>
<summary><strong>⚙️ Rigging & Animation (35 addons)</strong></summary>

<br/>

| Name | Description | Tags |
|------|-------------|------|
| **Character Rig Toolkit** | One-click humanoid, creature, and mechanical rig based on Rigify+ | `Rigging` `Animation` |
| **Mechanical Rig Kit** | IK/FK chains for mechanical joints, pistons, and gear systems | `Mechanical` `Rigging` |
| **Spring Bones** | Secondary motion for hair, clothing, and tails via dynamic bone chains | `Animation` `Physics` |
| **Action Mixer Pro** | NLA editor extension with crossfade blending and procedural modifiers | `Animation` `NLA` |

</details>

<details>
<summary><strong>📤 Export & Pipeline (35 addons)</strong></summary>

<br/>

| Name | Description | Tags |
|------|-------------|------|
| **Batch Object Exporter** | Export selected objects to FBX / OBJ / GLTF in bulk with custom naming | `Export` `Pipeline` |
| **Unreal Bridge** | One-click FBX export with correct scale, LOD generation, and collision mesh | `Unreal Engine` `Game Dev` |
| **Unity Exporter Pro** | Prefab-ready GLTF/FBX export with material name mapping for Unity | `Unity` `Game Dev` |
| **Texture Baker** | Bake PBR maps (AO, Normal, Roughness, Emission) to atlas in one pass | `Texturing` `Baking` |

</details>

---

## 🖼️ Gallery

<div align="center">

| Sci-Fi Hard Surface | Concept Lighting | City Generator |
|---|---|---|
| ![](https://via.placeholder.com/280x180/1a0e05/E87D0D?text=Hard+Surface+Kit) | ![](https://via.placeholder.com/280x180/060810/5080DC?text=Concept+Lighting) | ![](https://via.placeholder.com/280x180/0d0407/C83264?text=City+Generator) |
| *SciFi Hard Surface Kit v2.4* | *Concept Lighting Rig v1.8* | *City Block Generator v2.0* |

| Terrain Builder | Particle FX | Orb Shaders |
|---|---|---|
| ![](https://via.placeholder.com/280x180/040e0c/32C864?text=Terrain+Builder) | ![](https://via.placeholder.com/280x180/0e0b03/FFC832?text=Particle+FX) | ![](https://via.placeholder.com/280x180/0a0704/E87D0D?text=Orb+Shaders) |
| *Auto Terrain Builder v3.1* | *Particle FX Library v2.2* | *Orb Shader Pack v1.5* |

</div>

> 📸 Render previews for every addon live in [`/previews/`](previews/)

---

## 🛠️ Requirements

| Requirement | Minimum | Recommended |
|-------------|---------|-------------|
| **Blender** | `3.6 LTS` | `4.1+` |
| **Python** | `3.10` | `3.11` (bundled with Blender) |
| **GPU** | Any OpenGL 4.3 | NVIDIA RTX / AMD RX for Cycles X |
| **RAM** | 8 GB | 32 GB for heavy simulations |
| **OS** | Windows 10, macOS 12, Ubuntu 20.04 | Any modern 64-bit OS |

---

## 📋 Changelog

<details>
<summary><strong>v3.2.0 — March 2025</strong> (Latest)</summary>

- ✨ **New:** Cable & Pipe System (Geometry Nodes)
- ✨ **New:** Emissive Neon Kit — 20 neon material presets
- ✨ **New:** Ancient Ruins Kit with procedural moss and erosion
- 🔧 **Updated:** City Block Generator v2.0 — major performance rewrite
- 🔧 **Updated:** Auto Terrain Builder — new biome vegetation system
- 🐛 **Fixed:** Batch Exporter scale issue on FBX export in Blender 4.1
- 🐛 **Fixed:** Character Rig pole target offset on non-uniform scale rigs
- 🗑️ **Removed:** Deprecated `legacy_uv_tools.py` (superseded by Smart UV Pro)

</details>

<details>
<summary><strong>v3.1.0 — January 2025</strong></summary>

- ✨ **New:** Dungeon Builder GN — fully procedural room + corridor generator
- ✨ **New:** Water Shader GN — ocean, lake, river with foam
- 🔧 **Updated:** SciFi Hard Surface Kit — 40 new parameter presets
- 🔧 **Updated:** HDRI Rotator Pro — shadow catcher improvements
- 🐛 **Fixed:** Particle FX Library crash on Blender 4.0 smoke domain

</details>

[View full CHANGELOG →](CHANGELOG.md)

---

## 🤝 Contributing

Contributions are what make BlendLib great. All skill levels welcome!

```
1. Fork the repository
2. Create a feature branch:  git checkout -b addon/my-new-tool
3. Add your script to the correct category folder
4. Include a preview render in /previews/
5. Update the relevant section of README.md
6. Submit a Pull Request with a description and screenshots
```

**Submission checklist:**
- [ ] Tested on Blender **4.x** (and optionally 3.6 LTS)
- [ ] Addon includes a `bl_info` dictionary with correct metadata
- [ ] Preview render included (PNG, min. 800×500px)
- [ ] No external dependencies beyond Blender's bundled Python
- [ ] Script header comment explains what it does in ≤ 3 lines

See [CONTRIBUTING.md](CONTRIBUTING.md) for the full guide.

---

## 📜 License

```
MIT License — Copyright (c) 2025 BlendLib Contributors

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software to use, copy, modify, merge, publish, distribute,
sublicense, and/or sell copies — subject to the above copyright notice
appearing in all copies.
```

All scripts in this repository are free for **personal and commercial use**. See [LICENSE](LICENSE) for full terms.

---

## 🙌 Acknowledgements

- Inspired by the incredible 3D art community on **[ArtStation](https://www.artstation.com)**
- Built on top of the amazing **[Blender](https://www.blender.org)** open-source platform
- Community contributors listed in [CONTRIBUTORS.md](CONTRIBUTORS.md)
- Special thanks to the Blender Foundation and all addon developers whose work informed these tools

---

<div align="center">

**If BlendLib saves you time, drop a ⭐ — it helps more artists find the repository.**

<br/>

[![Star History Chart](https://img.shields.io/badge/View-Star%20History-E87D0D?style=for-the-badge&logo=github)](https://star-history.com/#blendlib/blender-scripts)

<br/>

[![Twitter](https://img.shields.io/badge/Twitter-@blendlib-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg)
[![ArtStation](https://img.shields.io/badge/ArtStation-Gallery-13AFF0?style=flat-square&logo=artstation&logoColor=white)](https://artstation.com)
[![Blender Market](https://img.shields.io/badge/Blender%20Market-Extensions-E87D0D?style=flat-square&logo=blender&logoColor=white)](https://extensions.blender.org)

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=E87D0D&height=100&section=footer&reversal=false" />

</div>
