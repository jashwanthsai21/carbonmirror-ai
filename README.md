# 🌍 CarbonMirror AI — Intelligent Carbon Footprint Awareness Platform

> **Hack2Skills PromptWars — Main Challenge 3 Submission**

CarbonMirror AI is an AI-powered sustainability platform that helps individuals understand, track, and reduce their carbon footprint through personalised insights, real AI coaching, gamification, and future impact visualisation.

Unlike traditional carbon calculators, CarbonMirror AI acts as a personal sustainability coach — transforming your footprint data into actionable reduction plans, a 5-year Carbon Twin projection, and measurable environmental progress.

---

## 🚀 Live Demo

[▶ View Live App](YOUR_DEPLOYED_LINK_HERE)

## 📂 GitHub Repository

[View Source Code](YOUR_GITHUB_LINK_HERE)

## 🎥 LinkedIn Build Journey

[View LinkedIn Post](YOUR_LINKEDIN_LINK_HERE)

---

## 📌 Problem Statement

Many individuals want to live more sustainably but struggle to understand:
- How much carbon they actually generate day-to-day
- Which activities create the highest environmental impact
- Which specific actions deliver meaningful reductions
- How their future environmental impact will unfold if habits continue

CarbonMirror AI addresses all four challenges using India-calibrated emission data, real AI-powered coaching, and an emotional "Carbon Twin" future visualisation that makes the stakes personal.

---

## ✨ Key Features

### 🧮 India-Specific Carbon Calculator
Calculates annual footprint across four categories — **Transport, Home Energy, Food & Diet, Shopping** — using India-specific emission factors:

- **Transport**: Petrol/CNG/electric cars, electric scooters (Ola S1, Ather 450, TVS iQube), auto-rickshaws, metro/train, domestic & international flights
- **Home Energy**: State-level grid intensity (Telangana, Karnataka, Tamil Nadu, Maharashtra, Delhi, Kerala, and 4 more DISCOMs), LPG/PNG/induction cooking
- **Food**: South Indian vegetarian, North Indian vegetarian, vegan, chicken/fish, mutton/beef patterns
- **Shopping**: Clothing and electronics consumption patterns

Outputs: Emission breakdown, CarbonMirror Sustainability Score (0–100), national average comparison, and personalised action tips.

**Data sources**: CEA Grid Emission Factors 2024, MoEFCC India GHG Platform, IPCC AR6, Oxford Poore & Nemecek 2018.

---

### 🤖 EcoGPT AI Coach (Real AI via Claude API)
Interactive sustainability assistant powered by the Claude AI API:

- Explains your emission sources in simple language
- Answers sustainability questions with India-specific context
- Generates personalised recommendations based on your actual footprint data
- References Indian cities, metro systems, PM Surya Ghar Yojana, local transport options
- **Graceful fallback**: If the AI API is unavailable, locally-generated expert responses ensure the feature never breaks

Built with full conversation history, typing indicators, and one-tap suggestion buttons.

---

### 🪞 Carbon Twin Simulator
Visualises two diverging futures based on your footprint data:

| Scenario | Description |
|----------|-------------|
| **Current Path** 🌫️ | Projected CO₂ if current habits continue for 5 years |
| **Green Path** 🌱 | Projected CO₂ after implementing the reduction roadmap |

Displays total savings in tonnes, equivalent km of driving, and trees planted equivalent.

---

### 📅 30-Day Carbon Reduction Roadmap
Automatically personalised based on your biggest emission source:

- **Week 1**: Foundation — audit your highest-impact category
- **Week 2**: Food choices — local markets, meal planning, meat reduction
- **Week 3**: Transport shift — metro, cycling, carpooling
- **Week 4**: Home energy and shopping — AC settings, BEE 5-star, repair culture

Each action includes its estimated CO₂ saving.

---

### 📊 Activity Tracking Dashboard
Log daily actions and visualise your progress:

- 5 categories: Transport, Food, Energy, Shopping, Eco Actions
- 23 specific activities with accurate CO₂ values and XP rewards
- Weekly bar chart with colour-coded days (green = eco action, amber/red = high emitter)
- Rolling activity log with 8 most recent entries

---

### 🏆 Gamification System
Full progression system to sustain engagement:

| Level | XP Required |
|-------|------------|
| 🌱 Beginner | 0 |
| 🌿 Green Warrior | 500 |
| 🌳 Earth Guardian | 1,200 |
| 🏆 Climate Champion | 2,500 |
| ⭐ Eco Legend | 5,000 |

**8 achievement badges**: First Log, 7-Day Streak, Low Carbon, Challenger, 100 XP Club, Veg Hero, Cycle Champ, Energy Star.

**6 weekly challenges**: Car-Free Week, Meat-Free Days, Energy Audit, Zero Plastic Day, Walk 30 min/day, Cold Wash Week.

---

### 📄 Sustainability Report Generator
One-click downloadable PDF report containing:
- Full footprint summary with category breakdown (%)
- CarbonMirror Score and benchmark comparison
- Carbon Twin 5-year projection
- Complete 30-day roadmap
- Progress stats (XP, level, streak, eco actions)

---

### 🇮🇳 India-Centric Design
Every detail is localised for the Indian context:
- Metro systems: Hyderabad, Delhi, Bangalore, Chennai, Mumbai
- Electric two-wheelers: Ola S1, Ather 450, TVS iQube
- Carpooling: QuickRide (popular in Hyderabad/Bangalore)
- Solar subsidy: PM Surya Ghar Yojana (up to ₹78,000)
- DISCOM: TSSPDCL, BESCOM, MSEDCL, KSEB and 6 more
- Diet: South Indian vegetarian, sabzi mandi shopping
- Second-hand: Cashify, OLX, Flyrobe

---

## 🛠️ Technical Architecture

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, JavaScript (ES6+) |
| AI Integration | Claude API (claude-sonnet-4-20250514) |
| Data Visualisation | Chart.js 4.4.1 |
| Typography | Inter + Sora (Google Fonts) |
| State Persistence | localStorage |
| Deployment | GitHub Pages / Vercel / Netlify |
| Architecture | Single-file SPA, zero build tools |

---

## 📁 Project Structure

```
carbonmirror-ai/
├── index.html      # Complete self-contained app
└── README.md       # This file
```

The entire app ships as a single `index.html`. Zero npm, zero dependencies to install — open and it works.

---

## 🚀 Quick Start

### Local
```bash
git clone https://github.com/YOUR_USERNAME/carbonmirror-ai
cd carbonmirror-ai
open index.html
```

### GitHub Pages
1. Fork the repo
2. Settings → Pages → `main` branch, root folder
3. Live at `https://YOUR_USERNAME.github.io/carbonmirror-ai`

### Vercel (recommended)
```bash
npx vercel --prod
```

### Netlify
Drag `index.html` to [app.netlify.com/drop](https://app.netlify.com/drop)

---

## 🌍 Carbon Calculation Methodology

Emission factors used are India-specific and referenced to peer-reviewed sources:

| Category | Source |
|----------|--------|
| Grid electricity | CEA Grid Emission Factors, India (2024) |
| Transport | MoEFCC India GHG Inventory, IPCC AR6 |
| Food emissions | Poore & Nemecek (2018), Oxford University |
| Shopping/consumption | Carbon Trust product lifecycle assessments |

India-specific factors applied:
- State-level grid intensity (0.50 – 0.95 kg CO₂/kWh across 10 states)
- Auto-rickshaw: 9 g CO₂e/passenger-km (CNG average)
- Metro/rail: 1 g CO₂e/passenger-km (Indian Railways grid mix)
- Domestic flight: 180 g CO₂e/km (DGCA average load factor)

---

## 📊 Evaluation Criteria Mapping

| Criterion | Implementation |
|-----------|---------------|
| **Individual understanding** | Personalised breakdown + CarbonMirror score + grade vs. India avg |
| **Tracking** | Activity logger, weekly chart, streak counter, 8 months history |
| **Reducing** | 13 tips sorted by CO₂ saving, 30-day roadmap, personalised actions |
| **Personalised insights** | AI coach reads actual footprint data for every response |
| **Simple actions** | One-tap logging, challenge progress, activity suggestions |
| **Innovation** | Carbon Twin future simulation, CarbonMirror score, AI fallback |
| **User engagement** | XP, levels, badges, challenges, leaderboard, community feed |
| **Technical execution** | Real AI API, graceful fallback, localStorage persistence, responsive |
| **Documentation** | India data sources cited, methodology explained, deployment guides |
| **India relevance** | 10 DISCOMs, local transport modes, diet patterns, PM schemes |

---

## 🔮 Future Roadmap

- [ ] Supabase backend for cross-device sync
- [ ] Carbon offset marketplace (Gold Standard India projects)
- [ ] Smart home device integration (smart meter APIs)
- [ ] Community challenges with real users
- [ ] ESG reporting for small businesses
- [ ] WhatsApp bot integration for daily logging

---

## 👤 Author

**Banoth Jashwanth Sai**
Built for Hack2Skills PromptWars Virtual Challenge — Main Challenge 3.

---

## 📄 License

MIT License — free to use, fork, and adapt.

---

*"The greatest threat to our planet is the belief that someone else will save it." — Robert Swan*
