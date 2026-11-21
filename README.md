 <!-- ===================== HEADER ===================== -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050816,50:14213D,100:5B21B6&height=220&section=header&text=CHIMERA&fontSize=75&fontColor=FFFFFF&fontAlignY=38&desc=AI-Powered%20Cyber%20Investigation%20%26%20Attack%20Graph%20Reconstruction&descSize=16&descAlignY=60&animation=fadeIn" width="100%" alt="CHIMERA Header"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=600&size=20&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=Turning+Fragmented+Logs+into+Connected+Intelligence;Reconstructing+Cyber+Attack+Stories;Investigating+Threats+with+Explainable+AI" alt="Typing SVG"/>

<br/><br/>

<img src="https://img.shields.io/badge/Project-Cybersecurity-7C3AED?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/AI-Powered-06B6D4?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Status-Hackathon%20Project-22C55E?style=for-the-badge"/>

<br/><br/>

**Turning fragmented security logs into a connected attack story.**

</div>

---

## 🧬 About CHIMERA

**CHIMERA** is an AI-powered cyber investigation platform designed to transform fragmented security logs into meaningful attack narratives.

Modern cyberattacks generate enormous amounts of security telemetry across multiple systems. These events are often scattered, delayed, and stored in different formats, making it difficult for security analysts to understand the complete attack sequence.

CHIMERA addresses this challenge by collecting, normalizing, correlating, and reconstructing security events into a connected attack graph.

It helps investigators understand:

- 🔍 What happened?
- 🕵️ Where did the attack originate?
- 🔗 How did the attacker move between systems?
- 🎯 Which users, devices, and services were affected?
- 🛡️ What actions should be considered for containment?

---

## ⚡ Core Capabilities

<table>
<tr>
<td width="50%">

### 🔎 Intelligent Log Analysis

Analyzes heterogeneous security logs from multiple sources.

</td>
<td width="50%">

### 🧩 Entity Resolution

Correlates users, IP addresses, devices, and VPN sessions.

</td>
</tr>
<tr>
<td width="50%">

### 🕸️ Attack Graph Reconstruction

Builds a time-ordered graph of suspicious activities.

</td>
<td width="50%">

### 🎯 Patient Zero Detection

Identifies the suspected initial compromised entity.

</td>
</tr>
<tr>
<td width="50%">

### 💥 Blast Radius Analysis

Helps visualize potentially affected accounts, devices, and services.

</td>
<td width="50%">

### 🤖 Explainable AI Dossier

Generates investigation insights with supporting log references.

</td>
</tr>
</table>

---

## 🏗️ System Architecture

CHIMERA follows a six-stage investigation pipeline:

```mermaid
flowchart TD
    A["📥 Security Log Collection"] --> B["⚙️ Log Normalization"]
    B --> C["🔍 Event Extraction"]
    C --> D["🧩 Entity Resolution"]
    D --> E["🕸️ Attack Graph Reconstruction"]
    E --> F["🤖 Explainable AI Dossier"]

    F --> G["🎯 Patient Zero"]
    F --> H["💥 Blast Radius"]
    F --> I["🛡️ Containment Recommendations"]

    style A fill:#172554,stroke:#38BDF8,color:#FFFFFF
    style B fill:#172554,stroke:#38BDF8,color:#FFFFFF
    style C fill:#172554,stroke:#38BDF8,color:#FFFFFF
    style D fill:#312E81,stroke:#818CF8,color:#FFFFFF
    style E fill:#312E81,stroke:#818CF8,color:#FFFFFF
    style F fill:#581C87,stroke:#C084FC,color:#FFFFFF
    style G fill:#164E63,stroke:#22D3EE,color:#FFFFFF
    style H fill:#164E63,stroke:#22D3EE,color:#FFFFFF
    style I fill:#164E63,stroke:#22D3EE,color:#FFFFFF
```

### 🔄 Investigation Workflow

| Stage | Description |
|---|---|
| 01. Collection | Collects Windows Sysmon, Firewall, and VPN logs |
| 02. Normalization | Converts different log formats into a canonical schema |
| 03. Event Extraction | Identifies suspicious activities using forensic rules |
| 04. Entity Resolution | Connects related IPs, users, devices, and sessions |
| 05. Graph Reconstruction | Builds a time-ordered attack graph |
| 06. AI Dossier | Presents explainable investigation findings |

---

## 🕸️ Attack Graph Reconstruction

CHIMERA connects isolated security events to reveal potential attack progression.

**Example investigation scenario:**

```text
        👤 jsmith@PC-001
                |
                ▼
       ⚠️ Suspicious PowerShell
                |
                ▼
       🔐 LSASS Credential Dump
                |
                ▼
          🌐 VPN Pivot
                |
                ▼
        🗄️ Database Server
                |
                ▼
        🚨 External C2 Server
         45.33.32.150
```

The reconstructed graph helps investigators follow suspicious activity across multiple entities and systems.

---

## 🛠️ Technology Stack

<div align="center">

### Programming & Data Processing

<img src="https://skillicons.dev/icons?i=python" alt="Python"/>
<img src="https://img.shields.io/badge/Pandas-Data%20Processing-150458?style=for-the-badge&logo=pandas&logoColor=white"/>

### Machine Learning & Graph Analysis

<img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/NetworkX-Graph%20Analysis-1F6FEB?style=for-the-badge"/>

### Dashboard & Visualization

<img src="https://skillicons.dev/icons?i=streamlit" alt="Streamlit"/>
<img src="https://img.shields.io/badge/PyVis-Network%20Visualization-6366F1?style=for-the-badge"/>

### AI & Threat Intelligence

<img src="https://img.shields.io/badge/Google-Gemini%20API-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
<img src="https://img.shields.io/badge/MITRE-ATT%26CK-CC0000?style=for-the-badge"/>

</div>

---

## 📊 Key Investigation Insights

- **Temporal Anomaly Detection:** Helps identify unusual event sequences and timing.
- **Attack Sequence Reconstruction:** Connects suspicious activities across systems.
- **Patient Zero:** Highlights the suspected initial compromised entity.
- **Blast Radius:** Provides a 0–100 impact score as described in the project design.
- **Evasion Detection:** Helps identify potentially skipped or concealed attack stages.
- **Explainability:** Provides investigation findings with supporting log references and MITRE ATT&CK mappings.

<sub>Note: Numerical performance figures presented in the hackathon presentation are project-reported results and should not be interpreted as independently validated benchmarks.</sub>

---

## 🧰 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/twinklee176/chimera-cyber-investigator.git
```

### 2. Navigate to the Project

```bash
cd chimera-cyber-investigator
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure Environment Variables

Create a `.env` file if the application uses API credentials:

```env
GEMINI_API_KEY=your_api_key_here
```

Do not commit API keys or other secrets to GitHub.

### 6. Run the Application

If your Streamlit entry point is `app.py`:

```bash
streamlit run app.py
```

> Verify the actual dependency filename and application entry point in the repository before running these commands.

---

## 📸 Project Preview

Add your actual application screenshots inside the `assets` folder.

<div align="center">

### Main Dashboard

<img src="assets/dashboard.png" width="90%" alt="CHIMERA Dashboard"/>

### Attack Graph Visualization

<img src="assets/attack-graph.png" width="90%" alt="Attack Graph"/>

### Patient Zero Analysis

<img src="assets/patient-zero.png" width="90%" alt="Patient Zero Analysis"/>

### Investigation Report

<img src="assets/investigation-report.png" width="90%" alt="Investigation Report"/>

</div>

---

## 🚀 Future Enhancements

- Real-time security log ingestion
- Integration with additional SIEM platforms
- Advanced threat intelligence enrichment
- Interactive attack graph exploration
- Automated incident response workflows
- Enhanced investigation report generation

---

## 👩‍💻 Project Contributors

CHIMERA was developed as a collaborative hackathon project.

<div align="center">

<a href="https://github.com/twinklee176">
  <img src="https://github.com/twinklee176.png" width="100" height="100" alt="Twinkle Mahato"/>
</a>
<a href="https://github.com/kashvinayak20-debug">
  <img src="https://github.com/kashvinayak20-debug.png" width="100" height="100" alt="Kashvinayak"/>
</a>
<a href="https://github.com/rajshree077">
  <img src="https://github.com/rajshree077.png" width="100" height="100" alt="Rajshree"/>
</a>
<a href="https://github.com/anmisha-dash">
  <img src="https://github.com/anmisha-dash.png" width="100" height="100" alt="Anmisha"/>
</a>

<br/>

| Contributor | GitHub |
|---|---|
| **Twinkle Mahato** | [@twinklee176](https://github.com/twinklee176) |
| Kashvinayak | [@kashvinayak20-debug](https://github.com/kashvinayak20-debug) |
| Rajshree | [@rajshree077](https://github.com/rajshree077) |
| Anmisha | [@anmisha-dash](https://github.com/anmisha-dash) |

</div>

---

## ⚠️ Disclaimer

CHIMERA is an academic and hackathon project intended for cybersecurity investigation and educational purposes. Its findings are investigative indicators and should be reviewed by qualified security professionals before any operational decisions are made.

---

<div align="center">

### 🧬 CHIMERA — Connect the Clues. Reconstruct the Attack.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:5B21B6,50:14213D,100:050816&height=120&section=footer" width="100%" alt="Footer"/>

</div>
