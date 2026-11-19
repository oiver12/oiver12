<div align="center">

# Oliver Baumgartner
### Robotics · Learning · Building

**MSc Robotics, Systems and Control @ ETH Zürich · ESOP Scholar**  
Reinforcement learning under partial observability · Memory · World models · Robot learning  
From custom PCBs to learning agents—I like turning ambitious ideas into working systems.

[![Website](https://img.shields.io/badge/Website-oliverbaumgartner.com-111827?style=flat-square)](https://oliverbaumgartner.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let’s_connect-0A66C2?style=flat-square)](https://www.linkedin.com/in/oliver-baumgartner-371291300/)

</div>

---

## 🔬 Current research

<table>
<tr>
<td width="45%" valign="top">
<a href="https://github.com/oiver12/predictive-fsc"><img src="https://raw.githubusercontent.com/oiver12/predictive-fsc/main/assets/navigation-demo.gif" alt="MAPO controller navigating a POMDP grid with noisy beacon observations" width="100%"></a>
</td>
<td width="55%" valign="top">

### 🧠 [MAPO](https://github.com/oiver12/predictive-fsc) — *Predictive Initialization of Finite-State Controllers for POMDPs*
<sub><b>O. Baumgartner</b>, N. Schmid, L. Cregg, K. Wallington, J. Lygeros · Automatic Control Laboratory, ETH Zürich · 2026 (manuscript)</sub>

Policy iteration on finite-state controllers gets stuck because memory is only useful once a later action reads it. **MAPO** learns a small *predictive* memory from simulated trajectories, distills it into a controller, and hands policy iteration a far better starting point.

| **17 / 22** | **4** | **≈5,000×** |
| :---: | :---: | :---: |
| benchmarks matched or beaten vs. FiVI | memory states solve long-horizon navigation | smaller policies than FiVI |

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Docker](https://img.shields.io/badge/Reproducible-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
</tr>
</table>

<details>
<summary><b>📄 Cite</b></summary>

```bibtex
@unpublished{baumgartner2026predictive,
  title  = {Predictive Initialization of Finite-State Controllers for {POMDPs}},
  author = {Baumgartner, Oliver and Schmid, Niklas and Cregg, Liam and Wallington, Kevin and Lygeros, John},
  note   = {Unpublished manuscript},
  year   = {2026}
}
```

</details>

---

## 🛠️ Flagship build

<table>
<tr>
<td width="55%" valign="top">

### 🪂 [VariometerV2](https://github.com/oiver12/VariometerV2)
<sub><b>2021 – 2024</b> · PCB → firmware → flight-tested · built by hand, pre-AI</sub>

A paragliding instrument engineered from the ground up and flown on my own harness. Years of evenings spent on schematics, firmware and filter tuning.

- 🔌 Three custom **KiCad PCB** revisions
- ⚙️ **ESP32** firmware on ESP-IDF + FreeRTOS
- 🧭 Quaternion orientation + **Kalman** baro/IMU fusion
- 🖥️ E-ink UI with a custom rendering engine
- 🔁 Host simulation and recorded-flight replay

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)

</td>
<td width="45%" valign="top">
<a href="https://github.com/oiver12/VariometerV2"><img src="https://raw.githubusercontent.com/oiver12/VariometerV2/main/docs/images/photo-device-in-flight.jpeg" alt="VariometerV2 mounted on a paragliding harness in flight" width="100%"></a>
</td>
</tr>
</table>

---

## ⚡ More projects

👣 **[Step_Detector](https://github.com/oiver12/Step_Detector)**  
Turning raw sensor data into motion estimates on STM32—with my own Kalman filter, quaternion orientation, FreeRTOS and wireless recording control.

🧩 **[Rubics-Cube-Solver](https://github.com/oiver12/Rubics-Cube-Solver)**  
Taking on an iconic puzzle through code—exploring the algorithms behind solving the Rubik’s Cube.

📡 **[Variometer-Maturarbeit](https://github.com/oiver12/Variometer-Maturarbeit)**  
Where my flight-instrument journey began—an Arduino variometer combining estimation research, C# simulation and Bluetooth app support.

🚀 **[tailtoss](https://github.com/oiver12/tailtoss)**  
AirDrop for my tailnet—a Rust app bringing drag-and-drop file transfers and clipboard sync to the COSMIC desktop through Tailscale.

---

<div align="center">

### 📈 On GitHub

<img src="https://github-readme-stats.vercel.app/api?username=oiver12&show_icons=true&hide_border=true&theme=transparent&hide_rank=true" alt="Oliver's GitHub stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=oiver12&layout=compact&hide_border=true&theme=transparent&langs_count=6&hide=G-code" alt="Most used languages" height="165" />

</div>
