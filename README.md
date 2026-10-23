# Urja Shetkari (उर्जा शेतकरी)

**From food provider to energy provider.** This platform helps small farmers earn from solar power and biogas alongside their crops.

Submitted to the **Seva First Innovation Challenge 2026** (Ministry of Education) under the theme *Samriddh Annadata, Samriddh Bharat*, Track A (Product or Technology).

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
| Income view | Shows crop, solar, land lease and dung income together. |

The interface is in Marathi and English.

## Users
Small and marginal farmers, village youth and ITI students, FPOs and cooperatives, CBG plant operators, and gram panchayats and Krishi Sahayaks.

## Status
This is an early prototype that runs on **sample data**. Subsidy figures are indicative and must be verified with MSEDCL, MNRE and the GOBARdhan portal. The hardware monitor is simulated.

## Roadmap
1. Survey 10–20 farmers in one village near Nashik.
2. Build an MVP with a backend (Firebase or Supabase) and a real ESP32 monitor.
3. Pilot with one FPO and one CBG unit.
4. Add a WhatsApp/IVR version for farmers without smartphones.

## Run
It is a single static file. Open `index.html` in a browser, or enable GitHub Pages on the main branch.

## Author
Ashish Patil (आशिष पाटील) · Proposed by Aashunik Foundation / Aashunik Skill Workforce Pvt. Ltd.
