# NTPU ESG GreenProof Team 🌱

We are five students in **Sustainability and ESG Data Analytics** (Prof. Min-Yuh Day, Ph.D., National Taipei University, Fall 2026). We build data and AI tools that check what companies say about sustainability against what their data shows.

---

## 👋 The team

| | Member | University | Role |
|---|---|---|---|
| 🔵 | **Hugo** | HSBA Hamburg School of Business Administration | Group leader |
| 🔴 | **Axel** | ESILV Paris | Vice leader |
| 🟡 | **Kjell** | HSBA Hamburg School of Business Administration | Team member · [personal website](https://kjell-boyens.streamlit.app) |
| 🟢 | **Yanis** | Centrale Paris | Team member |
| 🟣 | **Eva** | emlyon business school | Team member |

All five of us present, code with AI assistance and review each other's work.

---

## 📂 Our projects

### 1. GreenProof – a greenwashing screener for sustainability reports

**Question:** Are the green claims in corporate sustainability reports specific and backed by data, or are they vague?

**What it does**
- Finds environmental claims in a sustainability report (PDF) and sorts them into claim categories.
- Rates each claim against the EU Directive 2024/825 on empowering consumers for the green transition, which bans vague and offset-based green claims → **Claim Quality Score (0–100)**.
- Checks whether the report actually discloses the emissions data behind the claims (GRI 305) → **Evidence Score**.
- Three modes: transparent keyword rules, ClimateBERT, and an LLM mode.

**Sample:** consumer electronics (Apple, Samsung, LG, Sony, ASUS, Acer, HP, Philips).

🔗 [Live app](https://greenproof-d9nzwoveamyh7fjkbfattx.streamlit.app/) · [Code](https://github.com/hugoroeske/greenproof)

**Built with:** Python, Streamlit, pandas, ClimateBERT, LLM APIs

---

### 2. Case study – Alphabet / Google: AI for sustainability, and AI's own footprint

**Guiding question:** Is Alphabet's AI a net help for the climate, and is Alphabet on track for its own goal?

**What we looked at**
- **Company background:** history, financial status (FY2025 revenue $402.8 bn).
- **Business strategy:** revenue structure, "full-stack AI", Business Model Canvas.
- **AI for sustainability:** data-centre cooling, Google Maps eco-routing, Project Green Light, Flood Hub, Nest.
- **The AI paradox:** 33× less energy per prompt, but electricity demand +250 % since 2019 and emissions +81 % vs. the 2019 base year.
- **Our own analysis:** from 2023 to 2025 revenue grew 31 % and emissions 33 %, so there is no decoupling yet.

**Our verdict:** AI helps others, but today it is more problem than solution for Alphabet's own footprint. Its 2030 goal (−50 % vs. 2019) is off track.

Sources: Alphabet 10-K / 10-Q (SEC), Google 2026 Environmental Report, peer-reviewed papers (Nature 2024, FAccT 2025).

---

<sub>National Taipei University · Sustainability and ESG Data Analytics · Fall 2026</sub>

-->
