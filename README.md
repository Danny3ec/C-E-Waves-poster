# 📡 2.5 GHz Microstrip Patch Antenna (ADS Momentum)

Design and electromagnetic simulation of a **2.5 GHz square microstrip patch antenna** using **Keysight Advanced Design System (ADS) Momentum**.

The antenna is implemented on a **Rogers RT/Duroid 6010LM substrate** and uses an **inset-fed 50 Ω microstrip line** for impedance matching.

---

# ⚙️ Antenna Specifications

| Parameter                  | Value                   |
| -------------------------- | ----------------------- |
| Operating Frequency        | 2.5 GHz                 |
| Substrate                  | Rogers RT/Duroid 6010LM |
| Relative Permittivity (εr) | 10.7                    |
| Substrate Thickness        | 1.27 mm                 |
| Copper Thickness           | 35 µm                   |
| Feed Type                  | Inset-fed microstrip    |

---

# 🧠 Design Methodology

The antenna was designed using a combination of **analytical calculations** and **full-wave EM simulation**.

### Design steps

1. Initial patch dimensions calculated using **microstrip antenna theory**
2. Effective dielectric constant and **fringing field correction**
3. **50 Ω microstrip feedline design**
4. **Inset feed implementation** for impedance matching
5. **Optimization using ADS Momentum EM simulation**

---

# 📊 Simulation Results

Frequency sweep: **1 GHz – 4 GHz**

Final antenna performance:

| Parameter          | Result        |
| ------------------ | ------------- |
| Resonant Frequency | **2.501 GHz** |
| Return Loss (S11)  | **−11.99 dB** |

The design satisfies the typical antenna requirement:

```
S11 < −10 dB
```

indicating **good impedance matching**.

---

# 🧰 Tools Used

* **Keysight Advanced Design System (ADS)**
* **Momentum Electromagnetic Solver**

---

# 📂 Repository Contents

```
ADS_project/
│
├── antenna_layout/
├── substrate_stack/
├── EM_simulation/
├── S_parameter_results/
└── documentation/
```

---

# 📷 Example Simulation Result

![S11 Plot](images/Screenshot 2026-03-09-231755.png)

Example result:

```
Resonant frequency ≈ 2.501 GHz
Return loss ≈ −11.99 dB
```

---

# 👨‍💻 Author

Electrical Engineering project focused on **RF design and electromagnetic simulation of microstrip antennas**.

---

## ⭐ Topics

```
RF
Antenna Design
Microstrip Antenna
ADS Momentum
Electromagnetics
Microwave Engineering
```


