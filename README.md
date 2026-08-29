<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=220&section=header&text=YUVRAJ%20MISHRA&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Electrical%20Engineering%20%7C%20VLSI%20%7C%20SoC%20%7C%20Analog%20%26%20Digital%20Design&descSize=17&descAlignY=58" width="100%"/>
<a href="https://github.com/Venom893">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2800&pause=900&color=2C9AB7&center=true&vCenter=true&width=750&lines=Designing+at+the+transistor+level.;Building+RTL+that+can+become+silicon.;Exploring+the+path+from+schematic+%E2%86%92+GDSII.;VLSI+%7C+SoC+%7C+Analog+%7C+RTL+%7C+Physical+Design" alt="Typing SVG"/>
</a>
<br>
<a href="https://github.com/Venom893">
<img src="https://img.shields.io/badge/GitHub-Venom893-161B22?style=for-the-badge&logo=github" />
</a>
<a href="https://www.linkedin.com/in/yuvraj-mishra-2u/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" />
</a>
<a href="mailto:yuvimishra5154@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<br><br>
<img src="https://komarev.com/ghpvc/?username=Venom893&style=flat-square&color=2C9AB7&label=PROFILE+VISITS" />
</div>
---
⚡ `whoami`
```text
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│  Yuvraj Mishra                                              │
│  Electrical Engineering Graduate                            │
│                                                             │
│  Focus → VLSI • SoC • Analog/Mixed-Signal • RTL             │
│                                                             │
│  Currently exploring:                                       │
│  Transistor-level design → RTL → Synthesis → Physical Design│
│                                                             │
│  Goal → Build things that eventually become silicon.        │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```
I'm an Electrical Engineering graduate fascinated by what happens between a circuit idea and actual silicon.
My work sits at the intersection of:
🔬 Transistor-level circuits  
🧩 RTL & digital logic  
🏗️ ASIC / SoC implementation  
⚙️ Physical design & verification
I like going deeper than simply making something "work" — understanding why the circuit behaves the way it does, how it can be modeled, verified, synthesized, implemented, and ultimately turned into a physical design.
---
🧠 THE CHIP-DESIGN JOURNEY
```text
        CIRCUIT
           │
           ▼
   ┌────────────────┐
   │ CMOS / Analog  │
   │ Mixed-Signal   │
   └───────┬────────┘
           │
           ▼
   ┌────────────────┐
   │ SPICE / Spectre│
   │ Verilog-A      │
   └───────┬────────┘
           │
           ▼
   ┌────────────────┐
   │ RTL            │
   │ Verilog / SV   │
   └───────┬────────┘
           │
           ▼
   ┌────────────────┐
   │ Synthesis      │
   │ Yosys          │
   └───────┬────────┘
           │
           ▼
   ┌────────────────┐
   │ Physical Design│
   │ OpenROAD / STA │
   └───────┬────────┘
           │
           ▼
        ┌──────┐
        │GDSII │
        └──────┘
           │
           ▼
        SILICON
```
> **From devices and waveforms → RTL → physical implementation → silicon.**
---
🔬 WHAT I LIKE TO BUILD
<table>
<tr>
<td width="50%">
🧪 Analog / Mixed-Signal
CMOS circuits
Transistor-level design
ESD protection
GGNMOS characterization
SPICE / Spectre simulation
Verilog-A behavioral modeling
Device behavior analysis
</td>
<td width="50%">
🏗️ Digital / SoC
SystemVerilog / Verilog RTL
Digital logic
RTL simulation
Synthesis
Timing analysis
Physical design
RTL-to-GDSII
</td>
</tr>
</table>
---
🚀 PROJECT LAB
`01` — ⚡ Fault Detection in a DG-Integrated Microgrid
MATLAB • Simulink • Power Systems
A simulation study of fault behavior in a 13-bus distributed-generation-integrated microgrid.
<details>
<summary><b>🔍 What happens inside?</b></summary>
<br>
Modeled a 13-bus DG-integrated microgrid
Investigated symmetrical and unsymmetrical faults
Studied LG, LL, LLG and ABG faults
Analyzed three-phase voltage/current signatures
Investigated DG penetration and its effect on fault current
Studied protection coordination and fault localization
<br>
🔗 Explore the project →  
https://github.com/Venom893/DG-Fault-Detection
</details>
---
`02` — 🔥 GGNMOS ESD Protection Cell
Cadence Virtuoso • Spectre • SPICE • Verilog-A • 90nm PDK
A transistor-level exploration of Gate-Grounded NMOS ESD protection, including device characterization and behavioral modeling.
<details>
<summary><b>🧪 What I explored</b></summary>
<br>
GGNMOS ESD protection clamp
90nm `gpdk090` PDK
SPICE characterization
Snapback behavior
Verilog-A behavioral macro-modeling
HBM transient analysis
PDK/model debugging
Spectre simulation
A particularly interesting part
A compact-model limitation prevented the expected bipolar snapback behavior.
Instead of treating it as a dead end, I investigated the device behavior and developed a custom Verilog-A behavioral model to reproduce the required negative-resistance behavior.
That led to deeper characterization of:
`Vt1 ≈ 9.0 V @ 3.98 mA`
`Vh ≈ 5.35 V @ 20.4 mA`
and verification of 2 kV HBM transient behavior.
</details>
---
`03` — 🧮 Low-Power MAC → RTL-to-GDSII
SystemVerilog • Yosys • OpenROAD • OpenSTA • Sky130
A digital ASIC implementation experiment focused on taking a 32-bit MAC/accumulator beyond RTL.
<details>
<summary><b>🏗️ From RTL to physical implementation</b></summary>
<br>
```text
SystemVerilog RTL
       ↓
   Simulation
       ↓
    Synthesis
       ↓
 Floorplanning
       ↓
  Placement
       ↓
     CTS
       ↓
    Routing
       ↓
   STA / Power
       ↓
   DRC / LVS
       ↓
     GDSII
```
The project involved:
RTL design in SystemVerilog
Synthesis with Yosys
Physical implementation
Timing analysis
Clock-tree analysis
Power/area analysis
DRC/LVS verification
Sky130-based implementation
</details>
---
🛠️ MY VLSI TOOLBOX
<div align="center">
🔬 Circuit & Analog
<img src="https://img.shields.io/badge/Cadence%20Virtuoso-B71C1C?style=flat-square"/>
<img src="https://img.shields.io/badge/Spectre-6A1B9A?style=flat-square"/>
<img src="https://img.shields.io/badge/SPICE-1565C0?style=flat-square"/>
<img src="https://img.shields.io/badge/Verilog--A-37474F?style=flat-square"/>
🧩 RTL & Digital
<img src="https://img.shields.io/badge/SystemVerilog-1565C0?style=flat-square"/>
<img src="https://img.shields.io/badge/Verilog-0D47A1?style=flat-square"/>
<img src="https://img.shields.io/badge/RTL%20Design-263238?style=flat-square"/>
<img src="https://img.shields.io/badge/Digital%20Logic-455A64?style=flat-square"/>
🏗️ ASIC / Physical Design
<img src="https://img.shields.io/badge/Yosys-212121?style=flat-square"/>
<img src="https://img.shields.io/badge/OpenROAD-00695C?style=flat-square"/>
<img src="https://img.shields.io/badge/OpenSTA-283593?style=flat-square"/>
<img src="https://img.shields.io/badge/Sky130-455A64?style=flat-square"/>
<img src="https://img.shields.io/badge/DRC%20%7C%20LVS-5D4037?style=flat-square"/>
💻 Engineering Stack
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/MATLAB-0076A8?style=flat-square"/>
<img src="https://img.shields.io/badge/Simulink-FF6F00?style=flat-square"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
</div>
---
🎓 CERTIFICATIONS
<table>
<tr>
<td>🏆</td>
<td><b>Maven Silicon</b></td>
<td>VLSI System on Chip Design – Overview</td>
</tr>
<tr>
<td>🏆</td>
<td><b>Simplilearn SkillUP</b></td>
<td>VLSI Design Course</td>
</tr>
<tr>
<td>🏆</td>
<td><b>Microsoft × LinkedIn</b></td>
<td>Career Essentials in Generative AI</td>
</tr>
</table>
---
📡 CURRENT SIGNAL
```text
[ VLSI / SoC ] ███████████████████░░  Learning
[ Analog IC  ] █████████████████░░░░  Building
[ RTL       ] ███████████████████░░░  Building
[ Physical  ] ████████████████░░░░░░  Exploring
[ Silicon   ] ██████████████████████  Goal
```
Currently exploring
`Analog IC Design` · `SoC Architecture` · `RTL Design` · `ASIC Flow`  
`Physical Design` · `Timing Analysis` · `Verification` · `Semiconductor Technology`
---
💡 A LITTLE MORE ABOUT ME
```text
╭────────────────────────────────────────────────────╮
│                                                    │
│  🎓 Electrical Engineering Graduate                │
│                                                    │
│  🔬 I enjoy transistor-level circuit exploration   │
│                                                    │
│  🧩 I enjoy turning logic into synthesizable RTL   │
│                                                    │
│  🏗️ I'm exploring how RTL becomes physical silicon │
│                                                    │
│  🐛 I actually enjoy debugging simulation issues   │
│                                                    │
│  🚀 Long-term goal: build better silicon           │
│                                                    │
╰────────────────────────────────────────────────────╯
```
---
🌐 FIND ME
<div align="center">
<a href="https://github.com/Venom893">
<img src="https://img.shields.io/badge/🧑‍💻_GitHub-Explore_My_Work-161B22?style=for-the-badge"/>
</a>
<a href="https://www.linkedin.com/in/yuvraj-mishra-2u/">
<img src="https://img.shields.io/badge/💼_LinkedIn-Let's_Connect-0A66C2?style=for-the-badge"/>
</a>
<a href="mailto:yuvimishra5154@gmail.com">
<img src="https://img.shields.io/badge/✉️_Email-Say_Hello-EA4335?style=for-the-badge"/>
</a>
</div>
---
<div align="center">
⚡ `Think → Design → Simulate → Verify → Implement → Silicon`
<br>
Thanks for stopping by.
If chip design interests you too, we probably have something to talk about. 🔬
</div>
