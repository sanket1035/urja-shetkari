# Urja Shetkari (उर्जा शेतकरी)

**From food provider to energy provider.** This platform helps small farmers earn from solar power and biogas alongside their crops.

Submitted to the **Seva First Innovation Challenge 2026** (Ministry of Education), Maharashtra zone, under the theme *Samriddh Annadata, Samriddh Bharat*, Track A (Product or Technology).

**Sub-theme:** Farmer income protection, market access and digital crop-loss assessment.

**Live demo:** https://sanket1035.github.io/urja-shetkari/

## Problem
Farmers depend on one crop and are pushed into debt by irregular rain and drought. Government schemes already exist: PM-KUSUM, Magel Tyala Saur Krushi Pump, Mukhyamantri Saur Krushi Vahini (MSKVY) and GOBARdhan. But farmers don't know what they qualify for, installers are far away, and CBG plants struggle to collect dung from many small farms.

## What the prototype does
| Module | What it does |
|---|---|
| Scheme finder | The farmer enters land, distance to the nearest substation, pump HP, category and number of animals. The app lists the schemes they qualify for, their share of the cost in ₹, and the documents needed. |
| Dung collection | Farmers log dung by weight. A village collector delivers it to the CBG plant and the farmer is paid per kg over UPI. |
| Village installers | Suryamitra-trained local youth can be booked for installation and repair, which creates village jobs. |
| Solar monitor | An ESP32 with an INA219 sensor tracks pump output and alerts when the panels are dusty or faulty (simulated in the demo). |
| Market | Shows the nearest mandi (APMC), prices and market days in Marathi, and lets FPO members pool produce into one group lot to show dealers. Also lists fixed buyers beyond the crop: power (MSEDCL) and CBG (gas companies). No private dealer phone numbers are shown. |
| Crop loss | Explains the steps (e-Peek Pahani, crop insurance intimation within 72 hours, panchnama), gives a rainfall alert, and prepares a one-page evidence sheet with photo, location, time and survey number. It supports the official process and does not replace it. |
| Income view | Shows crop, solar, land lease and dung income together. |

The interface is in Marathi and English.

## Users
Small and marginal farmers, village youth and ITI students, FPOs and cooperatives, CBG plant operators, and gram panchayats and Krishi Sahayaks.

## Fit with the sub-theme
- **Income protection:** solar and CBG income that does not depend on the crop.
- **Market access:** mandi information and group lots, because dealers do not commit by phone without seeing the produce.
- **Digital crop-loss assessment:** e-Peek Pahani and the PMFBY app already exist. This project fills the gap between them with reminders and an evidence sheet. Whether it speeds up claims is not proven and will be tested in the pilot.

## Status
This is an early prototype that runs on **sample data**. Mandi prices and rainfall thresholds are samples. Subsidy figures are indicative and must be verified with MSEDCL, MNRE and the GOBARdhan portal. The hardware monitor is simulated.

## Roadmap (3-month pilot)
1. **Month 1:** Survey one village near Nashik, interview 10-20 farmers, put the MVP online, form the farmer group.
2. **Month 2:** File solar pump scheme applications, fit the IoT monitor on 3-5 pumps, start dung collection, set up a small biogas unit.
3. **Month 3:** Train 10-20 village youth, test the group lot and the crop-loss evidence sheet, measure results and report.
4. **After 3 months:** Scheme-approved solar pumps (the approval process can take roughly 75-100 days), a GOBARdhan CBG plant, and more villages.

## Run
It is a single static file. Open `index.html` in a browser, or enable GitHub Pages on the main branch.

## Author
Ashish Patil (आशिष पाटील) · Proposed by Aashunik Foundation / Aashunik Skill Workforce Pvt. Ltd.
