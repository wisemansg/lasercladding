#  Belt Finishing of Laser Cladded SS316L Surface🛠️

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Scanning%20Electron%20Microscopy%20(SEM)-00BFFF?logo=electron&logoColor=white" />
  <img src="https://img.shields.io/badge/Optical%20Microscopy-4A7043?logo=materialdesign&logoColor=white" />
  <img src="https://img.shields.io/badge/Contact%20Profilometer-2E8B57?logo=standard&logoColor=white" />
  <img src="https://img.shields.io/badge/Belt%20Finishing-FF6F00?logo=3dprinter&logoColor=white" />
  <img src="https://img.shields.io/badge/Materials%20Science-8B4513?logo=materialdesign&logoColor=white" />
</p>

---

This project studies the effect of belt finishing process on laser cladded SS316L surface using two different abrasive grain sizes (40 µm and 80 µm). The study evaluates the influence of finishing time and grit size on surface roughness (Ra, Rz) and bearing parameters (Rpk, Rk, Rvk) to achieve superfinished surfaces for high-performance applications.

## 1. Introduction

Belt finishing is a precision manufacturing process which utilizes abrasive belts to produce mirror polished metallic surfaces with very low surface roughness and induced compressive residual stress. It is widely used in automotive and aerospace sectors to enhance precision, performance, and reliability when combined with hard turning or laser cladding.

![Belt Finishing Process](https://github.com/wisemansg/beltfinishing/raw/main/assets/Belt%20finishing%20process.jpeg)

**Figure 1**: Belt finishing process

## 🎯 2. Objectives

- Predict the final roughness for turned laser cladded surface using belt finishing.
- Observe the effect of belt finishing using two different abrasive grit sizes (40 µm and 80 µm).
- Determine the required finishing time for each grit size to achieve desired surface quality.

## 🛠️ 3. Materials and Methods

![Laser Cladded Work Material](https://github.com/wisemansg/beltfinishing/raw/main/assets/(a)%20Laser%20cladded%20work%20material%2C%20(b)%2040-micron%20belt%20and%20(c)%2080-micron%20belt.jpeg)

**Figure 2**: (a) Laser cladded work material, (b) 40-micron belt and (c) 80-micron belt

![Belt Finishing Setup](https://github.com/wisemansg/beltfinishing/raw/main/assets/Belt%20and%20experimental%20setup%20(a)%2040%20%C2%B5m%2C%20(b)80%20%C2%B5m%20and%20(c)working%20principle%20.jpeg)

**Figure 3**: Belt and experimental setup (a) 40 µm, (b) 80 µm and (c) working principle

![Contact Profilometer](https://github.com/wisemansg/beltfinishing/raw/main/assets/Contact%20profilometer.jpeg)

**Figure 4**: Contact profilometer

**Table 4.1: Turning parameters**

| Parameter       | Value   | Units    |
|-----------------|---------|----------|
| Depth of cut    | 0.5     | mm       |
| Feed            | 0.2     | mm/rev   |
| Cutting speed   | 120     | m/min    |

**Table 4.2: Belt finishing conditions**

| Parameter                    | Value          | Units     |
|------------------------------|----------------|-----------|
| Alumina abrasive Grain size  | 80 and 40      | µm        |
| Pressure                     | 5              | Bar       |
| Belt feed rate               | 100            | mm/min    |
| Work material rotation speed | 120            | m/min     |
| Duration of time per operation | 10           | s         |
| Initial roughness (Ra)       | 2.008          | µm        |

## 📊 4. Results and Discussion

![Roughness Variation](https://github.com/wisemansg/beltfinishing/raw/main/assets/Variation%20of%20roughness%20with%20grain%20size%20and%20time.jpeg)

**Figure 5**: Variation of roughness with grain size and time

Belt finishing significantly reduces surface roughness over time. The Ra value decreases rapidly in the first 10–20 seconds, then slows down and stabilizes. Larger abrasive grains (80 µm) remove material faster initially, while smaller grains (40 µm) produce a finer final surface.

![Profile & Bearing Parameters](https://github.com/wisemansg/beltfinishing/raw/main/assets/Variation%20of%20profile%20and%20bearing%20parameters%20with%20grain%20size%20and%20time.jpeg)

**Figure 6**: Variation of profile and bearing parameters with grain size and time

![Percentage Drop 60s](https://github.com/wisemansg/beltfinishing/raw/main/assets/Percentage%20drop%20in%20roughness%20with%20grain%20size%20at%20end%20of%2060s.jpeg)

**Figure 7**: Percentage drop in roughness with grain size at end of 60s

- 80 µm belt: 76% reduction in Ra (from 2.008 µm to 0.466 µm)
- 40 µm belt: 67% reduction in Ra

![Percentage Drop per 10s](https://github.com/wisemansg/beltfinishing/raw/main/assets/Percentage%20drop%20in%20roughness%20with%20grain%20size%20at%20end%20of%20each%2010s.jpeg)

**Figure 8**: Percentage drop in roughness with grain size at end of each 10s

![Roughness after 60s](https://github.com/wisemansg/beltfinishing/raw/main/assets/Roughness%20based%20on%20grain%20size%20after%2060%20of%20belt%20finish.jpeg)

**Figure 9**: Roughness based on grain size after 60s of belt finish

![Bearing Parameters](https://github.com/wisemansg/beltfinishing/raw/main/assets/Influence%20of%20abrasive%20grain%20size%20on%20bearing%20parameters.jpeg)

**Figure 10**: Influence of abrasive grain size on bearing parameters

## 🚀 Applications of Belt Finishing

- Superfinishing of precision components in automotive and aerospace industries
- Improvement of surface integrity after laser cladding or hard turning
- Enhancement of wear resistance, fatigue life, and lubricant retention
- Achieving mirror-like surfaces with very low roughness (Ra < 0.1 µm)

## 📌 5. Conclusions

■ Belt finishing is highly effective for superfinishing laser cladded SS316L surfaces.  
■ Roughness and bearing parameters decrease significantly with smaller grain size and longer finishing time.  
■ Major improvement occurs in the first 10–20 seconds, followed by stabilization.  
■ The process produces plateau-like surfaces ideal for high-performance applications.

## 🛠️ Tools & Methods Used

- Belt Finishing System with Alumina abrasives (40 µm & 80 µm)
- CNC Turning Machine
- Contact Profilometer
- Optical Microscopy
- Python for data analysis and visualization
