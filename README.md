# AVIXA CTS Exam Study Guide & 1,000-Question Exam Simulator

> 🌐 **Live Web Application:** Take practice exams instantly in your browser at:  
> **👉 [https://deekaycode.github.io/cts-study-guide/](https://deekaycode.github.io/cts-study-guide/)**  
> *(You can also access the live site directly from the **Deployments** / **github-pages** section on the right sidebar of this repository — **no git pull, clone, or installation needed!**)*

A lightweight, responsive practice exam simulator and comprehensive study guide tailored specifically for the **AVIXA Certified Technology Specialist (CTS)** credential.

Contains **1,000 scenario-based questions** strictly modeled after the real CTS exam difficulty, testing project management processes, trade demarcation, contracts, CSI MasterFormat, DISCAS, audio formulas, video standards, and systematic troubleshooting.

---

## 🚀 How to Access (Online or Offline)

### 🌐 Option 1: Direct Online Access (Instant — No Git Pull or Download Needed)
Open the deployed web application directly in any browser on desktop, tablet, or mobile:  
👉 **[https://deekaycode.github.io/cts-study-guide/](https://deekaycode.github.io/cts-study-guide/)**  
*(Also accessible from the **Deployments** panel on the right sidebar of the GitHub repo page).*

### 💻 Option 2: 1-Click Windows Offline Launcher
If you prefer running offline locally, download or clone the repository and double-click:  
**`run_study_guide.bat`**  
It launches the exam simulator immediately in your default browser with zero setup.

### 📱 Option 3: Local Browser Launch (macOS, Linux, Chromebook, Windows)
Simply double-click or open **[`index.html`](index.html)** in any web browser (Chrome, Firefox, Safari, Edge, Brave).  
The full 1,000-question database is bundled in `questions_data.js`, allowing 100% offline functionality with zero CORS restrictions.

---

## 🎯 Exam Structure & Official AVIXA Scoring Guidelines

This study guide faithfully implements the official **AVIXA Exam Content Outline (ECO)** and scoring guidelines:

### 1. Domain Weighting (100 Questions Sampled per Exam)
Every exam session randomly draws **100 questions** from the 1,000-question pool weighted strictly according to AVIXA domain proportions:

| Domain | Category Name | Official Weight | Questions Picked | Scaled Max | Total Pool |
| :--- | :--- | :---: | :---: | :---: | :---: |
| **Domain A** | Creating AV Solutions | **35%** | **35 Questions** | 175 Points | **350 Questions** |
| **Domain B** | Implementing AV Solutions | **30%** | **30 Questions** | 150 Points | **300 Questions** |
| **Domain C** | Supporting AV System Operation | **15%** | **15 Questions** | 75 Points | **150 Questions** |
| **Domain D** | Servicing AV Solutions | **20%** | **20 Questions** | 100 Points | **200 Questions** |
| **TOTAL** | Full CTS Exam | **100%** | **100 Questions** | **500 Points** | **1,000 Questions** |

### 2. Official Scaled Scoring (0 – 500 Scale)
* **Passing Score:** A scaled score of **350 or higher** (out of 500 points) is required to pass (approx. 70%).
* **Pass / Fail Status Banner:** Displayed immediately upon exam submission.
* **Domain Performance Breakdown Table:** Displays raw correct answers, percentage score, scaled points, and competency rating (*Proficient*, *Borderline*, or *Needs Review*) for each of the four exam domains.

### 3. Review Questions Answered Incorrectly
* The results page displays technical explanations **only for questions answered incorrectly**, helping you target weak areas efficiently.
* For every missed question:
  - Question text, domain, and subtopic
  - Your selected answer (highlighted in red)
  - The correct answer (highlighted in green)
  - Detailed technical explanation covering the underlying standard, formula, or contractual rule
* **Targeted Retake:** Click **"🎯 Retake Missed Questions Only"** to immediately re-test yourself on missed questions until reaching 100% mastery.

---

## ⌨️ Keyboard Shortcuts

Speed up practice test taking with keyboard shortcuts:
* `1` or `A`: Select Option A
* `2` or `B`: Select Option B
* `3` or `C`: Select Option C
* `4` or `D`: Select Option D
* `F`: Mark / Unmark current question for review
* `Right Arrow`: Next question
* `Left Arrow`: Previous question

---

## 📁 Repository Files

* **[`index.html`](index.html)**: Clean, responsive single-page exam application.
* **[`questions_data.js`](questions_data.js)**: Pre-compiled standalone JavaScript data payload enabling zero-dependency offline execution.
* **[`questions.json`](questions.json)**: Complete JSON database of 1,000 categorized questions with answers and explanations.
* **[`questions.csv`](questions.csv)**: Standard CSV export of all 1,000 questions for Excel, Google Sheets, or flashcard (Anki) import.
* **[`run_study_guide.bat`](run_study_guide.bat)**: Windows 1-click launcher.

---

## 📝 Study Topics Covered

* **Domain A (Creating AV Solutions)**: Needs analysis, stakeholder discovery, RFIs, RFPs, Program Reports, CSI MasterFormat (Divisions 01, 26, 27, 28), site surveys, ambient light (lux/fc), DISCAS (ADM/BDM), room acoustics ($RT_{60}$, STC, NRC, NC curves), decibel calculations (power & voltage), throw distance, conduit fill (NEC 40%/31%/53%), Ohm's law, and thermal cooling (BTU/CFM).
* **Domain B (Implementing AV Solutions)**: Cable pathways, NEC codes (Article 725 Class 2, Article 800, Article 640), plenum CMP vs riser CMR vs CM, balanced audio, differential CMRR, XLR pinouts, phantom power (+48V), gain staging, automixers (Dugan vs gating, NOM), AEC reference routing, compressors/limiters, 70V/100V distributed audio, EDID & HDCP handshakes, HDMI 2.0/2.1, DisplayPort, HDBaseT 5Play, fiber optics (Single-mode vs Multi-mode OM3/OM4), IP networking (IPv4, subnets, VLANs, IGMP Snooping & Querier for multicast AVoIP), Dante/AES67 (PTP IEEE 1588, QoS DSCP), PoE (802.3af/at/bt), RS-232/422/485, and equipment rack layout/cooling/grounding.
* **Domain C (Supporting AV Operations)**: End-user training methodologies (Train-the-Trainer, QRGs, adult learning), meeting operations, Unified Communications (Teams Rooms, Zoom Rooms, BYOD USB-C), microphone handling and proximity effect, preventive maintenance schedules (filter cleaning, UPS battery cycles, laser phosphor lifespan), config backups, SLAs (MTTR, MTBF, response vs resolution time), and remote monitoring (SNMPv3 traps, cloud IoT).
* **Domain D (Servicing AV Solutions)**: AVIXA systematic 6-step troubleshooting methodology, half-split technique, trade demarcation, 60 Hz AC hum vs 120 Hz buzz, ground loop isolation, pin 1 problem (AES48), feedback elimination, digital cliff effect, digital sparkles, EDID emulation, HDCP key limit exhaustion, cable testing (TDR, wiremap, certification, fiber OTDR), multimeter diagnostics (AC outlet voltages, speaker DC resistance), multicast packet storms, and serial null-modem pinouts.
