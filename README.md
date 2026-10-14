# WASTEWISE

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-waste_management-lightgrey)

> Anticloud-hardened packaging of the upstream project `WASTEWISE` in category **WASTE MANAGEMENT**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** WASTE MANAGEMENT · **Upstream:** https://github.com/GDSC-ZHCET/WasteWise · **Upstream pin:** `5cdfa2ae5ed8ec04d97fc93cc24161bb9c880de5` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# 📌 Overview
**WasteWise** is a community-driven waste management platform that helps individuals and organizations track, manage, and recycle waste efficiently. The platform leverages AI/ML-based waste categorization, real-time waste tracking, and community engagement to promote responsible waste disposal. Built using Next.js, Firebase Firestore, and Google’s Gemini AI, WasteWise offers an interactive web experience with gamified rewards for eco-friendly actions.

# 🎯 Problem Statement
The growing crisis of **e-waste** and improper waste disposal is a significant environmental challenge, leading to pollution, health hazards, and inefficient recycling processes. **WasteWise** encourages better waste segregation, responsible disposal, and community-driven solutions to mitigate these issues.

# 🌍 Sustainable Development Goals (SDG)
WasteWise aligns with:
- **SDG 11 (Sustainable Cities and Communities)** – Promoting efficient waste management practices.
- **SDG 12 (Responsible Consumption and Production)** – Encouraging sustainable waste disposal and recycling.
- **SDG 13 (Climate Action)** - Proper waste management reduces landfill waste, lowers greenhouse gas emissions, and minimizes environmental pollution.
  
# 🚀 Features
### 🏡 Community Forum
- Users can share best practices, ideas, and environmental initiatives.
- Discussion threads on sustainable waste management.

### 🤖 AI-powered Waste Categorization
- Google’s **Gemini AI** helps classify waste items for better segregation.
- Provides disposal recommendations based on waste type.

### 📚 Educational Hub
- Learn about sustainable waste disposal methods.
- Access resources on waste recycling and management.

# 🔧 Tech Stack
| Component       | Technology Used             |
|----------------|----------------------------|
| **Frontend**   | Next.js (React framework)  |
| **Backend**    | Firebase Firestore (NoSQL) |
| **Authentication** | NextAuth (Google Provider) |
| **AI Component** | Google Gemini 2.0 Flash-exp |
| **Security**   | Firebase token verification, Secure API handling |
| **Hosting**    | Vercel                      |

# 📊 Process Flow
![1. **User Authentication** – Secure sign-in via Google authentication.
2. **Community Engagement** – Post, like, and comment on waste management discussions.
3. **AI Categorization** – Upload images of waste items to get AI-powered classification.
5. **Real-time Updates** – Stay updated with waste tracking progress and community discussions.](https://github.com/user-attachments/assets/f28e8ff8-466a-4d56-a20b-40c797e6591f)

# 🏗️ System Architecture
![The system consists of:
**Frontend**: Next.js web application.
**Backend**: Firebase Firestore for real-time data handling.
**AI Component**: Gemini AI for waste categorization.
**Authentication & Security**: Firebase Authentication and secure API routes.
**Hosting & Deployment**: Vercel for frontend, Firebase for backend services.](https://github.com/user-attachments/assets/3ea6c5f0-c53c-414f-a89f-560344789788)

# 🛠️ Installation & Setup
### 🚀 Backend Setup
source the project:
```bash
git source https://github.com/GDSC-ZHCET/WasteWise.git
cd WasteWise
```
Install dependencies:
```bash
npm install
```
Set up Firebase credentials in `.env` and start the backend:
```bash
npm start
```

### 🌐 Frontend Setup
Navigate to the frontend directory:
```bash
cd frontend
```
Install dependencies:
```bash
npm install
```
Run the Next.js development server:
```bash
npm run dev
```

# 📽️ Deployment URLs, Demo Video & Screenshots
🔗 **Live Dashboard**: [WasteWise Dashboard](https://wastewise-beige.vercel.app/)
🔗 **GitHub project**: [GitHub Link](https://github.com/GDSC-ZHCET/WasteWise.git)
📽 **Watch Demo Video**: [Demo Video](#) 

# 📌 Future Enhancements
- **Expand to Mobile App** – Develop an Android/iOS version.
- **AI-powered Waste Sorting** – Improve waste classification accuracy.
- **More Robust Reward-based Gamification** – Enhance user engagement.

# 📜 License
This project is licensed under the **MIT License**.

# 👨‍💻👩‍💻 Our Team
We are a team of engineers from **Zakir Husain College of Engineering and Technology, AMU**, and part of **Google Developer Student Clubs (GDSC) - ZHCET**.

- **Arslaan Azam** – [LinkedIn](https://www.linkedin.com/in/mohdarslaanazam/) | [Email](mailto:mohdarslaanazam@gmail.com)
- **Quteba Ahsan** – [LinkedIn](https://www.linkedin.com/in/quteba-ahsan-6529992a1) | [Email](mailto:qutebaahsan@gmail.com)
- **Roshaid Atique** – [LinkedIn](https://www.linkedin.com/in/roshaid-atique-020052287) | [Email](mailto:roshaid2004@gmail.com)
- **Shashank Chauhan (Team Lead)** – [LinkedIn](https://www.linkedin.com/in/shashank-chauhan-b492a1311) | [Email](mailto:shashankchauhan2518@gmail.com)

Thank you for checking out **WasteWise**! 🚀

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `backend/`, `frontend/`
- Snapshot size: **51 files**, **1550 lines of code** (measured; see Benchmarks)
- Primary languages: `.js` (16), `.jsx` (14), `.svg` (5), `.json` (4), `.mjs` (4), `(none)` (3)
- Upstream commit pinned for this packaging: `5cdfa2ae5ed8ec04d97fc93cc24161bb9c880de5`

---

## Installation

No installation section was found in the upstream readme, so the commands below are generated from the manifests detected in this project directory.

```sh
# No standard manifest detected. Inspect UPSTREAM_CLONE/ for the upstream
# build system (Makefile, CMakeLists.txt, configure, ...) and follow it.
```

Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

No usage section was found in the upstream readme. Entry points detected in this project directory:

Browse the snapshot layout listed under What This Project Does and follow the upstream run instructions for the detected ecosystem (Unknown (no standard manifest detected)).

Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

The upstream API surface is defined by the `WASTEWISE` source tree vendored in `UPSTREAM_CLONE/` (Unknown (no standard manifest detected) ecosystem). Public entry points:

- Source modules: `backend/`, `frontend/`
- The snapshot declares 17 dependency references across 1 ecosystem(s); see Dependencies below.
- Overlay API: `anticloud/cli.py` exposes 13 subcommands with JSON stdout; `anticloud/bench/runner.py` runs the 16-check suite; `anticloud/provenance/chain.py` exposes the SHA3-256 + Ed25519 provenance chain.

---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 51 |
| Lines of code | 1550 |
| Dependency references | 17 |
| Dependencies by ecosystem | npm: 17 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | @google/generative-ai | ^0.21.0 | frontend/package.json |
| npm | dotenv | ^16.4.7 | frontend/package.json |
| npm | firebase | ^11.2.0 | frontend/package.json |
| npm | firebase-admin | ^13.1.0 | frontend/package.json |
| npm | framer-motion | ^12.0.11 | frontend/package.json |
| npm | lucide-react | ^0.474.0 | frontend/package.json |
| npm | next | ^15.1.5 | frontend/package.json |
| npm | next-auth | ^4.24.11 | frontend/package.json |
| npm | react | ^19.0.0 | frontend/package.json |
| npm | react-dom | ^19.0.0 | frontend/package.json |
| npm | tailwind-scrollbar | ^3.1.0 | frontend/package.json |
| npm | zod | ^3.24.1 | frontend/package.json |
| npm | @eslint/eslintrc | ^3 | frontend/package.json |
| npm | eslint | ^9 | frontend/package.json |
| npm | eslint-config-next | 15.1.5 | frontend/package.json |
| ... | (2 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- None detected at the snapshot root; consult the upstream documentation link in the Upstream section.

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `WASTEWISE` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
MIT License

Copyright (c) 2025 GDGC ZHCET

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `WASTEWISE` (category: WASTE MANAGEMENT)
- **Upstream URL:** https://github.com/GDSC-ZHCET/WasteWise
- **Pinned commit (SHA):** `5cdfa2ae5ed8ec04d97fc93cc24161bb9c880de5`
- **Branch:** master
- **Pin provenance:** GitHub API commits/master. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`1721e21ac7795fe5e6f0d4ebb22b0d9a3b5d5f7048e6d64c28743fcd6f0b4735`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

