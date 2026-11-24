<div align="center">

<img src="https://raw.githubusercontent.com/dracsInfi19/dracsInfi19/main/assets/hero.svg" alt="DRACSINFI19 — animated 3D chip hero" width="100%"/>

<br>

<a href="https://vichaar-adarsh.vercel.app/"><img src="https://img.shields.io/badge/%E2%96%B6_LIVE_PORTFOLIO-vichaar--adarsh.vercel.app-00D9FF?style=for-the-badge&labelColor=020617"/></a>
<a href="https://www.linkedin.com/in/adarsh-s-vajrawad-4ba66b386"><img src="https://img.shields.io/badge/LINKEDIN-Adarsh_S_Vajrawad-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=020617"/></a>

<br><br>

<a href="#portfolio"><img src="https://img.shields.io/badge/PORTFOLIO-00D9FF?style=for-the-badge&labelColor=020617"/></a>
<a href="#snapshot"><img src="https://img.shields.io/badge/SNAPSHOT-7C3AED?style=for-the-badge&labelColor=020617"/></a>
<a href="#research"><img src="https://img.shields.io/badge/RESEARCH-FF8C00?style=for-the-badge&labelColor=020617"/></a>
<a href="#repos"><img src="https://img.shields.io/badge/REPOS-00D9FF?style=for-the-badge&labelColor=020617"/></a>
<a href="#projects"><img src="https://img.shields.io/badge/PROJECTS-7C3AED?style=for-the-badge&labelColor=020617"/></a>
<a href="#connect"><img src="https://img.shields.io/badge/CONNECT-FF8C00?style=for-the-badge&labelColor=020617"/></a>

<br><br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=2800&pause=900&color=00D9FF&center=true&vCenter=true&width=760&lines=Designing+approximate+4%3A2+compressors+for+efficient+multipliers;Writing+Verilog+RTL+%E2%86%92+simulate+%E2%86%92+measure+%E2%86%92+optimize;Building+a+pipelined+RISC-V+core+with+a+custom+instruction;Building+ESP32+%26+LoRa+systems+that+sense+the+real+world;Reading+papers+until+I+find+the+research+gap"/>

<br>

<img src="https://img.shields.io/badge/◉_STATUS-ONLINE-00D9FF?style=flat-square&labelColor=020617"/>
<img src="https://img.shields.io/badge/◉_FOCUS-VLSI-7C3AED?style=flat-square&labelColor=020617"/>
<img src="https://img.shields.io/badge/◉_MODE-RESEARCH-FF8C00?style=flat-square&labelColor=020617"/>
<img src="https://komarev.com/ghpvc/?username=dracsInfi19&style=flat-square&color=00D9FF&label=PROFILE+VIEWS&labelColor=020617"/>

</div>

<img src="https://raw.githubusercontent.com/dracsInfi19/dracsInfi19/main/assets/divider.svg" width="100%"/>

<a id="portfolio"></a>

## 🌐 Portfolio

<div align="center">

<a href="https://vichaar-adarsh.vercel.app/"><img src="https://raw.githubusercontent.com/dracsInfi19/dracsInfi19/main/assets/portfolio-card.svg" alt="Open the interactive 3D portfolio" width="100%"/></a>

<br>

<a href="https://vichaar-adarsh.vercel.app/"><img src="https://img.shields.io/badge/%E2%96%B6_OPEN_PORTFOLIO-00D9FF?style=for-the-badge&labelColor=020617"/></a>
<a href="https://vichaar-adarsh.vercel.app/repos.html"><img src="https://img.shields.io/badge/GITHUB_REPOS-7C3AED?style=for-the-badge&labelColor=020617"/></a>
<a href="https://vichaar-adarsh.vercel.app/contact.html"><img src="https://img.shields.io/badge/CONTACT-FF8C00?style=for-the-badge&labelColor=020617"/></a>

</div>

<details>
<summary><b>🧪 What's inside the portfolio</b> &nbsp;(click to expand)</summary>

<br>

| Page | What you get |
|:---|:---|
| [**About me**](https://vichaar-adarsh.vercel.app/) | Bio, education, a draggable **3D silicon chip** (three.js) and an interactive **full-adder lab** |
| [**GitHub repos**](https://vichaar-adarsh.vercel.app/repos.html) | Pulled live from the GitHub API, with filters |
| [**Contact**](https://vichaar-adarsh.vercel.app/contact.html) | Opens your mail app with the message pre-filled |

Built with plain HTML, CSS and JavaScript plus three.js, with no build step. It respects reduced-motion settings and falls back gracefully without WebGL.

</details>

<img src="https://raw.githubusercontent.com/dracsInfi19/dracsInfi19/main/assets/divider.svg" width="100%"/>

<a id="snapshot"></a>

## 🧠 Snapshot

> **I'm an Electronics & Communication Engineering student who wants to understand hardware end to end: from the transistor to the system to the research paper.**

<table>
<tr>
<td width="50%" valign="top">

**🎓 Education**<br>
BE Electronics & Communication Engineering (2nd year)<br>
Cambridge Institute of Technology, Bengaluru

**🎯 Primary focus**<br>
VLSI · RTL design · Computer arithmetic · Approximate computing

</td>
<td width="50%" valign="top">

**🛠️ I work with**<br>
Verilog · Python · C / C++ · Java · Git<br>
Arduino · ESP32 · LoRa · Sensors · Wireless communication

**🤝 Open to**<br>
Research collaboration · VLSI / hardware projects · Internships

</td>
</tr>
</table>

```text
CIRCUIT → LOGIC → ARCHITECTURE → RTL → HARDWARE → SYSTEM → RESEARCH
```

<div align="center">

<img src="https://skillicons.dev/icons?i=c,cpp,python,java,git,github,vscode,linux,arduino,raspberrypi&theme=dark"/>

</div>

<img src="https://raw.githubusercontent.com/dracsInfi19/dracsInfi19/main/assets/divider.svg" width="100%"/>

<a id="research"></a>

## 🔬 Research: Approximate Computing

**The question I'm chasing:** *how much accuracy can a circuit give up in exchange for lower power, smaller area and faster delay?*

Approximate arithmetic is useful where small errors are tolerable, such as image and signal processing and machine-learning inference. A multiplier's partial-product reduction tree is built from compressors, so I start with the **4:2 compressor** and work up to the multiplier.

<details>
<summary><b>🔢 The exact 4:2 compressor (my baseline)</b></summary>

<br>

```text
inputs : X1 X2 X3 X4 CIN        outputs : SUM, CARRY, COUT

X1 + X2 + X3 + X4 + CIN  =  SUM + 2 × (CARRY + COUT)

SUM   = X1 ⊕ X2 ⊕ X3 ⊕ X4 ⊕ CIN
COUT  = (X1 ⊕ X2) ? X3 : X1
CARRY = (X1 ⊕ X2 ⊕ X3 ⊕ X4) ? CIN : X4
```

An approximate design simplifies these equations. Some of the 32 input combinations then give a wrong output, and the job is to measure how wrong, how often, and what is saved.

</details>

<details>
<summary><b>📐 How I evaluate a design</b></summary>

<br>

| Metric | What it tells me |
|:---|:---|
| Error Rate | How often the output is wrong |
| Error Distance | Gap between exact and approximate output |
| Mean / Worst-case Error | Average and maximum damage |
| Power · Area · Delay | What the approximation actually buys |

```text
truth table → error distance → error pattern → multiplier effect → application effect → research gap
```

</details>

<details>
<summary><b>📚 My paper-reading workflow</b></summary>

<br>

```text
find → read → note → reproduce → compare → find limits → research gap → design → Verilog → simulate → analyse → improve
```

For each paper I extract: **problem · existing design · proposed design · truth table · error analysis · area / power / delay · limitations · research gap.**

My reviewed papers live in [Review-Papers](https://github.com/dracsInfi19/Review-Papers).

</details>

<details>
<summary><b>💻 RTL / Verilog roadmap</b></summary>

<br>

```text
Boolean algebra → gates → combinational → sequential → Verilog modules
   → testbenches → simulation → RTL → synthesis → area / power / delay → VLSI
```

</details>

<img src="https://raw.githubusercontent.com/dracsInfi19/dracsInfi19/main/assets/divider.svg" width="100%"/>

<a id="repos"></a>

## 📦 Repositories

| Repo | What's in it |
|:---|:---|
| [**Gods-Hand**](https://github.com/dracsInfi19/Gods-Hand) | LoRa mesh SOS system for flood scenarios: gateway engine, simulator, 23 unit tests, web dashboard |
| [**Review-Papers**](https://github.com/dracsInfi19/Review-Papers) | Reviewed research papers with notes |
| [**RESEARCH-PAPERS**](https://github.com/dracsInfi19/RESEARCH-PAPERS) | Deep learning and research of quantum domains |
| [**Classical-Projects**](https://github.com/dracsInfi19/Classical-Projects) | Classical engineering projects |
| [**Python_practice**](https://github.com/dracsInfi19/Python_practice) | Python practice problems in one place |
| [**SipkeCenter-X-Adarsh**](https://github.com/dracsInfi19/SipkeCenter-X-Adarsh) | An educational website (HTML) |

<a id="projects"></a>

## 🚀 Project Lab

<table>
<tr>
<td width="33%" valign="top" align="center">

### [📡 Gods Hand](https://github.com/dracsInfi19/Gods-Hand)
**LoRa mesh SOS system**

`Python` `LoRa` `ESP32` `Dijkstra` `DBSCAN` `Kalman`

Gateway engine for flood scenarios: link-quality routing, SOS validation, priority scoring, GPS refinement and a web dashboard. 23 unit tests. Node firmware and drone verification in progress.

</td>
<td width="33%" valign="top" align="center">

### 🔲 RISC-V Core
**Pipelined RTL · in progress**

`Verilog` `RISC-V` `Pipeline` `Testbench`

Pipelined RISC-V core in Verilog with one custom instruction. Goal: measured speedup against area cost.

</td>
<td width="33%" valign="top" align="center">

### 🌌 Quantum Communication
**BB84-inspired experiment**

`Polarization` `QBER`

Explores polarized weak-laser communication, key generation and eavesdropper simulation.

</td>
</tr>
</table>

<details>
<summary><b>🧠 Skill matrix</b> &nbsp;🟢 comfortable · 🟡 growing</summary>

<br>

| Domain | Skill | Level |
|:---|:---|:---:|
| Digital | Logic gates · Boolean algebra · Computer arithmetic | 🟢 |
| HDL | Verilog | 🟢 |
| HDL | RTL | 🟡 |
| VLSI | Approximate computing · Compressor design | 🟢 |
| VLSI | CMOS fundamentals · Multiplier architecture | 🟡 |
| Programming | Python | 🟢 |
| Programming | C / C++ · Java · DSA | 🟡 |
| Algorithms | Dijkstra routing · DBSCAN clustering · Kalman filtering | 🟡 |
| Embedded | Arduino · ESP32 | 🟢 |
| Embedded | LoRa mesh networking | 🟡 |
| Research | Paper reading · Literature review | 🟢 |
| Research | Gap identification | 🟡 |
| Quantum | Communication | 🟡 |

</details>

<img src="https://raw.githubusercontent.com/dracsInfi19/dracsInfi19/main/assets/divider.svg" width="100%"/>

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=dracsInfi19&show_icons=true&hide_border=true&bg_color=020617&title_color=00D9FF&icon_color=7C3AED&text_color=C9D1D9"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dracsInfi19&layout=compact&hide_border=true&bg_color=020617&title_color=00D9FF&text_color=C9D1D9"/>

</div>

<a id="connect"></a>

## 🔗 Connect

<div align="center">

<a href="https://vichaar-adarsh.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-vichaar--adarsh.vercel.app-00D9FF?style=for-the-badge&logo=vercel&logoColor=white&labelColor=020617"/></a>
<a href="https://www.linkedin.com/in/adarsh-s-vajrawad-4ba66b386"><img src="https://img.shields.io/badge/LinkedIn-Adarsh_S_Vajrawad-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=020617"/></a>
<a href="mailto:adarshsv14@gmail.com"><img src="https://img.shields.io/badge/Email-adarshsv14%40gmail.com-FF8C00?style=for-the-badge&logo=gmail&logoColor=white&labelColor=020617"/></a>
<a href="https://github.com/dracsInfi19"><img src="https://img.shields.io/badge/GitHub-dracsInfi19-7C3AED?style=for-the-badge&logo=github&logoColor=white&labelColor=020617"/></a>

<br><br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=16&duration=3000&pause=1500&color=00D9FF&center=true&vCenter=true&width=520&lines=Always+learning.;Always+building.;Always+researching."/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D9FF,50:0B3048,100:020617&height=100&section=footer"/>

</div>
