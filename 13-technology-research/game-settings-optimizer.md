# Game Settings Optimizer

**Model:** Claude | **Rating:** ⭐⭐⭐⭐⭐ | **Use Case:** General

**Source:** [Notion](https://app.notion.com/318433d7bedb80708341e8b1e09f2437)

---

# Task
Analyze and determine the optimal graphics configuration for Assassin’s Creed Odyssey on:
- CPU: Intel Core Ultra 9 285H
- GPU: Intel Arc 140T (Xe2 iGPU)
- RAM: 32GB shared memory
- Display: 120Hz, ~2.8K–3K native
Primary goal: Stable 60+ FPS minimum with strong 1% lows.
Secondary goal: Maintain high visual fidelity using intelligent upscaling.
Do NOT reduce to ultra-low settings unless strictly required for stability.
---
# Research Workflow
1. Identify Arc (Xe-class or comparable iGPU) benchmarks for AC Odyssey.
2. Extract performance at:
- Native ~3K
- 1920×1200
- 1920×1080
3. Confirm upscaling support:
- XeSS
- FSR (version if known)
- TSR (if applicable)
4. Identify known Arc driver issues affecting:
- Frame pacing
- DX11/DX12 stability
5. Label findings as:
- Confirmed
- Likely
- Estimated
If data is limited, explicitly state assumptions.
---
# Optimization Framework
## A. Resolution Decision (Critical Layer)
Compare:
- Native resolution
- 1920×1200
- 1920×1080
Select the highest resolution that maintains stable 60+ FPS minimum with acceptable 1% lows.
Then select:
- Best XeSS mode (Quality/Balanced/Performance), OR
- Best FSR fallback (specify version)
Explain reasoning in ≤3 sentences.
---
## B. Advanced Graphics Tuning
For each, provide:
- Recommended setting
- Short performance rationale
Categories:
- Textures
- Shadows
- Volumetrics
- Reflections
- Ambient Occlusion
- Effects / Particles
- Post-Processing
- Anisotropic Filtering
- V-Sync
---
## C. System-Level Optimization
Recommend and justify:
- Lenovo Vantage power mode
- Windows power plan
- Driver update necessity
- Frame cap strategy:
- 60
- 90
- 120
- Uncapped w/ VRR (if viable)
Frame pacing stability > peak FPS.
---
# Hardware Guardrails
- Assume Arc 140T = upper-mid integrated Arc tier unless verified
- Prioritize 1% lows over averages
- Avoid configurations unrealistic for sustained laptop thermals
- Clearly label assumptions
---
# Output Format In a Table (Strictly ordered as it is in the game)
### 🎮 Settings for Assassin’s Creed Odyssey
Target Resolution:
[Final decision]
Upscaling Tech:
[Exact mode + 1–2 line reasoning]
Overall Preset Base:
[Preset]
---
## Detailed Tweaks
- Textures:
- Shadows:
- Volumetrics:
- Reflections:
- Ambient Occlusion:
- Effects:
- Post-Processing:
- Anisotropic Filtering:
- V-Sync:
- Frame Cap:
---
## Expected Performance
- Estimated FPS Range:
- 1% Low Expectation:
- Visual Quality Assessment:
---
Confidence Level:
High / Moderate / Low (1 sentence justification)
