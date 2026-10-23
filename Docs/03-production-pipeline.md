# 03 — The 3D Animation Production Pipeline

The **pipeline** is the assembly line that turns an idea into a finished animated film, series, game or ad. Studios in India (DNEG, Cosmos-Maya, Green Gold, Assemblage, Xentrix and others) follow this same structure, though each adapts it.

There are three big phases:

```
PRE-PRODUCTION  ──►  PRODUCTION  ──►  POST-PRODUCTION
(Plan it)            (Build & move it)  (Polish & deliver it)
```

---

## Phase 1: Pre-production (planning)

Mistakes here are cheap to fix. Mistakes later are very expensive.

| Step | What happens | Output | Who does it |
|---|---|---|---|
| **1. Idea / concept** | The core story or message is decided | Logline, pitch | Writer, director, producer |
| **2. Script / screenplay** | Dialogue, scenes and actions are written | Script | Scriptwriter |
| **3. Concept art & visual development** | The look of characters, environments and colour mood is designed | Concept paintings, character sheets, colour keys | Concept artist, visual development artist |
| **4. Storyboard** | The script is drawn as a comic-like sequence of shots | Storyboard panels | Storyboard artist |
| **5. Animatic** | Storyboard panels are timed to scratch audio to check pacing | Rough video | Story editor |
| **6. Voice recording** | Actors record dialogue. In animation, voice usually comes **before** animation so animators can lip-sync | Audio tracks | Voice actors, sound director |
| **7. Previs (pre-visualisation)** | Rough 3D blocking of cameras and action | Low-detail 3D video | Previs artist |
| **8. Production design & planning** | Asset list, budget and schedule are prepared | Asset list, production bible | Producer, production manager, line producer |

> **Indian note:** For multi-language releases (like *Mahavatar Narsimha* in Hindi, Kannada, Telugu, Tamil and Malayalam), studios plan **dubbing and lip-sync** strategy early. Usually one "lead" language is animated and the others are dubbed.

---

## Phase 2: Production (building and animating)

### 2.1 Modelling
- Creating 3D objects (**assets**): characters, props, vehicles, environments.
- **Techniques:**
  - **Polygon / box modelling**: building from simple shapes (most common)
  - **Digital sculpting**: like clay, in ZBrush or Blender Sculpt, for organic detail such as faces and muscles
  - **NURBS / surface modelling**: smooth mathematical surfaces (cars, product design)
  - **Procedural modelling**: rule-based generation (Houdini, Geometry Nodes) for cities and terrain
  - **Photogrammetry / 3D scanning**: real objects photographed and converted to 3D (heritage sites like Hampi temples)
- **Retopology**: converting a high-detail sculpt into a clean, animation-friendly mesh.
- **Good topology** means edge loops follow muscle flow so deformation looks natural.

### 2.2 UV unwrapping
- "Unfolding" the 3D surface into a flat 2D map, like peeling an orange and laying the skin flat, so textures can be painted onto it.

### 2.3 Texturing
- Painting colour and surface detail maps: **Albedo / Base colour, Roughness, Metallic, Normal, Displacement, Ambient Occlusion**.
- Tools: Adobe Substance 3D Painter, Mari, Blender.

### 2.4 Look development (Look-dev) / shading
- Building **materials and shaders** that respond correctly to light (skin subsurface scattering, silk sheen, gold reflections). Indian costumes and jewellery are challenging and rewarding here.

### 2.5 Rigging
- Building the **skeleton (joints/bones)** and **controls** so animators can pose the character.
- Includes **skinning / weight painting** (how the mesh follows bones), **IK/FK** (inverse/forward kinematics), **facial rigs** (blendshapes / shape keys or joint-based) and **corrective shapes**.
- A good rig is fast, intuitive and doesn't break.

### 2.6 Layout
- Placing characters, sets and cameras for each shot, following the animatic. It sets lenses, framing and staging.

### 2.7 Animation
- Bringing characters to life.
- **Workflow:** *Blocking* (key poses) → *Spline / In-betweening* → *Polish* (overlap, follow-through, secondary motion, facial acting, lip-sync).
- **Methods:** Keyframe animation (hand-animated), Motion capture (recorded actor performance, then cleaned up), Procedural / simulation-driven.
- Guided by the **12 Principles of Animation** (see below).

### 2.8 FX / Simulation (Dynamics)
- Physics-based effects: **fire, smoke, water, explosions, destruction, magic, dust, rain**.
- Tools: Houdini (industry standard), Blender Mantaflow, Maya Bifrost, EmberGen.

### 2.9 Character effects (CFX)
- **Cloth simulation**: sarees, dhotis, dupattas and capes are complex flowing cloth, an especially relevant skill for Indian stories.
- **Hair and fur**: grooming and simulation (XGen, Blender hair curves, Yeti).
- **Muscle and skin** simulation.

### 2.10 Crowd simulation
- Armies, festival crowds, stadium audiences (Golaem, Houdini, Miarmy).

### 2.11 Lighting
- Placing virtual lights to create mood, direct the eye and match story beats. Lighters often work in **render passes / AOVs** for flexibility in compositing.

### 2.12 Rendering
- The computer calculates the final image from geometry, textures, lights and camera.
- **Offline (path-traced) renderers**: Arnold, RenderMan, V-Ray, Redshift, Cycles, Karma. They give high quality but can take **minutes to hours per frame**.
- **Real-time renderers**: Unreal Engine, Unity, Blender EEVEE. Frames take milliseconds, which suits games, virtual production and fast previews.
- **Render farms**: hundreds of computers rendering in parallel. Indian studios use on-premise farms or cloud farms such as AWS, Fox Renderfarm, GarageFarm and RebusFarm.

> **Quick maths for students:** A 90-minute film at 24 fps = 1,29,600 frames. At 1 hour per frame on one machine, that's about **15 years**. This is why render farms exist.

---

## Phase 3: Post-production (polish and delivery)

| Step | What happens | Tools |
|---|---|---|
| **Compositing** | Layering render passes, live-action plates and effects; fixing and integrating | Nuke, Fusion, After Effects, Blender Compositor |
| **Rotoscoping / Paint / Matchmove** (VFX) | Cutting out actors, cleaning wires and rigs, tracking camera motion | Silhouette, Mocha, PFTrack, 3DEqualizer, Nuke |
| **Editing** | Final cut and pacing | DaVinci Resolve, Premiere Pro, Avid |
| **Colour grading** | Final colour look and consistency | DaVinci Resolve, Baselight |
| **Sound design & music** | Foley, effects, background score, final mix (Dolby Atmos) | Pro Tools |
| **Dubbing / localisation** | Versions in Hindi, Kannada, Tamil, Telugu, Malayalam, Bengali, Marathi etc. | Dubbing studios |
| **Mastering & delivery** | DCP for theatres, OTT deliverables (Netflix / Prime / JioHotstar specs), broadcast masters | DCP tools |
| **CBFC certification** | Censor certificate required for Indian theatrical release (U, U/A 7+, U/A 13+, U/A 16+, A) | — |

> **India-specific:** Much of the global VFX "service" work done in India sits in **roto, paint, matchmove, prep and compositing**. These are common entry points for freshers.

---

## The 12 Principles of Animation

(From *The Illusion of Life* by Disney animators **Ollie Johnston and Frank Thomas**, 1981.) Every animation course in India teaches these.

| # | Principle | Simple meaning |
|---|---|---|
| 1 | **Squash and stretch** | Objects deform to show weight and flexibility (a bouncing ball) |
| 2 | **Anticipation** | A small move before the main action (a crouch before a jump) |
| 3 | **Staging** | Presenting an idea clearly so the audience knows where to look |
| 4 | **Straight-ahead vs pose-to-pose** | Animate frame by frame, or key poses first and fill in later |
| 5 | **Follow-through and overlapping action** | Parts keep moving after the main body stops (hair, saree pallu, tail) |
| 6 | **Slow in and slow out** (ease in / ease out) | Movements accelerate and decelerate naturally |
| 7 | **Arcs** | Natural motion follows curved paths |
| 8 | **Secondary action** | Supporting actions that add life (whistling while walking) |
| 9 | **Timing** | Number of frames determines speed, weight and emotion |
| 10 | **Exaggeration** | Pushing poses for clarity and appeal |
| 11 | **Solid drawing** (solid posing in 3D) | Volume, weight and balance |
| 12 | **Appeal** | Characters that are charismatic and interesting to watch |

---

## Pipeline management (technical side)

- **Pipeline TDs (Technical Directors)** write tools (Python, MEL, C++) that connect departments.
- **Asset management / production tracking**: Autodesk Flow Production Tracking (formerly ShotGrid), ftrack, Kitsu (open source).
- **File formats**: **USD (Universal Scene Description, by Pixar)** is now the industry-wide standard for exchanging scenes; also Alembic (.abc), FBX, OBJ, glTF/GLB (web and AR), OpenEXR (render images).
- **Version control**: Perforce (games), Git LFS.
- **Colour management**: ACES / OpenColorIO.

---

## Typical timelines (indicative)

| Project | Typical duration | Team size (indicative) |
|---|---|---|
| 30-sec 3D TV ad | 3–8 weeks | 5–25 |
| 11-min kids' TV episode (series pipeline) | 6–12 weeks per episode (many in parallel) | 50–200 for the series |
| 90-min animated feature (Indian) | 2–4 years | 150–500+ |
| 90-min animated feature (Hollywood/Pixar) | 4–7 years | 300–800+ |
| Short film (student/indie) | 3–12 months | 1–10 |

*Mahavatar Narsimha* was reportedly made on about **₹40 crore**. A big Hollywood animated feature typically costs **US$100–200 million (₹850–1,700 crore)**.

---

### Website use
- An **animated scroll-story** of the pipeline: one model (for example a Yakshagana character or a Mysuru Dasara elephant) morphs through wireframe → clay → textured → rigged → animated → lit → final render as the user scrolls. This would be the signature interactive feature of the site.
- The 12 Principles page can have **small looping demos** (GIF/WebM or Three.js) for each principle.
