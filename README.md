<!-- ============================================================ -->
<!--  GitHub Profile README · Aviral Goyal (@avviiiral)            -->
<!--  Paste into the repo named exactly: avviiiral/avviiiral      -->
<!-- ============================================================ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,100:1f6feb&height=120&section=header&text=Aviral%20Goyal&fontSize=46&fontColor=ffffff&fontAlignY=55" alt="Aviral Goyal" width="100%" />

<a href="https://aviral-goyal.netlify.app/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3200&pause=900&color=58A6FF&center=true&vCenter=true&width=640&lines=Full-Stack+%26+Computer+Vision+Engineer;Django+%C2%B7+Angular+%C2%B7+OpenCV+%C2%B7+YOLOv8+%C2%B7+PyTorch;Industrial+automation+%E2%86%94+vision+%E2%86%94+analytics" alt="Typing SVG" />
</a>

<p>
  <a href="https://aviral-goyal.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-aviral--goyal.netlify.app-1f6feb?style=flat-square&logo=netlify&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/avviiiral/"><img src="https://img.shields.io/badge/LinkedIn-avviiiral-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/avviiiral"><img src="https://img.shields.io/badge/GitHub-@avviiiral-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

</div>

---

### `> whoami`

I build **end-to-end systems** — from the camera stream and the PLC on the shop floor, through the Django/Angular application layer, to the analytics that turn raw signals into decisions.

```yaml
role:      Full-Stack & Computer Vision Engineer
bridges:   [industrial automation, computer vision, data & financial analytics]
builds:    Python · Django · Angular · OpenCV · YOLOv8 · PyTorch
approach:  ship working pipelines → measure → harden
```

---

### 🧰 Core Stack & Systems

| Domain | Stack |
|:--|:--|
| **Backend & Web** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![ASGI / Uvicorn](https://img.shields.io/badge/ASGI%20%2F%20Uvicorn-499848?style=flat-square&logo=gunicorn&logoColor=white) ![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat-square&logo=sass&logoColor=white) |
| **Computer Vision & Edge / Industrial** | ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square&logo=ultralytics&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white) ![RTSP / MJPEG](https://img.shields.io/badge/RTSP%20%2F%20MJPEG-30363D?style=flat-square&logo=ffmpeg&logoColor=white) ![PLC / HMI](https://img.shields.io/badge/PLC%20%2F%20HMI-30363D?style=flat-square) ![Microcontrollers](https://img.shields.io/badge/Microcontrollers-00979D?style=flat-square&logo=arduino&logoColor=white) |
| **Data & Analytics** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Automated Ingestion](https://img.shields.io/badge/Automated%20Ingestion-30363D?style=flat-square) ![XIRR / Portfolio Analytics](https://img.shields.io/badge/XIRR%20%2F%20Portfolio%20Analytics-30363D?style=flat-square) ![QR / Invoice Parsing](https://img.shields.io/badge/QR%20%2F%20Invoice%20Parsing-30363D?style=flat-square) |

<details>
<summary><b>How the pieces connect</b></summary>

```text
 ┌──────────────┐   RTSP / MJPEG   ┌─────────────────────┐   REST / WS   ┌──────────────┐
 │ Cameras      │ ───────────────▶ │ OpenCV + YOLOv8     │ ────────────▶ │ Django (ASGI)│
 │ PLC / HMI    │ ───  signals ──▶ │ PyTorch (CUDA)      │               │ + Angular UI │
 │ MCUs         │                  └─────────────────────┘               └──────┬───────┘
 └──────────────┘                                                               │
                                                                     Pandas · reports · KPIs
```

</details>

---

### 🚀 Featured Work & Active Focus

| Project | What it does | Stack |
|:--|:--|:--|
| 💹 **[Personal Wealth Monitoring System (PWMS)](https://github.com/avviiiral/Personal_Wealth_Monitoring_System)** | Portfolio analytics platform tracking **Indian equities, mutual funds and bonds** — ISIN-based instrument mapping, automated NAV ingestion and **XIRR** return calculations. | `Django` `Angular` `Pandas` |
| 🎥 **BGLIIN.AI** | AI-powered **production monitoring** with live **multi-camera** vision analytics for the shop floor. | `Django` `Angular` `YOLOv8` `OpenCV` `PyTorch` |
| 🏭 **Industrial & Data Utilities** | Hardware-linked shop-floor workflows and Python automation tools — e.g. **QR / GST e-invoice** data-logging pipelines. | `Python` `PLC/HMI` `Pandas` |
| 🌐 **[Portfolio](https://aviral-goyal.netlify.app/)** | Projects, case studies and contact — the full picture in one place. | `Netlify` |

<details>
<summary><b>Example · PWMS holding snapshot</b> <i>(synthetic data)</i></summary>

| ISIN | Instrument | Type | Units | Invested (₹) | Current (₹) | XIRR |
|:--|:--|:--|--:|--:|--:|--:|
| `INF000X00001` | Sample Flexi Cap Fund – Direct | Mutual Fund | 125.400 | 25,000.00 | 27,310.00 | 9.8% |
| `INE000A00002` | Example Industries Ltd | Equity | 40 | 48,000.00 | 51,200.00 | 6.4% |
| `IN0000B00003` | Demo 7.10% Govt Bond 2034 | Bond | 10 | 10,000.00 | 10,240.00 | 7.1% |

<sub>Illustrative rows only — no real holdings, prices or returns.</sub>

</details>

<details>
<summary><b>Example · e-invoice QR log entry</b> <i>(synthetic data)</i></summary>

```json
{
  "scanned_at": "2026-01-15T10:42:07+05:30",
  "station": "GATE-01",
  "invoice_no": "INV-DEMO-0001",
  "seller_gstin": "00AAAAA0000A0Z0",
  "doc_date": "2026-01-14",
  "total_value": 11800.00,
  "status": "logged"
}
```

</details>

---

### 📊 GitHub Stats & Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=avviiiral&show_icons=true&hide_border=true&include_all_commits=true&theme=github_dark&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=avviiiral&layout=compact&hide_border=true&langs_count=8&theme=github_dark&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" alt="Top languages" />

<img src="https://streak-stats.demolab.com?user=avviiiral&hide_border=true&theme=github-dark-blue&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" alt="GitHub streak" />

<!-- Note: the public github-readme-stats instance is shared and can rate-limit.
     If the cards fail to load, self-host it on Vercel and swap the base URL. -->

</div>

---

### 🤝 Connect

<div align="center">

<a href="https://aviral-goyal.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-1f6feb?style=for-the-badge&logo=netlify&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/avviiiral/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://github.com/avviiiral"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>

<sub>Open to conversations on computer vision in manufacturing, full-stack Django/Angular systems, and analytics pipelines.</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1f6feb,100:0d1117&height=6&section=footer" width="100%" alt="" />
