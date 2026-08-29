<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,45:1D4ED8,100:06B6D4&height=190&section=header&text=YUVRAJ%20MISHRA&fontSize=44&fontColor=FFFFFF&animation=fadeIn&fontAlignY=35" width="100%"/>

<a href="https://readme-typing-svg.demolab.com">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=18&duration=2500&pause=800&color=38BDF8&center=true&vCenter=true&width=760&height=45&lines=Electrical+Engineering+Graduate;VLSI+%7C+SoC+%7C+IC+Design;RTL+%E2%86%92+GDSII+%E2%86%92+Silicon;Designing%2C+debugging%2C+learning+%E2%9A%A1" alt="Typing animation"/>
</a>

<br>

<a href="https://github.com/Venom893">
<img src="https://img.shields.io/badge/⚡_GITHUB-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>
<a href="https://www.linkedin.com/in/yuvraj-mishra-">
<img src="https://img.shields.io/badge/🔗_LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:yuvimishra5154@gmail.com">
<img src="https://img.shields.io/badge/✉️_EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=Venom893&style=for-the-badge&color=06B6D4&label=VISITORS" alt="Profile visitors"/>

</div>

---

<div align="center">

### 🧠 `A transistor is where the story starts — not where it ends.`

**Circuit** → **RTL** → **Verification** → **Synthesis** → **Physical Design** → **GDSII** → **Silicon**

</div>

---

## 👋 `whoami`

I'm an **Electrical Engineering graduate** interested in the engineering layers that turn an idea into hardware.

My curiosity lives around **VLSI, SoC, analog/mixed-signal IC design, RTL, ASIC implementation and physical design**.

I like projects where I can go deeper than the final output:

> **What happened? → Why did it happen? → How can I verify it? → How does it become hardware?**

---

## 🔭 THE HARDWARE STACK I'M EXPLORING

<table>
<tr>
<td align="center" width="33%">

### 🔬 CIRCUIT

Transistors  
CMOS  
Analog / Mixed-Signal  
ESD  
SPICE

</td>
<td align="center" width="33%">

### 🧩 RTL

Verilog  
SystemVerilog  
Digital Logic  
MAC / Datapaths  
Verification

</td>
<td align="center" width="33%">

### 🏗️ SILICON

Synthesis  
STA  
CTS  
Placement  
Routing  
DRC / LVS  
GDSII

</td>
</tr>
</table>

---

## 🛠️ MY SILICON TOOLBOX

<p align="center">

<img src="https://skillicons.dev/icons?i=python,cpp,c,java,matlab,linux,docker,git,github&perline=9" />

<br><br>

<img src="https://img.shields.io/badge/Cadence%20Virtuoso-CC0000?style=for-the-badge" />
<img src="https://img.shields.io/badge/Spectre-7B1FA2?style=for-the-badge" />
<img src="https://img.shields.io/badge/SPICE-1565C0?style=for-the-badge" />
<img src="https://img.shields.io/badge/SystemVerilog-1E88E5?style=for-the-badge" />
<img src="https://img.shields.io/badge/Verilog-546E7A?style=for-the-badge" />
<img src="https://img.shields.io/badge/Yosys-37474F?style=for-the-badge" />
<img src="https://img.shields.io/badge/OpenROAD-2E7D32?style=for-the-badge" />

</p>

---

# 🚀 PROJECT LAB

### 🔋 Low-Power MAC — RTL → GDSII

<details>
<summary><b>⚡ Open the project → see what happened under the hood</b></summary>

<br>

A **32-bit MAC/accumulator** taken through an ASIC implementation flow.

```text
RTL
 ↓
Simulation
 ↓
Synthesis
 ↓
Floorplan
 ↓
Power Planning
 ↓
Placement
 ↓
CTS
 ↓
Routing
 ↓
STA / DRC / LVS
 ↓
GDSII
```

**Tools:** `SystemVerilog` · `Yosys` · `OpenROAD` · `OpenSTA` · `Magic`

### 📊 Reported results

| Metric | Result |
|---|---:|
| ⏱️ Clock | **100 MHz** |
| 📐 Area | **5,062 µm²** |
| 📊 Utilization | **16%** |
| ⚡ Power | **0.864 mW** |
| ✅ DRC | **0 violations** |
| 🔍 LVS | **431 / 431 matched** |

<a href="https://github.com/Venom893/Low-Power-MAC-Sky130--RTL-to-GDSII">
<img src="https://img.shields.io/badge/🔎_OPEN_PROJECT-2563EB?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</details>

---

### 🛡️ GGNMOS ESD Protection

<details>
<summary><b>🔬 Open the project → enter the transistor-level world</b></summary>

<br>

A **Gate-Grounded NMOS (GGNMOS)** ESD protection design explored using a **90nm gpdk090 PDK**.

**Tools & concepts**

`Cadence Virtuoso` · `Spectre` · `SPICE` · `Verilog-A` · `ESD` · `Snapback` · `HBM`

### ⚡ Characterization

```text
Trigger voltage (Vt1) → 9.0 V @ 3.98 mA
Holding voltage (Vh)   → 5.35 V @ 20.4 mA
HBM stress             → 2 kV
```

The work involved transistor-level simulation, behavioral modeling and investigation of device/tool behavior.

<a href="https://github.com/Venom893/GGNMOS-ESD-Protection-Cadence">
<img src="https://img.shields.io/badge/🔎_OPEN_PROJECT-2563EB?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</details>

---

### 🌐 DG-Integrated 13-Bus Microgrid

<details>
<summary><b>⚡ Open the project → explore the fault analysis</b></summary>

<br>

A **MATLAB/Simulink** study of fault behavior in a distributed-generation integrated microgrid.

**Explored**

`LG` · `LL` · `LLG` · `ABG` faults  
Three-phase voltage/current behavior  
Distributed generation  
Fault-current analysis  
Protection coordination

<a href="https://github.com/Venom893/DG-Fault-Detection">
<img src="https://img.shields.io/badge/🔎_OPEN_PROJECT-2563EB?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</details>

---

## 🎯 MY FAVORITE PART OF ENGINEERING

<div align="center">

```text
Something doesn't work.
        ↓
"Interesting..."
        ↓
Measure it.
        ↓
Find the weird behaviour.
        ↓
Understand the cause.
        ↓
Fix it.
        ↓
Verify it.
        ↓
Learn something new.
```

### 🐛 Bugs are annoying.

### 🔬 Understanding why they happened is fun.

</div>

---

## 🏆 CERTIFICATIONS

<details>
<summary><b>🎓 Click to explore certifications</b></summary>

<br>

**🟢 Maven Silicon**  
VLSI – System on Chip (SoC) Design

**🔵 Simplilearn SkillUp**  
VLSI Design Course

**🟣 Microsoft + LinkedIn**  
Career Essentials in Generative AI

</details>

---

## 🎮 EASTER EGG

<details>
<summary><b>👀 You found the hidden section.</b></summary>

<br>

```text
          ┌─────────────────────────────┐
          │       SILICON MINDSET       │
          ├─────────────────────────────┤
          │                             │
          │  Learn the abstraction.     │
          │  Then look underneath it.  │
          │                             │
          │  Learn the tool.            │
          │  Then understand the tool. │
          │                             │
          │  Fix the bug.               │
          │  Then understand the bug.  │
          │                             │
          └─────────────────────────────┘
```

☕ Coffee helps.  
🔬 Curiosity helps more.  
⚡ Building things helps most.

</details>

---

## 🧭 WHERE I'M HEADING

```text
Electrical Engineering
        │
        ├── 🔬 Analog / Mixed-Signal
        │
        ├── 🧩 RTL / Digital Design
        │
        └── 🏗️ ASIC / SoC
                │
                ├── Synthesis
                ├── STA
                ├── Physical Design
                └── GDSII
                        ↓
                     SILICON
```

I'm building depth across these layers because I want to understand **the complete hardware journey**, not just one stage of it.

---

## 🤝 IF YOU LIKE THIS KIND OF STUFF...

<div align="center">

**VLSI** · **SoC** · **IC Design** · **RTL** · **Physical Design** · **Semiconductors**

<br>

<a href="https://github.com/Venom893">
<img src="https://img.shields.io/badge/⚡_EXPLORE_MY_GITHUB-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="https://www.linkedin.com/in/yuvraj-mishra-">
<img src="https://img.shields.io/badge/🔗_CONNECT_ON_LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:yuvimishra5154@gmail.com">
<img src="https://img.shields.io/badge/✉️_SAY_HELLO-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<br><br>

### ⚡ Think → Design → Simulate → Verify → Implement → Silicon

<br>

<sub>Thanks for stopping by. 👋</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,55:2563EB,100:0F172A&height=110&section=footer" width="100%"/>
