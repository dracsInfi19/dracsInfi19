<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,50:0B3048,100:00D9FF&height=230&section=header&text=DRACSINFI19&fontSize=64&fontColor=FFFFFF&fontAlignY=40&animation=fadeIn&desc=Engineering%20the%20hardware%20behind%20everything&descSize=18&descAlignY=62&descColor=9FE9FF"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2800&pause=900&color=00D9FF&center=true&vCenter=true&width=720&lines=VLSI+%7C+RTL+%7C+Verilog;Approximate+Computing+Research;4%3A2+Compressors+%E2%86%92+Multipliers;Embedded+Systems+%7C+ESP32+%7C+Arduino;Learn+%E2%86%92+Build+%E2%86%92+Measure+%E2%86%92+Optimize"/>

<br>

<a href="#about"><img src="https://img.shields.io/badge/ABOUT-020617?style=for-the-badge&labelColor=020617&color=00D9FF"/></a>
<a href="#stack"><img src="https://img.shields.io/badge/STACK-020617?style=for-the-badge&labelColor=020617&color=7C3AED"/></a>
<a href="#research"><img src="https://img.shields.io/badge/RESEARCH-020617?style=for-the-badge&labelColor=020617&color=FF8C00"/></a>
<a href="#projects"><img src="https://img.shields.io/badge/PROJECTS-020617?style=for-the-badge&labelColor=020617&color=00D9FF"/></a>
<a href="#skills"><img src="https://img.shields.io/badge/SKILLS-020617?style=for-the-badge&labelColor=020617&color=7C3AED"/></a>
<a href="#connect"><img src="https://img.shields.io/badge/CONNECT-020617?style=for-the-badge&labelColor=020617&color=FF8C00"/></a>

<br><br>

<img src="https://img.shields.io/badge/◉_STATUS-ONLINE-00D9FF?style=flat-square&labelColor=020617"/>
<img src="https://img.shields.io/badge/◉_FOCUS-VLSI-7C3AED?style=flat-square&labelColor=020617"/>
<img src="https://img.shields.io/badge/◉_MODE-RESEARCH-FF8C00?style=flat-square&labelColor=020617"/>
<img src="https://komarev.com/ghpvc/?username=dracsInfi19&style=flat-square&color=00D9FF&label=PROFILE+VIEWS&labelColor=020617"/>

</div>

<br>

<a id="about"></a>

## 🧠 About

I'm an **Electronics & Communication Engineering student** who wants to understand how hardware connects end to end:

```text
CIRCUIT → LOGIC → ARCHITECTURE → RTL → HARDWARE → SYSTEM → RESEARCH
```

<table>
<tr>
<td align="center" width="33%">

**⚡ ELECTRONICS**<br>
Digital Systems<br>
Embedded Hardware<br>
Communication

</td>
<td align="center" width="33%">

**🧬 VLSI**<br>
RTL Design<br>
Verilog<br>
Computer Arithmetic

</td>
<td align="center" width="33%">

**🔬 RESEARCH**<br>
Approximate Computing<br>
4:2 Compressors<br>
Multiplier Architectures

</td>
</tr>
</table>

<details>
<summary><b>🎯 Currently focused on</b> &nbsp;(click to expand)</summary>

<br>

```text
BUILDING      ██████████████████░░  90%
LEARNING      ████████████████░░░░  80%
RESEARCH      ███████████████░░░░░  75%
```

> Bars show where my time and attention go right now, not formal proficiency scores.

</details>

---

<a id="stack"></a>

## ⚙️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=c,cpp,python,java,git,github,vscode,linux,arduino,raspberrypi&theme=dark"/>

<br><br>

<img src="https://img.shields.io/badge/VERILOG-RTL-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/VLSI-CMOS-7C3AED?style=for-the-badge"/>
<img src="https://img.shields.io/badge/APPROXIMATE-COMPUTING-00A8CC?style=for-the-badge"/>
<img src="https://img.shields.io/badge/EMBEDDED-ESP32-E7352C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/QUANTUM-COMMUNICATION-C026D3?style=for-the-badge"/>

</div>

<table>
<tr>
<td align="center" width="25%"><b>💻 Software</b><br>Python · C · C++ · Java<br>Git · GitHub</td>
<td align="center" width="25%"><b>🔲 Digital</b><br>Logic Gates · Boolean Algebra<br>Combinational · Sequential</td>
<td align="center" width="25%"><b>🧬 VLSI</b><br>Verilog · RTL<br>Compressors · Multipliers · CMOS</td>
<td align="center" width="25%"><b>🔧 Hardware</b><br>Arduino · ESP32<br>Sensors · Actuators</td>
</tr>
</table>

---

<a id="research"></a>

## 🔬 Research: Approximate Computing

<div align="center">

### `4:2 COMPRESSORS → MULTIPLIERS → HARDWARE EFFICIENCY`

<img src="https://img.shields.io/badge/RESEARCH-ACTIVE-00D9FF?style=for-the-badge&labelColor=020617"/>
<img src="https://img.shields.io/badge/DOMAIN-VLSI-7C3AED?style=for-the-badge&labelColor=020617"/>
<img src="https://img.shields.io/badge/TOPIC-ARITHMETIC-FF8C00?style=for-the-badge&labelColor=020617"/>

</div>

<br>

I study how small arithmetic approximations trade **accuracy** against **power, area and delay**, starting from approximate 4:2 compressors and building up to multiplier trees.

> **How much accuracy are we willing to trade for hardware efficiency?**

<details>
<summary><b>🔢 4:2 compressor and multiplier flow</b></summary>

<br>

```text
 X1 X2 X3 X4 CIN
   └──┴──┴──┴──┘
        │
   ┌────▼─────┐
   │ 4:2 COMP │──► SUM, CARRY, COUT
   └──────────┘

PARTIAL PRODUCTS → COLUMN REDUCTION (HA / FA / 4:2) → FINAL ADDER → PRODUCT
```

Compressors cut the number of partial-product rows before the final addition, which makes compressor design a natural starting point for multiplier architectures.

</details>

<details>
<summary><b>📐 Error metrics I track</b></summary>

<br>

| Metric | What it tells me |
|:---|:---|
| Error Distance | Gap between exact and approximate output |
| Error Rate | How often the approximation produces an error |
| Mean Error | Average error magnitude |
| Worst Case Error | Maximum error |
| Power / Area / Delay | Hardware efficiency gained |

</details>

<details>
<summary><b>❓ Questions I'm working through</b></summary>

<br>

1. What exactly is a 4:2 compressor, and how does the exact design work?
2. What changes in an approximate architecture?
3. Which truth-table combinations introduce errors, and how large are they?
4. How do errors propagate through a compressor tree and a multiplier?
5. What happens to power, area and delay?
6. Where is approximation actually useful?

</details>

<details>
<summary><b>📚 Research workflow</b></summary>

<br>

```text
Find papers → Read → Take notes → Reproduce → Compare
   → Find limits → Research gap → Design → RTL / Verilog
   → Simulate → Analyse → Improve
```

For every paper I extract: **problem · existing design · proposed design · truth table · error analysis · area / power / delay · limitations · research gap.**

</details>

<details>
<summary><b>💻 RTL / Verilog journey</b></summary>

<br>

```text
Boolean algebra → Logic gates → Combinational → Sequential
   → Verilog → Modules → Testbenches → Simulation
   → RTL → Synthesis → Area / Power / Delay → VLSI
```

</details>

---

<a id="projects"></a>

## 🚀 Project Lab

<table>
<tr>
<td width="33%" valign="top" align="center">

### 🚗 Vehicle Black Box
**ESP32 experimental system**

`GPS` `IMU` `RTC` `Audio`<br>`Data Logging` `Wi-Fi`

Detects events, logs them with time and location, and uploads the data for analysis.

</td>
<td width="33%" valign="top" align="center">

### 📡 Radar System
**Arduino sensing system**

`HC-SR04` `PIR` `Servo`<br>`LED` `Buzzer` `Serial`

Sweeps with a servo, detects objects and motion, and reports through LED, buzzer and serial.

</td>
<td width="33%" valign="top" align="center">

### 🌌 Quantum Communication
**BB84-inspired experiment**

`Polarization` `QBER`<br>`Basis Comparison`

Explores polarized weak-laser communication, key generation and eavesdropper simulation.

</td>
</tr>
</table>

<details>
<summary><b>🔍 Project architectures</b></summary>

<br>

```text
VEHICLE BLACK BOX     ESP32 ← GPS + IMU + RTC → Event detection → Logging + Audio → Wi-Fi upload
RADAR SYSTEM          Arduino ← HC-SR04 + PIR + Servo → Processing → LED / Buzzer / Serial
QUANTUM COMM          Sender → Polarization → Weak laser → Free space → Detection
                      → Basis comparison → Key → QBER → Security analysis
```

</details>

---

<a id="skills"></a>

## 🧠 Skills

<details open>
<summary><b>Skill matrix</b> &nbsp;🟢 comfortable &nbsp;·&nbsp; 🟡 growing</summary>

<br>

<div align="center">

| Domain | Skill | Level |
|:---|:---|:---:|
| Digital | Logic Gates · Boolean Algebra · Computer Arithmetic | 🟢 |
| HDL | Verilog | 🟢 |
| HDL | RTL | 🟡 |
| VLSI | Approximate Computing · Compressor Design | 🟢 |
| VLSI | CMOS Fundamentals · Multiplier Architecture | 🟡 |
| Programming | Python | 🟢 |
| Programming | C / C++ · Java · DSA | 🟡 |
| Embedded | Arduino · ESP32 | 🟢 |
| Research | Paper Reading · Literature Review | 🟢 |
| Research | Gap Identification | 🟡 |
| Quantum | Communication | 🟡 |

</div>

</details>

<details>
<summary><b>📈 Learning progress</b></summary>

<br>

```text
Digital Electronics    ██████████████████░░  90%
Embedded Systems       ██████████████░░░░░░  70%
Verilog / RTL          █████████████░░░░░░░  65%
Research               █████████████░░░░░░░  65%
VLSI Fundamentals      ████████████░░░░░░░░  60%
Approximate Computing  ███████████░░░░░░░░░  55%
Quantum Communication  ████████░░░░░░░░░░░░  40%
```

</details>

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=dracsInfi19&show_icons=true&hide_border=true&bg_color=020617&title_color=00D9FF&icon_color=7C3AED&text_color=C9D1D9"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dracsInfi19&layout=compact&hide_border=true&bg_color=020617&title_color=00D9FF&text_color=C9D1D9"/>

</div>

---

<a id="connect"></a>

## 🔗 Connect

<div align="center">

<a href="https://github.com/dracsInfi19"><img src="https://img.shields.io/badge/GitHub-dracsInfi19-000000?style=for-the-badge&logo=github&logoColor=white"/></a>

<br><br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=16&duration=3000&pause=1500&color=00D9FF&center=true&vCenter=true&width=520&lines=Always+learning.;Always+building.;Always+researching."/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D9FF,50:0B3048,100:020617&height=100&section=footer"/>

</div>
