# KisanSaathi - AI-Based Smart Irrigation Advisory System

**Use Case ID:** KJS-AGR-01  
**Course:** Web Development Laboratory (`316U01L306`), Semester III

🔗 **Live Demo:** [https://kisan-saathi-wdl.vercel.app](https://kisan-saathi-wdl.vercel.app)

---

## Overview

KisanSaathi is an AI and IoT-enabled decision support platform built for sugarcane farmers in Northern Karnataka. It replaces traditional experience-based irrigation with data-driven advisories derived from soil moisture sensors, weather forecasts, satellite imagery, and predictive machine learning models.

### Key Features

- **Plot-Specific Recommendations:** Precise guidance on irrigation timing and duration.
- **Resource Optimization:** Reduces water wastage, energy consumption, and soil degradation.
- **Multilingual Support:** Generates advisories in local languages for registered farmers.

---

## Project Structure

```
├── public/                  ← Deployed to Vercel (static site root)
│   ├── index.html           ← Task 1: Homepage Structure
│   ├── farm-info.html       ← Task 2: Farm Info using Lists
│   ├── advisory.html        ← Task 3: Irrigation Advisory (Formatting Tags)
│   ├── gallery.html         ← Task 4: Farm Gallery (Images)
│   ├── plot-map.html        ← Task 5: Farm Plot Navigation (Image Map)
│   ├── plot-a.html          ← Task 5: Plot A Details
│   ├── plot-b.html          ← Task 5: Plot B Details
│   ├── plot-c.html          ← Task 5: Plot C Details
│   ├── irrigation-table.html← Task 6: Soil Moisture Table
│   ├── registration.html    ← Task 7: Farmer Registration Form
│   ├── css/
│   │   └── style.css        ← Shared stylesheet
│   └── images/
│       └── farm_map.png     ← Farm plot map image
│
├── information/             ← Reference documents (not deployed)
│   ├── WDL_Expt1_HTML.pdf
│   ├── tasks.md
│   └── CaneSense - Web Development Lab.md
│
├── vercel.json              ← Vercel deployment configuration
└── README.md
```

---

## Running Locally

```bash
# Serve from the public/ directory
cd public
python3 -m http.server 8080

# Then open http://localhost:8080
```

---

## Deployment

This project is configured for **one-click Vercel deployment**.  
Vercel auto-serves from the `public/` directory (configured in `vercel.json`).

Simply push to `main` and the deployment at  
[https://kisan-saathi-wdl.vercel.app](https://kisan-saathi-wdl.vercel.app) will update automatically.

---

### Course Outcomes

| CO Code | Description                                                                          |
| :-----: | :----------------------------------------------------------------------------------- |
| **CO1** | Develop web pages using semantic HTML5 and CSS3.                                     |
| **CO2** | Implement responsive web layouts with modern styling frameworks.                     |
| **CO3** | Build interactive pages using JavaScript DOM manipulation and jQuery event handling.  |
| **CO4** | Create component-based single-page applications using React.js.                      |
| **CO5** | Integrate front-end interfaces with mock APIs and full-stack backends.               |

---

## Project Team

- **Student Contributors:** Arav Arun, Mrudul Bhagwat, Mohammed Attar, Eshika Arya
- **Course In-Charges:** Dr. Pradnya Gotmare, Sheetal Pareira, Rohini Nair, Shivani Deosthale, Veena Badgujar
