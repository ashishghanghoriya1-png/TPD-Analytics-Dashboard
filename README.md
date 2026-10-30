# Madhya Pradesh Teacher Professional Development Analytics Dashboard (AY 2022-23 to AY 2026-27)

Interactive executive analytics dashboard evaluating statewide teacher capacity-building interventions across Madhya Pradesh from AY 2022-23 to AY 2026-27. All metrics follow the official Indian Academic Year cycle (1 April to 31 March).

---

## Executive Overview

* Verified Government Teachers: 205,657 unique civil servants matching confirmed state HRMS employee codes (AA1234 format).
* Multi-Year Retention: 162,955 teachers (79.2%) participated in training across two or more separate Academic Years.
* Active Cohort in Latest Full AY (2025-26): 119,304 verified teachers actively engaged across digital courses and monthly cluster dialogues.
* Active Cohort in Ongoing AY 2026-27: 33,607 verified teachers engaged in CLSS Rounds 6 and 7 (August and September 2026).
* Geographic Reach: 100% saturation across all 55 administrative districts of Madhya Pradesh.
* Classroom Pedagogy Score: 78.0% average score on objective curriculum pedagogy assessments.
* Classroom Practice Submissions: 74,562 structured teaching logs submitted by educators.


---

## Timeline Period Segregation: Covid vs Post-Covid

The dashboard provides top-level timeline segregation across the two major operational eras of teacher capacity-building in Madhya Pradesh:

1. **Covid Period (Before April 2023 - AY 2022-23):**
   * **Focus:** Remote digital training on the DIKSHA mobile app while physical schools and group meetings were suspended.
   * **Key Interventions:** Mission Ankur Course 1, Professional Support Program (PSP Batches 1 & 2).
   * **Reach:** 129,090 verified government civil servants across 173,312 activity records.
   * **In-Person & Cluster Dialogues:** 0 (Suspended for health precautions).

2. **Post-Covid Period (After April 2023 - AY 2023-24 to AY 2026-27):**
   * **Focus:** Blended teacher development combining monthly in-person school cluster dialogues (CLSS), subject pedagogy workshops, district trainer orientations (DO), and online communities.
   * **Key Interventions:** Mission Ankur Courses 2 to 6, CLSS Rounds 1 to 7, Subject Pedagogy 2024, PLC Digital Course, NAS Assessment Course.
   * **Reach:** 193,754 verified government teachers across 747,247 activity records.
   * **Continuation from Covid Period:** 118,016 teachers (91.4% continuation rate from the initial Covid cohort into Post-Covid blended training).
---

## Timeline Period & Academic Year Summary

| Academic Year | Dates Covered | Total Activity Records | Mapped Records | Verified Civil Servant Teachers | Retention from Prior FYs | Primary Interventions Active |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| AY 2022-23 | 1 Apr 2022 to 31 Mar 2023 | 173,312 | 157,905 | 129,090 | Baseline | Mission Ankur Course 1, PSP Batches 1 & 2 |
| AY 2023-24 | 1 Apr 2023 to 31 Mar 2024 | 225,741 | 212,135 | 129,432 | 103,650 (80.3%) | Mission Ankur Courses 2 & 3, PSP 3, General Pedagogy |
| AY 2024-25 | 1 Apr 2024 to 31 Mar 2025 | 247,346 | 181,710 | 107,875 | 76,403 (70.8%) | Subject Pedagogy, NAS Course, Mission Ankur 4-6, PSP 4-5, ECE 1-6 |
| AY 2025-26 | 1 Apr 2025 to 31 Mar 2026 | 227,206 | 193,045 | 119,304 | 103,127 (86.4%) | PLC Digital Course, CLSS Rounds 1 to 5 (Aug, Sep, Nov, Dec 2025, Jan 2026), DO 1-5 |
| AY 2026-27 | 1 Apr 2026 to 31 Mar 2027 | 46,954 | 46,630 | 33,607 | 31,300 (93.1%) | CLSS Rounds 6 & 7 (Aug & Sep 2026), DO Rounds 6 & 7 |
| All AYs Cumulative | 1 Apr 2022 to 30 Sep 2026 | 920,559 | 791,425 | 205,657 | 162,955 (79.2%) | All 19 State Training Interventions |

---

## Live Dashboard on GitHub Pages

This repository is formatted for instant deployment via GitHub Pages:
1. Open repository Settings.
2. Click Pages in the left sidebar.
3. Under Build and deployment > Source, select Deploy from a branch.
4. Choose main branch and / (root) folder, then click Save.
5. Your interactive dashboard will be live at https://<your-username>.github.io/<repository-name>/.

---

## Key Dashboard Features

* Academic Year Slicing: Interactive buttons for AY 2022-23, AY 2023-24, AY 2024-25, AY 2025-26, and AY 2026-27 with real-time card and chart updates.
* Channel Bifurcation: Filter by Online Courses (DIKSHA), In-Person Training, Cluster Meetings (CLSS), or District Orientations (DO).
* Course-Wise Selector: Nested dropdown under Online Courses to analyze specific courses with completion rates and learning shifts.
* Monthly Trajectory Panel: Interactive 48-month timeline comparing monthly inflows against cumulative progression.
* Zero External Dependencies: Built entirely with standalone HTML5, CSS3, and JavaScript with embedded SVG graphics.
* Executive Access Protection: Integrated cryptographic access gate using SHA-256 validation to restrict executive analytics and civil service data to authorized reviewers. Includes one-click Lock action and session persistence.

---

## Data Governance & Audit Status

All metrics reconcile directly with state HRMS registries, DIKSHA telemetry exports, and physical session rosters with zero mathematical delta:
* Total Training Activity Records: 920,559
* Total Registered Portal Profiles: 386,710
* Verified Civil Servant Teachers: 205,657
* Unmapped Portal Logins Segregated: 181,053 (Guest accounts and unvalidated logins kept separate to protect civil service audit integrity).
