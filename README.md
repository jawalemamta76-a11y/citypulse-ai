# 🌆 UrbanChaos : ChaosCompass AI
### *Exploring, Experiencing & Navigating the Chaos We Call Home*

> **"Stop just surviving the city. Start adventuring it."**  
> Real-time messy crowd-signals, panic voice notes, flooded streets, street food aromas, and sketchy unlit alleys — synthesized into verified vibes, safe corridors, and spontaneous thrills.

---

## 🎯 The Problem & Vision

Cities are beautiful, overwhelming, and unpredictable. One minute you're hunting for the best street food, the next you're stuck in traffic, dodging a sudden downpour, stumbling into a random festival, or wondering why that one street feels sketchy at night.

Standard navigation tools (like Google Maps) treat cities like cold geometrical graphs. They will gladly walk you straight through:
- A pitch-black alley where streetlights broke down
- A knee-deep flooded underpass with stalled auto-rickshaws
- A 40-minute honking gridlock bottleneck
- While completely ignoring the legendary unlisted charcoal kebab cart 30 meters away!

**UrbanChaos (ChaosCompass AI)** changes the game. It ingests messy real-world city inputs and transforms them into **actionable clarity, safe passages, and spontaneous micro-adventures**.

---

## ⚡ Core Capabilities & Features

### 1. 🎙️ The Chaos Dump: Multimodal Real-World Ingestion Engine
Takes messy, unorganized city inputs in any format:
- **Voice Notes**: Panicked or hyped voice notes (*"Bro this place is pure fire!"* or *"Help, I'm stuck, dark alley lights out"*). Built with live mic recording, real-time waveform visualization, and speech-to-text transcript generation.
- **Visual & Photo Drops**: Direct camera/photo uploads of flooded streets, street food griddles, unlit scaffolding, or street performers.
- **Computer Vision AI Simulation**: Detects water depth, illuminance lux, crowd buzz, and hazard risks.
- **Citizen Rants & Social Posts**: Raw emotional vents converted into structured geo-anchored events.
- **City Sensor & Telemetry Integration**: Corroborates community reports with rainfall radar, traffic velocity sensors, and acoustic decibel monitors.

### 2. 🗺️ Living City Radar (Interactive Map)
- Interactive dark-mode CartoDB basemap with animated pulsing radar markers.
- **Dynamic Category Layers**:
  - 🌮 **Street Food Gems** (Golden pins: secret menus, wait times, hygiene scores)
  - 🌧️ **Hazards & Floods** (Crimson warning pins: waterlogging depths, road barriers)
  - 🛡️ **Night Safe Corridors** (Emerald pins: high-illuminance pathways, CCTV coverage)
  - 🎷 **Spontaneous Vibes** (Purple pins: flash street musicians, courtyard buskers)
  - 🚗 **Gridlock Bottlenecks** (Orange pins: stalled buses, standstill junctions)
- **Safe Havens Overlay**: Real-time beacons for 24/7 pharmacies, transit police kiosks, and well-lit bodegas.

### 3. 🧭 Multi-Modal Chaos Routing (Survival vs Adventure vs Safe Walk)
- 🛡️ **Night Safe Corridor (Guardian Path)**: 100% well-lit streets, active storefronts, verified CCTV monitoring; bypasses unlit scaffolding.
- 🌮 **City Explorer (Vibe & Foodie Path)**: Detours intentionally by 2 minutes to take you past secret charcoal kebab carts and courtyard brass bands.
- 🏃 **Survival Evade / Fast Dry Path**: Highline skybridge bypass avoiding 40cm flash floods and 35-minute car gridlocks.
- **Interactive Turn-by-Turn Guidance Simulator**: Step-by-step walk simulation with real-time audio and hazard avoidance triggers.

### 4. 🎲 The Chaos Quest Roller ("Stop Surviving, Start Living")
- Roll the dice to turn dreary weather, long layovers, or late-night cravings into interactive quests.
- Interactive checkpoints with confetti celebrations and Explorer XP leveling.
- Unlocks secret perks (unlisted speakeasy counters, clay pot chai discounts).

### 5. 🛡️ Night Guardian Safety Shield
- **Simulated Fake Incoming Call**: Realistic phone call screen with interactive speech script to deter suspicious bystanders.
- **Emergency Siren Alarm**: Browser Web Audio acoustic deterrent synthesizer.
- **Safe Haven Radar**: Quick call links and directions to the nearest 24/7 lit sanctuaries.
- **Guardian Beacon Share**: 1-click location sharing for emergency contacts.

---

## 🛠️ Tech Stack

- **Framework**: React 19 + TypeScript + Vite
- **Styling**: Tailwind CSS v4 + Plus Jakarta Sans + JetBrains Mono
- **Mapping**: Leaflet + Custom Animated HTML DivIcons
- **Audio Synthesizer**: Web Audio API (zero external mp3 dependencies)
- **Visuals & Delight**: Canvas Confetti + Lucide Icons + Cyberpunk Glow UI

---

## 🚀 Running Locally

```bash
# Clone the repository
cd "PromptWarWith AI"

# Install dependencies
npm install

# Start development server
npm run dev
```

Open `http://localhost:5173` in your browser.

## 🚀 Deploy to Vercel

1. Push this project to a GitHub repository.
2. Import the repository in Vercel.
3. Use the default settings:
   - Framework Preset: Vite
   - Build Command: `npm run build`
   - Output Directory: `dist`
4. Deploy.

The project includes a `vercel.json` rewrite so client-side routes resolve correctly.
