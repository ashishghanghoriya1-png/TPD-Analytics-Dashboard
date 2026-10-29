# Madhya Pradesh Teacher Professional Development (TPD) Analytics Dashboard (2022-2026)

Interactive executive analytics dashboard evaluating statewide teacher capacity-building interventions across Madhya Pradesh from 2022 to 2026.

---

## Executive Overview

* **Verified Government Teachers:** 205,657 unique civil servants matching confirmed state HRMS employee codes (`AA1234` format).
* **Multi-Year Retention:** 162,955 teachers (79.2%) participated in training across two or more separate school years.
* **Active Cohort This Year (2025-26):** 71,593 teachers actively engaged in ongoing school cluster meetings and digital modules.
* **Geographic Reach:** 100% saturation across all 55 administrative districts of Madhya Pradesh.
* **Classroom Pedagogy Score:** 78.0% average score on objective curriculum pedagogy assessments.
* **Classroom Practice Submissions:** 74,562 structured teaching logs submitted by educators.

---

## Live Dashboard on GitHub Pages

This repository is formatted for instant deployment via **GitHub Pages**:
1. Open repository **Settings**.
2. Click **Pages** in the left sidebar.
3. Under **Build and deployment > Source**, select **Deploy from a branch**.
4. Choose **main** (or **master**) branch and `/ (root)` folder, then click **Save**.
5. Your interactive dashboard will be live at `https://<your-username>.github.io/<repository-name>/`.

---

## Key Dashboard Features

* **Longitudinal Slicing:** Interactive tabs for 2022, 2023, 2024, 2025, and 2026 with real-time recalculation.
* **Channel Bifurcation:** Filter by Online Courses (DIKSHA), In-Person Training, Cluster Meetings (CLSS), or District Orientations (DO).
* **Course-Wise Selector:** Nested dropdown under Online Courses to analyze specific courses (Mission Ankur, PSP, ECE, NAS/PLC) with completion rates and learning shifts.
* **Monthly Trajectory Panel:** Interactive 48-month timeline comparing monthly inflows against cumulative progression.
* **Zero Dependencies:** Built entirely with standalone HTML5, CSS3, and modern JavaScript with embedded SVG graphics.

---

## Data Governance & Audit Status

All metrics reconcile directly with state HRMS registries, DIKSHA telemetry exports, and physical session rosters with zero mathematical delta:
* **Total Training Activity Records:** 920,559
* **Total Registered Portal Profiles:** 386,710
* **Verified Civil Servant Teachers:** 205,657
* **Unmapped Portal Logins Segregated:** 181,053 (Guest accounts and unvalidated logins kept separate to protect civil service audit integrity).
