# EcoCycle – Smart Plastic Waste Management Platform

An interactive, modern, responsive web application focused on addressing the escalating global plastic waste crisis through education, AI-driven clean technologies, municipal waste segregation, and community habit transformation.

---

## 🌟 Key Features

### 1. Hero & Verified Global Baselines
- **Hero Statement**: *"Turn Plastic Waste into a Sustainable Future"* with dual interactive CTAs (*"Explore Solutions"* & *"Calculate My Plastic Footprint"*).
- **Global Metric Cards**: Authenticated baseline data from **OECD**, **UNEP**, **IUCN**, and **NOAA** with interactive source verification and publication links.

### 2. Plastic Pollution Awareness & Polymer Matrix
- **Four Core Pollution Pillars**: Land & Freshwater Contamination, Marine Wildlife & Ocean Gyres, Human Health & Microplastic Bioaccumulation, and the Single-Use Crisis.
- **Scientific Plastic Matrix**: Side-by-side comparison of **Biodegradable & Compostable**, **Mechanically Recyclable**, and **Non-Recyclable** plastics, detailing degradation times, resin codes, pros/cons, and real-world disposal rules.

### 3. Smart Recycling Solutions & Clean Tech
- **6 Advanced Technological Frontiers**:
  1. AI-Powered Computer Vision & Spectral Identification
  2. Recycling Robotics & Automated High-Speed Delta Sorting
  3. Optical Near-Infrared (NIR) Air-Jet Sorting Systems
  4. Advanced Depolymerization & Upcycled Construction Materials
  5. Smart Reverse Vending (RVMs) & IoT Waste Tracking
  6. Closed-Loop Bottle-to-Bottle & Refill Systems
- **Scientific Nuance**: Transparently explains mechanism, benefits, and practical limitations (highlighting that plastic-to-fuel is thermal recovery and not circular recycling).

### 4. Plastic Footprint Calculator
- Custom weekly usage sliders for bottles, shopping bags, takeout containers, disposable cups/straws, and snack wrappers.
- Computes weekly and yearly item totals, estimated polymer mass in kilograms, and lifecycle greenhouse gas footprint (kg CO₂e).
- Generates personalized eco-swaps and syncs directly with the **Impact Dashboard** via `localStorage`.

### 5. Interactive Waste Sorting Guide
- Searchable directory of everyday plastic items with resin codes (RIC #1–#7).
- Category filters: *Curbside Recyclable*, *Special Store Drop-Off*, *Non-Recyclable / Trash*, and *Industrial Compostable*.
- Preparation steps (rinsing, cap retention, drying) and warnings against "wishcycling".
- Prominent reminder to cross-reference local municipal waste hauler guidelines.

### 6. 7-Day Plastic-Free Challenge
- 7 daily actionable missions with practical zero-waste tips.
- Real-time progress bar, streak tracker, local storage persistence, and celebratory confetti animations upon completion.

### 7. Verified Recycling Center Locator
- Search by City name or PIN / Postal code.
- Filter by accepted resin types (PET, HDPE, Film, PP, Styrofoam, E-Waste).
- Verified facilities with operating hours, phone, official links, and directions.
- **"Submit Verified Center" Form**: Community contribution modal that saves new verified centers to local storage.

### 8. Personal Impact Dashboard
- Real-time logger: One-tap buttons to record avoided bottles, bags, takeout containers, straws, and sorted items.
- Monthly reduction goal tracker with progress percentages.
- Visual category distribution charts and strict scientific disclosure distinguishing self-reported estimates from certified municipal scale weights.

### 9. Take Action Today & Sector Blueprints
- Tailored action plans and 24-hour quick wins for **Students & Youth**, **Households & Families**, **Colleges & Universities**, and **Communities & Neighborhoods**.
- Full action checklist modal for each sector.

### 10. Footer & Global Resources
- Newsletter subscription with instant feedback.
- Interactive **Contact & Partnerships Desk** modal.
- Outbound citations to **UNEP**, **The Ocean Cleanup**, **Ellen MacArthur Foundation**, **Plastic Soup Foundation**, and **Break Free From Plastic**.

---

## 🛠️ Tech Stack
- **Frontend**: React 19, Vite 8, Tailwind CSS v4
- **Icons**: Lucide React
- **Celebration Effects**: Canvas Confetti
- **State & Persistence**: React Hooks + LocalStorage API

---

## 🚀 Running the Project

```bash
# Navigate to the project directory
cd ecocycle-app

# Install dependencies (if not already installed)
npm install

# Start the development server
npm run dev
```

Open `http://localhost:5173/` in your browser.
