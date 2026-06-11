# Day 8 - Personal Environmental Health Analyzer

## 🎯 Objective
Use Claude as a Senior Data Analyst, Environmental Researcher, UX Designer,
and Frontend Dashboard Developer to build a fully interactive Personal
Environmental Health Analyzer dashboard for my city — Aligarh, Uttar Pradesh.

---

## 🤖 Prompt Used

```
Act as a Senior Data Analyst, Environmental Researcher, UX Designer, and
Frontend Dashboard Developer.
Create a Claude Artifact called:
🌍 Personal Environmental Health Analyzer

DATA RULES
If no dataset is provided, automatically search the web for the latest AQI
and water-quality data for the user's current city/location.
Use the most recent available data, cite sources, clean the data, handle
missing values, and validate quality before analysis.

ANALYSIS
Generate: cleanest city, most polluted city, highest AQI city, lowest AQI
city, average AQI, number of cities analyzed, trends, anomalies, most
surprising observation, executive summary.

INTERACTIVE DASHBOARD
Create a fully interactive Claude Artifact with key metrics, AQI charts,
PM2.5 and PM10 comparisons, city ranking, filters, health analysis,
report card, and personalized recommendations.

DESIGN
Modern, professional, mobile responsive, dark theme, smooth animations,
premium UI, clean typography, dashboard-style layout.

OUTPUT
Generate a complete downloadable HTML application ready to save as index.html.
```

---

## 📊 Dashboard Output — Key Metrics (Aligarh, June 2026)

| Metric | Value |
|--------|-------|
| Home City | Aligarh, Uttar Pradesh |
| Cities Analyzed | 12 |
| Average AQI (India) | 148 — Poor |
| Highest AQI | 194 — Aligarh |
| Lowest AQI | 54 — Hyderabad |
| Environmental Health Score | 38/100 — Grade D |
| Data Sources | CPCB AQI Bulletin, IQAir, aqi.in, aqicn.org, IQAir 2026 |

---

## 📋 Executive Summary

Analysis of 12 major Indian cities in June 2026 reveals deeply alarming air
quality across North India. Aligarh records one of the highest AQIs at 194
(Unhealthy), driven primarily by PM2.5 (~85 μg/m³) and PM10 (~145 μg/m³),
placing it well above WHO safe limits.

The Indo-Gangetic Plain cities — Ghaziabad (204), Lucknow (155), Kanpur
(168), and Delhi (160) — form a chronic pollution belt due to vehicular
emissions, industrial discharge, and unfavorable topography.

Southern cities — Hyderabad (54), Chennai (56), and Bengaluru (60) — show
markedly better air quality.

Aligarh's tap water shows very high hardness (TDS 800–1200 mg/L), posing
serious risks for hair fall, scalp dryness, and skin conditions.

**Overall Environmental Health Score for Aligarh: 38/100 — Grade D.
Immediate action strongly recommended.**

---

## 🚦 AQI Category Legend

| Range | Category | Color |
|-------|----------|-------|
| 0–50 | Good | 🟢 Green |
| 51–100 | Satisfactory | 🟢 Light Green |
| 101–150 | Moderate | 🟡 Yellow |
| 151–200 | Poor | 🟠 Orange |
| 201–300 | Very Poor | 🔴 Red |
| 301+ | Severe | 🔴 Dark Red |

---

## 🏙️ City Rankings (12 Cities Analyzed)

| Rank | City | AQI | Category |
|------|------|-----|----------|
| 1 (Cleanest) | Hyderabad | 54 | Satisfactory |
| 2 | Chennai | 56 | Satisfactory |
| 3 | Bengaluru | 60 | Satisfactory |
| — | Lucknow | 155 | Poor |
| — | Kanpur | 168 | Poor |
| — | Delhi | 160 | Poor |
| — | Aligarh | 194 | Poor |
| 12 (Most Polluted) | Ghaziabad | 204 | Very Poor |

---

## 🏥 Health Impact — Aligarh (AQI 194)

| Health Aspect | Risk Level |
|--------------|------------|
| Lung health | 🔴 High |
| Sleep quality | 🔴 High |
| Energy levels | 🔴 High |
| Exercise performance | 🔴 High |
| Long-term health | 🔴 High |
| Hair fall (hard water) | 🔴 High |
| Scalp dryness | 🔴 High |
| Skin dryness | 🔴 High |
| Acne risk | 🟡 Moderate |
| Sensitive skin | 🔴 High |

---

## 📝 Personal Report Card — Aligarh

| Category | Score | Grade |
|----------|-------|-------|
| Air Quality Score | Low | D |
| Water Quality Score | Low | D |
| Overall Environmental Score | 38/100 | D |
| Hair Risk | High | — |
| Skin Risk | High | — |

---

## 💡 Key Learnings

**1. Prompt engineering can build full data applications**
A single well-structured prompt generated a complete interactive dashboard
with real data, charts, filters, and health analysis — no coding required.

**2. Context matters for data accuracy**
By specifying the city (Aligarh, Uttar Pradesh), Claude fetched real AQI
data from CPCB, IQAir, and aqicn.org instead of generating generic numbers.

**3. Multi-role prompting produces richer outputs**
Assigning Claude four roles simultaneously (Data Analyst, Researcher, UX
Designer, Frontend Developer) produced a dashboard that covered data,
design, and health insights all in one artifact.

**4. Environmental data is deeply personal**
Seeing Aligarh's AQI at 194 with a health score of 38/100 makes the data
feel real and actionable — not just numbers on a screen.

**5. Claude can generate downloadable applications**
The prompt produced a complete index.html file ready to save, open in a
browser, and share — no backend or hosting required.

---

## 📸 Screenshots

Environmental Health Analyzer Dashboard

<img width="768" height="598" alt="image" src="https://github.com/user-attachments/assets/1b275eb8-5695-46ad-96e6-e020f92278f7" />


---

## ✅ Summary

Today I used Claude to build a fully interactive Personal Environmental
Health Analyzer for Aligarh, Uttar Pradesh. The dashboard analyzed 12
Indian cities using real June 2026 AQI data and revealed that Aligarh has
one of the worst air quality scores in India at 194 AQI with an overall
environmental health score of just 38/100 — Grade D. This task demonstrated
how Claude can act as a full-stack data and design tool when given a
detailed, multi-role prompt with clear output requirements.
