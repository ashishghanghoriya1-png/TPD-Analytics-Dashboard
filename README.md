# Madhya Pradesh Teacher Professional Development Analytics Dashboard (FY 2022-23 to FY 2026-27)

Interactive executive analytics dashboard evaluating statewide teacher capacity-building interventions across Madhya Pradesh from FY 2022-23 to FY 2026-27. All metrics follow the official Indian Financial Year cycle (1 April to 31 March).

---

## Executive Overview

* Verified Government Teachers: 205,657 unique civil servants matching confirmed state HRMS employee codes (AA1234 format).
* Multi-Year Retention: 162,955 teachers (79.2%) participated in training across two or more separate Financial Years.
* Active Cohort in Latest Full FY (2025-26): 119,304 verified teachers actively engaged across digital courses and monthly cluster dialogues.
* Active Cohort in Ongoing FY 2026-27: 33,607 verified teachers engaged in CLSS Rounds 6 and 7 (August and September 2026).
* Geographic Reach: 100% saturation across all 55 administrative districts of Madhya Pradesh.
* Classroom Pedagogy Score: 78.0% average score on objective curriculum pedagogy assessments.
* Classroom Practice Submissions: 74,562 structured teaching logs submitted by educators.

---

## Financial Year Cohort Summary (1 April to 31 March)

| Financial Year | Dates Covered | Total Activity Records | Mapped Records | Verified Civil Servant Teachers | Retention from Prior FYs | Primary Interventions Active |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| FY 2022-23 | 1 Apr 2022 to 31 Mar 2023 | 173,312 | 157,905 | 129,090 | Baseline | Mission Ankur Course 1, PSP Batches 1 & 2 |
| FY 2023-24 | 1 Apr 2023 to 31 Mar 2024 | 225,741 | 212,135 | 129,432 | 103,650 (80.3%) | Mission Ankur Courses 2 & 3, PSP 3, General Pedagogy |
| FY 2024-25 | 1 Apr 2024 to 31 Mar 2025 | 247,346 | 181,710 | 107,875 | 76,403 (70.8%) | Subject Pedagogy, NAS Course, Mission Ankur 4-6, PSP 4-5, ECE 1-6 |
| FY 2025-26 | 1 Apr 2025 to 31 Mar 2026 | 227,206 | 193,045 | 119,304 | 103,127 (86.4%) | PLC Digital Course, CLSS Rounds 1 to 5 (Aug, Sep, Nov, Dec 2025, Jan 2026), DO 1-5 |
| FY 2026-27 | 1 Apr 2026 to 31 Mar 2027 | 46,954 | 46,630 | 33,607 | 31,300 (93.1%) | CLSS Rounds 6 & 7 (Aug & Sep 2026), DO Rounds 6 & 7 |
| All FYs Cumulative | 1 Apr 2022 to 30 Sep 2026 | 920,559 | 791,425 | 205,657 | 162,955 (79.2%) | All 19 State Training Interventions |

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

* Financial Year Slicing: Interactive buttons for FY 2022-23, FY 2023-24, FY 2024-25, FY 2025-26, and FY 2026-27 with real-time card and chart updates.
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
