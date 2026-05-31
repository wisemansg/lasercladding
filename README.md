#  Laser Cladding of SS316L on 42CrMo4 Substrate🔬

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Scanning%20Electron%20Microscopy%20(SEM)-00BFFF?logo=electron&logoColor=white" />
  <img src="https://img.shields.io/badge/Energy%20Dispersive%20Spectroscopy%20(EDS)-00BFFF?logo=electron&logoColor=white" />
  <img src="https://img.shields.io/badge/Optical%20Microscopy-4A7043?logo=materialdesign&logoColor=white" />
  <img src="https://img.shields.io/badge/Laser%20Cladding-FF6F00?logo=3dprinter&logoColor=white" />
  <img src="https://img.shields.io/badge/Cold%20Spray-8B4513?logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/Materials%20Science-8B4513?logo=materialdesign&logoColor=white" />
</p>

---

This project investigates laser cladding (LC) of SS316L powder on 42CrMo4 substrate and compares it with cold spray (CS) deposition. The study optimizes powder feed rate and track overlap, and evaluates geometry, microstructure, dilution, and hardness.

## 1. Introduction

In the field of additive manufacturing, deposition methods vary widely based on material characteristics and application requirements. This section offers insight into laser cladding (LC) and compares an LC deposit with a cold spray (CS) coating. LC finds extensive application in rapid manufacturing, parts restoration, surface coating, and novel alloy development. LC enables coatings ranging from 50 µm to 2 mm. Cold spray uses a supersonic gas jet for deposition while largely preserving the powder microstructure.

## 🎯 2. Objectives

The aim is to optimize laser cladding parameters and compare results with a cold spray deposit of the same powder. Specific objectives include:
1. Finding the optimal feed rate for a height to width ratio of 0.2 of the clad track.
2. Examining the effect of different overlapping coefficients.
3. Analyzing the microstructure of the LC deposit compared to cold spray.

## 🛠️ 3. Material and Parameters

**Substrate**: 42CrMo4 (42CD4) alloy steel  
**Powder**: PTA SS316L austenitic stainless steel  
**CS Substrate**: 6000 series Aluminium

**Table 3.1: 42CD4 substrate composition**

| Element | Fe       | C        | Si   | Mn       | P     | S     | Cr       | Mo      |
|---------|----------|----------|------|----------|-------|-------|----------|---------|
| wt%     | 96.8–97.8| 0.38-0.45| 0.40 | 0.60-0.90| 0.025 | 0.035 | 0.90-1.20| 0.15-0.30 |

**Table 3.2: SS316L powder composition**

| Element | Fe      | Ni     | C    | Si   | Mn  | P     | S     | Cr      | Mo     |
|---------|---------|--------|------|------|-----|-------|-------|---------|--------|
| wt%     | 61.9-72 | 10-14  | 0.07 | 0.75 | 2.0 | 0.045 | 0.030 | 0.90-1.20 | 2.00-3.00 |

![Coaxial Laser Cladding](https://github.com/wisemansg/lasercladding/raw/main/assets/Coaxial%20laser%20cladding%20deposition%20schematic.jpeg)

**Figure 3.1**: Coaxial laser cladding deposition schematic

**Table 3.3: Laser cladding parameters**

| Parameter          | Value | Units |
|--------------------|-------|-------|
| Operating distance | 13    | mm    |
| Laser power        | 3     | kW    |
| Speed              | 1     | m/min |

![Clad Beam Cross-section](https://github.com/wisemansg/lasercladding/raw/main/assets/Clad%20beam%20cross-section%20.jpeg)

**Figure 3.2**: Clad beam cross-section

## 📊 5. Results and Discussion

![Single Clad Tracks](https://github.com/wisemansg/lasercladding/raw/main/assets/Single%20clad%20tracks.jpeg)

**Figure 3.3a**: Single clad tracks

![Feed Rate Thickness](https://github.com/wisemansg/lasercladding/raw/main/assets/Clad%20thickness%20for%20increasing%20feed%20rate.jpeg)

**Figure 3.3b**: Clad thickness for increasing feed rate

**Table 3.4: Feed rate effect on deposit size**

| Track # | Feed rate (rpm) | Group 1 | Group 2 | Group 3 | Group 4 |
|---------|-----------------|---------|---------|---------|---------|
| 1       | 7.5             | 46.4    | -       | -       | -       |
| 2       | 8.5             | 46.7    | 46.6    | 46.6    | 45.7    |
| 3       | 9.5             | 47      | 47      | 46.9    | 45.9    |
| 4       | 10.5            | 47.2    | 47.3    | 47.2    | 46.3    |
| 4       | 11.5            | -       | 47.6    | 47.4    | -       |

![Overlap](https://github.com/wisemansg/lasercladding/raw/main/assets/30%25%2050%25%2070%25%20overlap.jpeg)

**Figure 3.4a**: 30% 50% 70% overlap

**Table 3.5: Overlap effect on deposit size**

| Track overlap (%) | Group 1 | Group 2 | Group 3 | Group 4 |
|-------------------|---------|---------|---------|---------|
| 30                | 45.8    | 46.9    | 46.8    | 46.8    |
| 40                | 46      | 47.1    | 47.0    | -       |
| 50                | -       | 47.4    | 47.4    | -       |
| 70                | -       | -       | -       | 47.9    |

![Single Track Reconstruction](https://github.com/wisemansg/lasercladding/raw/main/assets/Single%20track%20optical%20microscopy%20reconstruction.jpeg)

**Figure 3.5**: Single track optical microscopy reconstruction

![Dilution 20x](https://github.com/wisemansg/lasercladding/raw/main/assets/SS316L%20powder%20geometric%20dilution%20in%20the%20substrate%20(OM%2020x%20magnification).jpeg)

**Figure 3.6a**: SS316L geometric dilution (OM 20x)

![Dilution 5x](https://github.com/wisemansg/lasercladding/raw/main/assets/SS316L%20powder%20geometric%20dilution%20in%20the%20substrate%20(OM%205x%20magnification).jpeg)

**Figure 3.6b**: SS316L geometric dilution (OM 5x)

![HAZ](https://github.com/wisemansg/lasercladding/raw/main/assets/316L%20on%2042CD4%20HAZ%20penetration.jpeg)

**Figure 3.7**: 316L on 42CD4 HAZ penetration

![CS Interface](https://github.com/wisemansg/lasercladding/raw/main/assets/Cold%20spray%20(CS)%20optical%20microscopy%20observations%20(CS%20interface).jpeg)

**Figure 3.8a**: Cold spray optical microscopy (interface)

![CS Cracked](https://github.com/wisemansg/lasercladding/raw/main/assets/Cold%20spray%20(CS)%20optical%20microscopy%20observations%20(Cracked%20sample).jpeg)

**Figure 3.8b**: Cold spray optical microscopy (cracked sample)

![SEM LC vs CS](https://github.com/wisemansg/lasercladding/raw/main/assets/LC%20(a)%20and%20CS%20(b)%20BSE%20SEM%20imaging.jpeg)

**Figure 3.9**: LC (a) and CS (b) BSE SEM imaging

![Elemental Mapping](https://github.com/wisemansg/lasercladding/raw/main/assets/LC%20(a)%20and%20CS%20(b)%20elemental%20mapping.jpeg)

**Figure 3.10**: LC (a) and CS (b) elemental mapping

![Microhardness](https://github.com/wisemansg/lasercladding/raw/main/assets/Microhardness%20variation%20along%20clad%20deposit%20and%20substrate.jpeg)

**Figure 3.11**: Microhardness variation along clad deposit and substrate

**Table 3.6: CS sample micro hardness**

| Measure | Load (g) | Hardness (HV) |
|---------|----------|---------------|
| 1       | 200      | 350.1         |
| 2       | 200      | 354.5         |
| 3       | 200      | 306.5         |
| 4       | 200      | 259.7         |
| 5       | 200      | 192.1         |

## 🚀 Applications of Laser Cladding

- Surface repair and restoration of high-value components
- Wear and corrosion resistant coatings
- Rapid manufacturing and functionally graded materials
- Aerospace, automotive, oil & gas, and tooling industries

## 📌 Conclusions

■ Optimal parameters: 8.5 rpm feed rate and 30% overlap gave uniform coating of ~0.81 mm per layer.  
■ Good metallurgical bonding with minimal dilution (~10 µm).  
■ Significant hardness improvement in LC clad layer.  
■ Cold spray showed higher hardness but lower ductility and some defects.

## 🛠️ Tools & Methods Used

- Laser Cladding System  
- Cold Spray System  
- Optical Microscopy (OM)  
- Scanning Electron Microscopy (SEM) + EDS  
- Vickers Microhardness Testing  
- Python for analysis
