# 04 — Software and Hardware Guide (with Indian pricing context)

> ⚠️ **Prices change often and depend on exchange rates and GST (18% on software in India).** USD figures below are indicative list prices. INR conversions use roughly **₹85–88 = US$1**. Always check the official Indian store or an authorised Indian reseller before publishing prices.

---

## 1. Core 3D software (all-in-one packages)

| Software | Developer | Best for | Cost | Used in India by |
|---|---|---|---|---|
| **Blender** | Blender Foundation (open source) | Everything: modelling, sculpting, animation, rendering (Cycles/EEVEE), VFX, 2D (Grease Pencil) | **Free forever** | Students, freelancers, indie studios, YouTubers, increasingly mid-size studios |
| **Autodesk Maya** | Autodesk | Industry standard for **character animation and rigging** in film/TV/VFX | ~US$2,010/yr (US list, before tax); **Maya Indie** for small earners (under US$100k/yr) at a much lower annual price, purchasable through the India e-store ⚠️ | DNEG, most feature and TV studios |
| **Autodesk 3ds Max** | Autodesk | Architectural visualisation, game assets, product viz | Similar to Maya; Indie version available ⚠️ | ArchViz firms, game art outsourcing studios |
| **Cinema 4D** | Maxon | Motion graphics, advertising, broadcast design | Subscription (Maxon One bundle) ⚠️ | Ad agencies, broadcast (sports/news graphics) |
| **Houdini** | SideFX | **FX / simulations**, procedural workflows | **Houdini Apprentice: free** (non-commercial); Indie ~US$269/yr; FX full licence is expensive | VFX FX departments, games (procedural) |

**Free student licences:** **Autodesk** gives free 1-year educational licences (Maya, 3ds Max) to verified students and educators. **Maxon**, **SideFX** (Houdini Education) and **Foundry** (Nuke Non-commercial) also offer free or discounted student and learning versions. Students in India should always use these legally rather than pirated copies. Piracy means no updates, malware risk, and studios check software ethics in interviews.

## 2. Sculpting and texturing

| Software | Purpose | Cost |
|---|---|---|
| **ZBrush** (Maxon) | Digital sculpting, the industry standard for characters and creatures | Subscription; also **ZBrush for iPad** |
| **Blender Sculpt Mode** | Sculpting | Free |
| **Adobe Substance 3D Painter / Designer / Sampler** | PBR texturing and materials | Subscription (Steam perpetual versions sometimes available) |
| **Foundry Mari** | High-end film texturing | Expensive; non-commercial version |
| **Quixel Mixer / Megascans** | Scanned real-world materials | Megascans now available via **Fab** marketplace (Epic) |
| **Nomad Sculpt** | Sculpting on iPad and Android tablets | Low one-time cost; good for mobile-first Indian learners |

## 3. Rendering engines

| Renderer | Type | Comes with / works with |
|---|---|---|
| **Cycles** | Path tracer (offline) | Blender (free) |
| **EEVEE** | Real-time rasteriser | Blender (free) |
| **Arnold** | Path tracer | Bundled with Maya / 3ds Max |
| **RenderMan** (Pixar) | Path tracer | Maya, Houdini, Blender; free non-commercial version |
| **V-Ray** (Chaos) | Path tracer | 3ds Max, Maya, SketchUp. Very popular in Indian ArchViz |
| **Corona** (Chaos) | Path tracer | 3ds Max, Cinema 4D. Popular for interiors |
| **Redshift** (Maxon) | GPU renderer | Cinema 4D, Maya, Houdini, Blender |
| **Octane** (OTOY) | GPU renderer | Multiple |
| **Karma** | Path tracer | Houdini |
| **D5 Render / Lumion / Enscape / Twinmotion** | Real-time ArchViz | Popular with Indian architects |

## 4. Game engines and real-time

| Engine | Cost | Notes |
|---|---|---|
| **Unreal Engine 5** (Epic Games) | Free to learn and use; 5% royalty only after US$1 million gross per product (games). Free for most film/animation/linear work ⚠️ check current licence | Nanite, Lumen, MetaHuman; used for **virtual production**, animated series, games |
| **Unity** | Free Personal tier (revenue thresholds apply); paid Pro tiers | Huge in Indian mobile gaming |
| **Godot** | Free, open source | Growing indie choice |

## 5. Compositing, editing and VFX

| Software | Purpose | Cost |
|---|---|---|
| **Nuke** (Foundry) | Industry standard for VFX compositing | Expensive; **Nuke Non-commercial** free |
| **DaVinci Resolve + Fusion** (Blackmagic) | Edit, colour, compositing, audio | **Free** version is very capable; Studio is a one-time purchase |
| **Adobe After Effects** | Motion graphics, compositing | Creative Cloud subscription (India pricing available) |
| **Silhouette, Mocha Pro** | Rotoscoping, paint, planar tracking | Paid |
| **3DEqualizer, PFTrack, SynthEyes** | Matchmove / camera tracking | Paid |

## 6. Specialised tools

| Tool | Purpose |
|---|---|
| **Marvelous Designer** | Realistic cloth and costume creation (sarees, kurtas, armour) |
| **Autodesk MotionBuilder** | Motion-capture editing |
| **Rokoko, Xsens, Vicon, OptiTrack** | Motion-capture hardware and suits |
| **Move.ai / Rokoko Vision / DeepMotion** | AI markerless mocap from phone or webcam video (budget-friendly) |
| **Cascadeur** | Physics-assisted keyframe animation (free tier) |
| **Character Creator / iClone** (Reallusion) | Fast character creation and animation |
| **MetaHuman** (Epic) | Photoreal digital humans for Unreal |
| **SpeedTree** | Trees and vegetation |
| **Golaem** | Crowd simulation |
| **EmberGen** (JangaFX) | Real-time fire and smoke |
| **Gaea / World Machine** | Terrain generation |
| **Krita / Photoshop / Procreate** | Concept art and storyboards |
| **Storyboarder** (free) / **Toon Boom Storyboard Pro** | Storyboarding |

## 7. Production tracking and pipeline

- **Autodesk Flow Production Tracking** (formerly ShotGrid/Shotgun)
- **ftrack**
- **Kitsu** (free, open source; good for small Indian studios and colleges)
- **Perforce, Git LFS**: version control
- **Python** is the main scripting language across Maya, Houdini, Blender and Nuke

## 8. AI-assisted tools (2025–2026)

See [10-trends-and-future.md](10-trends-and-future.md) for detail.
- Text/image-to-3D: Meshy, Tripo, Luma Genie, Rodin, Hunyuan3D
- AI video: Runway, Kling, Veo, Sora and others
- AI mocap: Move.ai, Plask, DeepMotion
- AI texturing: Substance 3D (Adobe Firefly integration)
- AI upscaling and denoising: OptiX / OIDN denoisers (already built into Blender/Arnold)

---

## 9. Recommended learning stack for Indian beginners

| Budget | Stack | Total software cost |
|---|---|---|
| **₹0 (Free stack)** | Blender + Krita + DaVinci Resolve + Unreal Engine + Houdini Apprentice | **₹0** |
| **Student (verified)** | Above + Maya/3ds Max (free edu licence) + Substance (student pricing) + Nuke Non-commercial | ~₹0–5,000/yr |
| **Freelancer** | Blender + Substance 3D + ZBrush + Maya Indie (if eligible) | ~₹25,000–60,000/yr ⚠️ |
| **Studio** | Maya / Houdini / Nuke / Substance / ZBrush + render farm | Lakhs per seat per year |

> **Our recommendation for the website:** start with **Blender**. It is free, professional, runs on modest PCs, has a huge Indian YouTube community (including Hindi tutorials), and the skills transfer to Maya later.

---

## 10. Hardware guide (Indian market, 2026) ⚠️ indicative

### Minimum to start learning (budget ~₹45,000–60,000)
- **CPU:** Intel Core i5 (12th gen+) / AMD Ryzen 5 (5600 or newer)
- **RAM:** 16 GB
- **GPU:** NVIDIA GTX 1650 / RTX 3050 (an NVIDIA RTX GPU is strongly preferred: CUDA/OptiX speeds up Blender Cycles)
- **Storage:** 512 GB NVMe SSD
- **Monitor:** 24" Full HD IPS

### Recommended for serious students / freelancers (~₹1,00,000–1,60,000)
- **CPU:** Ryzen 7 / Intel Core i7 (8+ cores)
- **RAM:** 32 GB (64 GB for heavy sims)
- **GPU:** NVIDIA RTX 4060 Ti 16 GB / RTX 5060 Ti / RTX 4070-class (VRAM matters for rendering)
- **Storage:** 1 TB NVMe SSD + 2 TB HDD for archives
- **Monitor:** 27" QHD with good sRGB coverage
- **Pen tablet:** Wacom One / XP-Pen / Huion (₹4,000–15,000), useful for sculpting and texturing

### Professional workstation (₹2.5 lakh+)
- Ryzen 9 / Threadripper / Intel Core Ultra 9, 64–128 GB RAM, RTX 4080/4090/5080/5090-class GPU, calibrated monitor

### Laptops
- Gaming laptops with **RTX 4060 / 5060 or above** (₹80,000–1,50,000) work well for students who need portability.
- Ensure good cooling. Indian summers plus long renders cause thermal throttling.

### India-specific practical tips
- **Power backup:** use a **UPS** (₹5,000–15,000), and an inverter in areas with frequent power cuts. A power cut mid-render or mid-save can corrupt files.
- **Voltage stabiliser / surge protector** for the PC.
- **Save often + auto-save + cloud backup** (Google Drive / OneDrive).
- **Cloud render farms** let students render final projects without buying expensive GPUs.
- **Second-hand GPUs** are common on OLX and in local markets (SP Road in Bengaluru is famous for computer hardware). Test before buying.
- **Internet:** 4G/5G or broadband of 50 Mbps+ helps with downloading assets and uploading renders.

---

### Website use
- **"Tools" page** with filterable cards (Free / Paid / Student-free; Category: Modelling / Animation / FX / Rendering / Compositing).
- **"Build your PC" calculator** with three budget tiers in INR. Add a disclaimer and a "last updated" date.
- A **"Free stack" banner** that says "Start for ₹0" is a strong hook for Indian students.
