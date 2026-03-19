#  eVTOL vs Other Modes — Stated Preference Survey
### Intra-City Travel · Bengaluru Metropolitan Region · Pilot Programme 2026

> **Course:** Discrete Choice Modelling  
> **Institution:** IIT Kharagpur  
> **Survey Type:** Stated Preference (SP) — Multi-modal Choice Experiment

---

##  About This Survey

This is an interactive stated preference (SP) survey designed to study travel behaviour and mode choice preferences for **on-demand eVTOL (electric Vertical Take-Off and Landing) air taxi services** in Bengaluru.

The survey compares eVTOL against existing intra-city modes — **app cab (Ola/Uber), Namma Metro, and Auto-rickshaw** — across 6 real Bengaluru origin-destination corridors.

### Survey Structure

| Part | Section | Questions |
|------|---------|-----------|
| A | Socio-Demographic Information | Q1–Q4 |
| B | Current Intra-City Travel Behaviour | Q5–Q10 |
| C | Stated Preference Choice Scenarios | 6 Choice Sets |
| D | Attitudes Towards eVTOL | Q11–Q14 |

### SP Choice Set Corridors

| Set | Origin → Destination | Time of Day | Modes |
|-----|---------------------|-------------|-------|
| 1 | Koramangala → MG Road | Peak (9 AM) | eVTOL, App Cab, Metro |
| 2 | Whitefield → Indiranagar | Peak (8:30 AM) | eVTOL, App Cab, Metro |
| 3 | HSR Layout → Rajajinagar | Off-peak (2 PM) | eVTOL, App Cab, Auto |
| 4 | Electronic City → Hebbal | Peak (8 AM) | eVTOL, App Cab, Metro, Auto |
| 5 | Malleshwaram → BTM Layout | Evening Peak (6:30 PM) | eVTOL, App Cab, Metro |
| 6 | JP Nagar → Yeshwanthpur | Mid-morning (11 AM) | eVTOL, App Cab, Auto |

### Attributes Used in Choice Sets

- **Travel Time** (door-to-door, in minutes)
- **Fare** (one-way, in ₹)
- **Wait / Access Time** (booking to pick-up or walk to station)
- **Comfort / Reliability** (qualitative: High/Medium/Low)

---

## Live Survey

🔗 **[Click here to open the survey](https://YOUR-USERNAME.github.io/evtol-sp-survey-bangalore/index.html)**

*(Replace YOUR-USERNAME with your GitHub username after deployment)*

---

## Files in This Repository

```
evtol-sp-survey-bangalore/
│
├── index.html        ← The complete interactive survey (open this in any browser)
└── README.md         ← This file
```

---

## How to Use Locally

1. Download or clone this repository
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari)
3. No internet connection needed after loading (except for Google Fonts)

---

## Data Collection

Each respondent can download their own responses as a **CSV file** at the end of the survey. To collect responses at scale, consider integrating with a form backend like Formspree or Google Forms embedding.

The CSV columns map directly to variables for use in **Biogeme**, **NLOGIT**, or **R (mlogit)** for Multinomial Logit / Nested Logit estimation.

---

*Academic use only. Data collected is anonymous and used solely for research.*
