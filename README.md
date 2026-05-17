# Echocardiogram (ECHO) Process Improvement & Revenue Analysis
### Cook County Health — Cardiology Department

> **Presented to C-suite leadership at Cook County Health**
> Projected impact: **+1 Echo procedure per technologist per day** → estimated **$900,000 in annual revenue recovery**

---

## Project Overview

This project was completed in partnership with the Cardiology Echo department at **Cook County Health**, one of the largest public health systems in the United States. The engagement spanned two parallel workstreams: **operational process improvement** and **financial/billing analysis** of FY 2025 Echocardiology revenue.

The goal was to identify inefficiencies in both inpatient and outpatient echocardiogram workflows, apply Lean methodology to recommend improvements, and evaluate the department's financial performance to surface billing disparities.

Findings and recommendations were presented directly to C-suite leadership at Cook County Health.

---

## The Problem

The Echo department was performing **5–6 procedures per technologist per day** and wanted to increase throughput. Initial observation and data collection revealed significant time being lost across every procedure type:

| Procedure | Path | Current Mean Time |
|---|---|---|
| Regular Echo | Inpatient | 68.7 min |
| Contrast Study | Inpatient | 61.0 min |
| TEE Study | Inpatient | 59.0 min |
| Bubble Study | Inpatient | 68.3 min |
| Regular Echo | Outpatient | 64.5 min |
| Contrast Study | Outpatient | 72.2 min |

---

## Methodology

### Data Collection — Custom Mobile App
To capture granular, real-time data, we deployed a **custom-built mobile application (Tech Time Tracker)** to Echo technologists. The app recorded timestamped durations for each step of the procedure workflow, enabling procedure-level analysis that would not have been possible with existing records.

### Process Mapping
Separate process maps were built for inpatient and outpatient workflows, reflecting their distinct complexity levels and sources of variability.

### Lean Waste Analysis — TIMWOODS Framework
All identified inefficiencies were categorized using the **TIMWOODS framework** (Transportation, Inventory, Motion, Waiting, Overproduction, Overprocessing, Defects, Skills):

| Waste Type | Inpatient | Outpatient | Key Causes |
|---|---|---|---|
| Waiting | 35% | 64% | Nurse unavailability, IV delays, room conflicts, no pre-scheduling |
| Transportation | 26% | 4% | Elevator delays, repeated floor travel, fragmented workflow |
| Skills | 9% | 14% | Techs assisting with food trays, restroom help, unclear role boundaries |
| Defects | 9% | 11% | SkyView login failures, incorrect order types, machine crashes |
| Inventory | 6% | 0% | Contrast agents not pre-stocked, no standardized protocols |
| Motion | 6% | — | Repeated corridor travel, no standardized travel sequence |

### Spaghetti Diagram Analysis
Outpatient movement tracking revealed:
- **116 average steps per encounter**
- **28% of encounters exceeded 200 steps**, linked to room conflicts and delays
- Southern Echo rooms added significant unnecessary distance per trip
- Workroom 2831 (isolated at far east wall) forced techs to cross the full floor for every supply run

---

## Key Findings

1. **Waiting is the #1 waste in both pathways** — inpatient and outpatient
2. **IV placement accounts for 46% of all outpatient delay events** (12 of 26 flagged records)
3. **SkyView login failures add 5–10 minutes per encounter** — tech prep outliers showed a max of 31.2 minutes vs. a mean of 2.7 minutes
4. **Inpatient tech prep had a standard deviation of 20.2 minutes** — driven by floor travel without first confirming patient availability
5. **Rooming delays spiked to 48.3 minutes max** (vs. 3.9 minute mean) due to room conflicts with Holter monitor patients
6. **Provident site averages 17 minutes longer than Stroger** — a site-specific transport protocol gap

---

## Recommendations

Eight recommendations were developed, classified as Immediate or Structural:

| ID | Priority | Recommendation | Problem Addressed | Impact |
|---|---|---|---|---|
| R1 | Immediate | Patient Ready Confirmation Call | Patient not in room / unavailable | Cuts prep time 6.6 → 2.4 min; IP echo ~58–62 min |
| R2 | Immediate | IV Pre-Placement for Outpatient Contrast | 46% of outpatient IV wait | Outpatient contrast: 72.2 → 62–67 min |
| R3 | Immediate | Nurse Pre-Notification Protocol | Nurse unavailability, IV delays | Tech prep 6.1 → 3 min |
| R4 | Immediate | SkyView IT Fix — Session Persistence | 5–10 min system crashes | Eliminates crashes per affected visit |
| R5 | Immediate | Pre-Scan Restroom Prompt | Mid-exam interruptions | Removes 3–5 min delays |
| R6 | Immediate | Shift-Start 5S Supply Checklist | Supply retrieval delays | Removes 3–10 min delays |
| R7 | Structural | Room Pre-Assignment with Conflict Check | Holter monitor room overlap | Rooming: 48.3 min max → 2.4 min median |
| R8 | Structural | Provident Transport Protocol | 17-min gap vs. Stroger | Total time: 78 → ≤65 min |

---

## Projected Outcomes

| Metric | Before | After Lean Implementation |
|---|---|---|
| Regular Echo (Inpatient) | 68.7 min | 58–62 min (▼ 7–11 min) |
| Contrast Study (Inpatient) | 61.0 min | 55–60 min (▼ 5–10 min) |
| TEE Study (Inpatient) | 59.0 min | 50–55 min (▼ 5–9 min) |
| Contrast Study (Outpatient) | 72.2 min | 62–67 min (▼ 10–16 min) |
| **Throughput per tech per day** | **5–6 procedures** | **+1 additional procedure/tech/day** |
| **Estimated annual impact** | — | **~$900,000 in revenue recovery** |

---

## Financial Analysis — FY 2025

A separate analysis of the department's billing data revealed the full financial scope of the operation and identified site-specific disparities:

| Metric | Value |
|---|---|
| Total Charges | $6,867,080 |
| Facility (Hospital) Fees | $5,933,187 (86% of charges) |
| Professional Fees | $933,893 (14% of charges) |
| Total Encounters | 9,989 |
| Top Procedure | ECHO TTE Complete w/ Contrast ($4.86M) |

**Key billing finding:** Professional fees account for 57% of record volume but only 14% of charges — a structural disparity driven by the low average charge per professional fee record (~$163 vs. ~$1,392 for facility fees). Several procedure types had no corresponding CPA charge entries, indicating a billing gap requiring reconciliation.

---

## Tools & Methods

- **Excel** — financial modeling, billing data analysis, charge/volume architecture
- **Custom mobile app** — real-time timestamped data collection (Tech Time Tracker)
- **Lean / TIMWOODS framework** — waste identification and classification
- **Spaghetti diagramming** — movement and motion analysis
- **Process mapping** — inpatient and outpatient workflow documentation
- **Statistical analysis** — procedure-level outlier detection (mean, max, standard deviation)

---

## Team

Zanib Hasson · Nabila Baklia · Umar Arif · Ali Choudhry
Faculty Advisor: Prof. Chandrasekaran Ranga · TA: Sonali Bondre

*Cook County Health Mentors: Dr. Doukky, Mr. Mazin, Mrs. Johnson, Dr. Outler, Mrs. Amanda Grasso, Mrs. Andrea Gibson, Dr. Mikaitis*

