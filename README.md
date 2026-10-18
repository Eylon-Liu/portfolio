# Eylon Liu — Project Portfolio

Full-stack and mobile developer with experience across iOS (SwiftUI), web (React, TypeScript), and Python. I enjoy building tools that solve real problems — from AI-powered health record management to quantitative finance pipelines.

This repo showcases selected projects. Source code for each is available upon request.

---

## FamilyVitals

**iOS app for managing personal and family health records with AI-powered data extraction.**

Upload a medical report as a PDF or photo, and the app automatically extracts lab results, dates, hospital names, and reference ranges using AI vision models. Designed for families who want to track health trends over time without manual data entry.

<p align="center">
  <img src="images/overview.png" width="230" alt="Dashboard — at-a-glance health metrics and abnormal indicator trends" />
  &nbsp;&nbsp;
  <img src="images/reports.png" width="230" alt="Reports — organized by category with AI-generated summaries" />
  &nbsp;&nbsp;
  <img src="images/me.png" width="230" alt="Profile — multi-family-member support" />
</p>

**What it does:**
- Extracts structured data from medical reports via AI (Gemini, Qwen, DeepSeek) — handles PDFs, photos, and batch imports
- Tracks 60+ lab indicators across reports, flags abnormal values, and charts trends over time
- Supports multiple family member profiles with independent data
- Fully bilingual (Chinese/English) with on-device data storage — no account or server needed

**Technical highlights:**
- SwiftUI + CoreData, iOS 16+
- Three AI provider integrations with automatic failover and batch-to-single fallback on token overflow
- Multi-pass text extraction for long reports (chunked processing with deduplication-aware merging)
- Configurable API endpoints for Alibaba Cloud workspace keys
- XcodeGen-based project configuration
- Published on TestFlight

---

## LifeMap — Personal Website

**Interactive editorial-atlas personal site.** World map of cities lived and traveled, work timeline, life chapters, and photography.

**Live:** [eylon-liu.vercel.app](https://eylon-liu.vercel.app)

**Stack:** React (JSX), Mapbox GL, Vercel static deploy. Single-source build with JSX precompilation.

---

## OIS AI — AI Calendar & Task Manager

**Web app that uses AI to intelligently schedule tasks around your real calendar.**

Connects to your calendar, understands your working hours and energy patterns, then allocates tasks to optimal time slots. Includes routine management, break optimization, and productivity analytics.

**Stack:** Python (Flask), DeepSeek API, SQLite. Full-featured dashboard with analytics and AI chat interface.

---

## Contour

**A reflective journaling app — understand what shaped you.**

Interactive journaling experience that helps users explore personal history and recurring life patterns through guided prompts and timeline visualization.

**Stack:** React Native, JavaScript.

---

## Quantitative Finance Tools

**Collection of financial analysis notebooks and trading algorithms.**

- Fixed income & credit landscape analysis across tech and financial sectors
- FX risk modeling with strip-based and fixed approaches
- Algorithmic trading strategies with backtesting
- Interactive data exploration dashboards (desktop GUI)

**Stack:** Python, Jupyter, pandas, matplotlib.

---

## Technical Skills

| Area | Technologies |
|---|---|
| **Mobile** | SwiftUI, CoreData, UIKit, XcodeGen, TestFlight |
| **Frontend** | React, TypeScript, JavaScript, HTML/CSS, Mapbox |
| **Backend** | Python, Flask, Node.js, SQLite |
| **AI/ML** | REST API integrations (Gemini, DeepSeek, Qwen), prompt engineering, vision models, structured extraction |
| **Finance** | Fixed income analysis, FX risk, algorithmic trading, quantitative modeling |
| **Tools** | Git, Xcode, Vercel, Jupyter |

---

## Contact

- GitHub: [Eylon-Liu](https://github.com/Eylon-Liu)
- Website: [eylon-liu.vercel.app](https://eylon-liu.vercel.app)
