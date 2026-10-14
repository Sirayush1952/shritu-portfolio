# SHRITU SINHA — THE AUTOMOTIVE PORTFOLIO EXPERIENCE

> **“I DON'T JUST IMAGINE THE FUTURE. I BUILD IT.”**  
> *Built with curiosity. Powered by imagination. Driven by the future.*

A futuristic, luxury automotive-themed personal portfolio website for **Shritu Sinha**, an aspiring AI developer, software creator, and technology enthusiast.

---

## 🏎️ Core Architectural Features

### 1. Opening Loading Experience
- Full-screen cinematic sequence with corner brackets, fine technical crosshairs, and outlined progress indicator.
- Enormous bold uppercase **LOADING** with glitch text styling.
- Smooth progress indicator (0% to 100%) with status telemetry messages.
- Discreet **Skip Intro** option.
- Synchronized Web Audio ignition sound on reveal.

### 2. Main Hero: The Engine Room (`IGNITION`)
- Interactive real-time 3D **V12 Twin-Turbo Performance Engine** crafted with Three.js and React Three Fiber.
- Components include engine block, V60 cylinder heads, twin-turbochargers with spinning turbine blades, mandrel titanium exhaust headers, serpentine belt with spinning pulleys, and pulsing ignition leads.
- Full orbit controls: drag to rotate, pinch/scroll to zoom, and camera reset button.
- **6 Interactive Hotspots** on mechanical parts:
  - **Engine Block** → About Me (*The Driver*)
  - **Turbocharger** → Projects (*The Garage*)
  - **Ignition System** → Skills (*Headlight Knowledge*)
  - **Cooling System** → Achievements (*Pole Position*)
  - **Transmission** → Journey & Learning Process
  - **Exhaust System** → Contact (*The Finish Line*)
- Floating mechanical **Information Ring HUD** detailing technical specifications, personal automotive analogies, and section jump actions.

### 3. Personal Branding
- Located in the left hero corner.
- Elegant cursive word **Portfolio** (*Great Vibes*).
- Oversized uppercase two-line name **SHRITU SINHA** combining solid metallic silver gradients and cyan neon outlined typography.
- Tagline: *“I DON'T JUST IMAGINE THE FUTURE. I BUILD IT.”*

### 4. Signature 3D Rotating Wheel (Top-Right)
- Continuously rotating 3D hypercar wheel with forged alloy spokes, carbon-ceramic drilled rotor, and cyan Brembo-style brake caliper.
- Hover accelerates spin and glow.
- Click toggles quick-access racing telemetry navigation dropdown.
- Integrated **Audio Controller** (Mute / Unmute).

### 5. Racing Dashboard Navigation HUD
Five dedicated automotive sections:
1. `IGNITION` — Hero Engine Room
2. `THE DRIVER` — Biography & Philosophy
3. `THE GARAGE` — Projects & Prototypes
4. `POLE POSITION` — Awards & Accolades
5. `THE FINISH LINE` — Contact & Transmission

### 6. Crystalline Aerodynamic Sculpture & Liquid Paint Drips
- 3D faceted translucent crystal butterfly inspired by aerodynamic hypercars.
- Translucent faceted wings with refractive dispersion, inner light core, and fluttering motion.
- Surrounded by flowing liquid-paint drops and glossy metallic tendrils dripping downward.

### 7. Homepage Statistics
- **YEARS EXPERIENCE**: `2+`
- **PROJECTS DONE**: `100%`
- **CREATIVE DRIVE**: `100%` (smoothly counts from 1 to 100 with a triumphant cyan glow upon reaching 100).

### 8. THE DRIVER (About Me)
- Exact personal creed and builder introduction.
- **5 Automotive Metaphors**:
  - *Curiosity is the Ignition* (12,000 RPM Spark)
  - *Creativity is the Design Language* (Sculptural Aerodynamics)
  - *Learning Process is the Journey* (Closed Circuit Telemetry)
  - *Projects are the Machines* (Digital Chassis)
  - *Ambition is the Destination* (Unlimited Apex)
- Dedicated luxury editorial portrait frame and signature slot (with refined SVG placeholders).

### 9. THE GARAGE (Projects Showcase)
- 5 distinct engineered machines:
  1. **JARVIS AI Assistant** (Python, Local AI, Voice Interaction, TTS, Desktop Automation)
  2. **wallla** (Wallpaper Customization Studio)
  3. **2.0** (Next-Gen E-Commerce Experience)
  4. **Fastest Finger** (Low-Latency Buzzer System)
  5. **Racing Game** (Open-World 3D Driving Simulator)
- **Interactive Fuel Gauge**: Transparent cylindrical glass reservoir with real-time liquid wave gradient. Automatically calculates level from number of configured projects while strictly preserving an empty reserve capacity (never hits 100%).
- Detailed **Project Modal** with status badges (*Working Prototype*, *In Development*, *Concept*), stack tags, benchmarks, and links.

### 10. Headlight Knowledge System (Skills)
- Vehicle bonnet assembly with realistic bi-xenon projector headlights and LED halo rings.
- Tactile physical-style toggle switch (**BEAM HIGH / OFF**).
- When turned **ON**: Casts bright volumetric light beams and illuminates the floating knowledge panel.
- Technical skills with editable level tags (*Exploring*, *Learning*, *Working Knowledge*).

### 11. POLE POSITION (Achievements)
- Automotive award hall with metallic borders and spotlight effects.
- Zoomable, keyboard-accessible **Certificate Viewer Modal** with next/previous controls and celebratory confetti.

### 12. THE FINISH LINE (Contact)
- Headline: *“EVERY GREAT JOURNEY STARTS WITH A CONNECTION.”*
- Telemetry contact cockpit with client validation and mailto dispatch protocol.
- Status notice: *“THE NEXT CHAPTER IS UNDER CONSTRUCTION.”*
- Final Tagline: *“BUILT WITH CURIOSITY. POWERED BY IMAGINATION. DRIVEN BY THE FUTURE.”*

### 13. Zero-Dependency Web Audio System
- Built-in Web Audio API synthesizer (`src/utils/audioSystem.ts`) producing starter motor cranks, turbo spool whistles, throttle revs, mechanical toggle clicks, and chimes directly in browser memory without external assets.

---

## 🛠️ Tech Stack

- **React 19 & TypeScript**
- **Vite**
- **Tailwind CSS 4**
- **Three.js & React Three Fiber (@react-three/fiber)**
- **Drei (@react-three/drei)**
- **Framer Motion**
- **Lucide Icons**
- **Canvas Confetti**

---

## 🚀 Running the Project

### Development Server:
```bash
npm run dev
```

### Production Build:
```bash
npm run build
```

### Preview Production Build:
```bash
npm run preview
```

---

## 🎨 Easy Customization Guide

All personal data, skills, projects, and achievements are centrally managed in a single, well-documented TypeScript file:

👉 **`src/data/portfolioData.ts`**

- **Personal Info / Tagline**: Edit `portfolioData.branding`
- **Introduction & Metaphors**: Edit `portfolioData.about`
- **Portrait Photo**: Place your photo at `public/images/shritu-portrait.jpg`
- **Signature**: Place your vector signature at `public/images/shritu-signature.svg`
- **Projects**: Add, remove, or edit entries in `portfolioData.projects` (the fuel gauge will automatically recalculate).
- **Skills**: Add or adjust skill levels in `portfolioData.skills`.
- **Certificates**: Add trophies in `portfolioData.achievements`.
